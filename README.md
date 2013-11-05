# Github Downloader

This shell script takes a github website path to any file/folder on github and using `svn export` downloads just that file/folder from github.

# Usage

`./github-downloader [website url to file/folder]`

#Example

`./github-downloader https://github.com/twbs/bootstrap/tree/master/examples/carousel`

This will export the carousel example folder from the twitter boostrap project.

```./github-downloader https://github.com/twbs/bootstrap/tree/master/examples/carousel/carousel.css```

This will export just the carousel.css file from the twitter boostrap project.

