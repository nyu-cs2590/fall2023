## Compile the website on github
Typically if you're only making minor changes to the `.md` files, you can just push it to the remote. Github should build and deploy it automatically.
You can check if deployment is successful and the logs under 'Deployment' on the right sidebar.

## Compile the website locally
The site is built by Jekyll. To compile it locally, you will need to install Ruby 2.7.1 (or above).

I'm using rbenv to set up the environment.
```
rbenv local 2.7.1
[path to .rbenv]/shims/bundle install
```

To build and serve the site locally, run
```
[path to .rbenv]/shims/bundle exec jekyll serve
```
