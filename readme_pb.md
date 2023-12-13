# create local repo, connect it to master on github
# (already uploaded the ssh key to central github settings
# to test: ssh git@github.com
git clone git@github.com:prbnbaral/prbnbaral.github.io.git
git remote add origin git@github.com:prbnbaral/prbnbaral.github.io.git

# edit _config.yml
git add _config.yml
git add images/profile.jpg # the edited/newly added file
git status #status check
git add images/* #all images copied
git commit -m 'upload profile images, etc'
git status "status changed
git push #final push

for initial setup with jeykyll, run
	bundle install
once, then to "compile" and serve up the website locally, run:
	bundle exec jekyll serve
