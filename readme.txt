tag 1.0.5

execute

php artisan vendor:publish --provider="Jerickcm\pkgs_db\\BlogPackageServiceProvider" --tag="migrations"


echo "/vendor/" > .gitignore
git init
git checkout -b master
git add .
git commit -m "Initial commit"
git tag 1.0.0

// packages/fhsinchy/inspire

git remote add origin git@github.com:jerickcm/pkgs_db.git
git push -u origin --all
git push -u origin --tags
https://github.com/jerickcm/pkgs_db.git
