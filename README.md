## Bulma with SCSS

The documentation HTML is produced with the Ruby-based `jekyll` tool.

1. Make sure Ruby 2.x is installed.
2. `gem install jekyll`

## Viewing the documentation locally

Then to view the documentation in your local checkout:
1. In a separate shell session do:
```
jekyll serve -w
```
This will start an HTTP server at `http://localhost:4000/` that serves the docs built in the `_site` directory; and anytime the docs are rebuilt by you, it will serve the docs site on the fly.
