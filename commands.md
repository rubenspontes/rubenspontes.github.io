# watch sass stylesheets
sass --watch assets/css:assets/css

# browser-sync
> static sites
browser-sync start --server --files "*.html, *.css"

> php
browser-sync start --proxy "myproject.dev" --files "*.php, assets/css/*.css"

> wordpress
browser-sync start --proxy localhost/wordpress --files "*.css, *.php"

# start http server
http-server [path]