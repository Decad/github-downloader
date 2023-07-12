# ⚠⚠⚠⚠⚠  Deprecation Notice ⚠⚠⚠⚠⚠ 

Note github is [removing SVN support](https://github.blog/2023-01-20-sunsetting-subversion-support/) on January 8, 2024. This project will no longer work after this date.

# Github Downloader

This shell script takes a github website path to any file/folder on github and using `svn export` downloads just that file/folder from github.

# Usage

`./github-downloader [website url to file/folder]`

# Example

`./github-downloader https://github.com/Decad/github-downloader/blob/master/README.md`

This will download just the README.md file from this repo, you can also download whole directories
