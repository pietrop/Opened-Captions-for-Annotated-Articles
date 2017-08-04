# Optional: Publish to github pages - draft

- Install git if you don't have it 
<!-- link to github documentaiton -->
- Create repo in github 
- Follow instructions to do first commit and link to remote
<!-- copy and paste here -->

For example 

<!-- …or create a new repository on the command line -->

```bash
echo "# test_repo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:pietrop/test_repo.git
git push -u origin master
```

<!--
…or push an existing repository from the command line
```
git remote add origin git@github.com:pietrop/test_repo.git
git push -u origin master
```
-->

- Activate github pages from `docs` folder in settings. 


[Simpler GitHub Pages publishing](https://github.com/blog/2228-simpler-github-pages-publishing) using `docs` folder in master branch.

[Github pages documentation ](https://help.github.com/categories/github-pages-basics/)


## Documentation 
- [Installing git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Create repo in github](https://help.github.com/articles/create-a-repo/)