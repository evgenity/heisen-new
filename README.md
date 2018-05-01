# Quick install

## Docker dev
```
docker run --rm --volume="$PWD:/srv/jekyll" -p 35729:35729 -p 4000:4000 -it jekyll/jekyll jekyll serve
```

## Cloud9 dev
```
sudo apt update
sudo apt-get install ruby ruby-dev build-essential
bundle install 
jekyll serve --port 8080 --host 0.0.0.0
```
