# recette-cookies
> Une recette gourmande :p

## Pour désindexer les fichiers après les avoir mis dans .gitignore 

git filter-branch --index-filter 'git rm --cached mdp.password-local mdp.password-prod' HEAD
