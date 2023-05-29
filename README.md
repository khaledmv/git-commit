
## Git repository

- git add .
- git commit -m " < update text > "
- git branch -M Main
- git remote add origin
- git push -u origin Main
- git rm --cache assets/*.css.map
- git checkout -b < new branch >
- Remove Gti cached code is-  git rm -rf --cached .

## Git new branch
- Add -- git checkout -b < new branch >
- Delete -- git push < remote > --delete < branch >
- Link -- <a href="https://www.atlassian.com/git/tutorials/using-branches/git-checkout#:~:text=New%20Branches&text=The%20git%20branch%20command%20can,to%20switch%20to%20that%20branch."> Git new branch help </a>

## …or push an existing repository from the command line
- git remote add origin https://github.com/khaledmv/{git-name}.git
- git branch -M Main
- git push -u origin Main


## Git Remote check
- git remote -v



## Laravel Helper

- Enable debug query 
-> \DB::enableQueryLog();
->    view()->render();
-> dd(\DB::getQueryLog());


## Image path Helper

  $imageUrl = "";
        
        if(!is_null($this->image)){
            $imagePath = public_path() . "/img/" . $this->image;
            if(file_exists($imagePath)) $imageUrl = asset("img/" . $this->image);
        }
 return $imageUrl;
 
 
 ## laravel Mail 
 php artisan vendor:publish --tag=laravel-mail
 
 ## Django -- 
 
 - py -m venv project-name
 - project-name\Scripts\activate.bat
 - py -m pip install Django
 - django-admin startproject mysite
 - py manage.py runserver

  
  
  ## Windows helper
  - SFC /SCANNOW
  - DISM /Online /Cleanup-Image /CheckHealth
  - DISM /Online /Cleanup-Image /ScanHealth
  - DISM /Online /Cleanup-Image /RestoreHealth
