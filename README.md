# Hexo-theme-wen

A terse and clear hexo theme. Crafted from scratch with love.

Inspired by [Todd Motto](https://toddmotto.com)

## Live Preview

[Preview](http://hopsken.com)

## Installation

Clone this repository into your theme folder:
```sh
$ cd hexo
$ git clone https://github.com/Hopsken/hexo-theme-wen themes/wen
```

Set `theme` in main hexo root config file: `_config.yml`
```
theme: wen
```

## Config

Set up [gitment](https://github.com/imsun/gitment) in the theme config file.
```
# theme/wen/_config.yml

gitment:
  enable: true
  github_id: #your github id
  repo: #the repo to save comments, commonly your github pages repo
  client_id: #github oath2 client_id
  client_secret: #github oath2 client_secret
```
For detail usage, check [here](https://github.com/imsun/gitment).

Or you can use disqus
```
disqus: #your disqus id
```

## LICENSE
MIT
