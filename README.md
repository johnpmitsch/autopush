# autopush

autopush to git on file changes

`brew install watchman`

Running

`watchman-make -p '**/*.js' '**/*.html' '**/*.css' --run  "git add -A && git commit -m 'updated' && git push origin master"`

will autopush to git on file changes
