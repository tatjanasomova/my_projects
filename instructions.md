jekyll new .source/repos/<your_site_name>
bundle exec jekyll serve
bundle exec jekyll serve --draft

https://{username}.github.io/{repositoryname}.

Open the _config.yml file and add the following:
url: tomjoht.github.io
baseurl: /myreponame


curl -u 'USER' https://api.github.com/user/repos -d '{"tatjanasomova":"test"}'


git init
git init -b main
git add
# Adds the files in the local repository and stages them for commit. To unstage a file, use 'git reset HEAD YOUR-FILE'.
git add .gitignore
git commit -m "First commit"
# Commits the tracked changes and prepares them to be pushed to a remote repository. To remove this commit and modify the file, use 'git reset --soft HEAD~1' and commit and add the file again.
# git remote add origin somova.tatjana@gmail.com:tanya-somova/<som_projects>.git
git remote add origin tatjana.somova@mottmac.com:tatjanasomova/<my_projects>.git
git remote add origin git@github.com:alexpchin/<reponame>.git

git init -b gh-pages
git checkout -b gh-pages
git commit -m "First commit"
git push -u origin gh-pages
git remote add origin https://github.com/tanya-somova/som_projects.git
# Sets the new remote
git remote -v
Verifies the new remote URL