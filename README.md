# Welcome to Simplicity
## A (really) simple blog theme for hexo

- It's black & white. CSS come from [Bolt CSS](https://boltcss.com/)
- Icons from [Eva Icons](https://github.com/akveo/eva-icons)
- No outsource script (Google Analytics, Disqus, whatever). I will never implement it. KISS
- Tags supported. Summary page with all the tags and their posts (/tags)
- No categories (not yet and maybe ever)
- No pages (not yet and maybe ever)
- No gallery image.
- No search module.

## Installation
Install the theme by using :
$ git clone https://github.com/g-coomans/hexo-theme-simplicity themes/simplicity

Then update your blog's main `_config.yml` to set the theme to `simplicity`:

i.e:

``` yaml
# Extensions
## Plugins: http://hexo.io/plugins/
## Themes: http://hexo.io/themes/
theme: simplicity
```

## Post Configuration
Each post supports the standard `title` & `date`.

## Theme Configuration
The theme's global configuration is done in `/themes/simplicity/_config.yml`.

## Menu
Setup the links in header & footer to your social pages (or what you want)  in the theme's `_config.yml` as an array of objects.

Example:

``` yaml
menu:
  - name: Home
    link: /
    icon: home
  - name: Tags
    link: /tags
    icon: folder
  - name: Archives
    link: /archives
    icon: archive
  - name: Github
    link: https://github.com/*user_repos*
    icon: github
  - name: Linkedin
    link: https://www.linkedin.com/in/*user_profile*
    icon: linkedin
tags_title: Tags summary
```

# Creator
This theme was created by Geoffrey Coomans, check out my [github](https://github.com/g-coomans).

## Contributions
Contributions are welcome!

1. Fork it.
2. Create your feature branch: git checkout -b my-new-feature
3. Commit your changes: git commit -am 'Add some feature'
4. Push to the branch: git push origin my-new-feature
5. Submit a pull request :D

If you have a question, feature request or a bug you need me to fix, please [click here](https://github.com/g-coomans/hexo-theme-simplicity/issues/new) to file an issue.

## License
MIT

## Hexo themes
I like this ones:
- [next](https://github.com/next-theme/hexo-theme-next)
- [minimalism](https://github.com/f-dong/hexo-theme-minimalism/blob/master/README_EN.md)
- [brewksi](https://github.com/tiaanduplessis/hexo-theme-brewski)

Enjoy :)
