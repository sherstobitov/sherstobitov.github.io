# sherstobitov.com

## Run locally via Docker

```sh
# run in current project directory
docker run --rm --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve --force_polling
```
