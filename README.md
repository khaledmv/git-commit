
## Git repository

- git add .
- git commit -m " < update text > "
- git branch -M Main
- git remote add origin
- git push -u origin Main
- git rm --cache assets/*.css.map
- git checkout -b < new branch >

## Git new branch
- Add -- git checkout -b < new branch >
- Delete -- git push < remote > --delete < branch >
- Link -- <a href="https://www.atlassian.com/git/tutorials/using-branches/git-checkout#:~:text=New%20Branches&text=The%20git%20branch%20command%20can,to%20switch%20to%20that%20branch."> Git new branch help </a>


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
