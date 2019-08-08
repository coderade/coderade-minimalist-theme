
# coderade-minimalist-theme

This project contains the source code for the theme used on my [blog].

This theme is based on the on the Hugo theme 
[hugo-minimalist-theme](https://github.com/digitalcraftsman/hugo-minimalist-theme) that by the way is based
[Minimalistic](https://github.com/rriegger/MinimalisticBlogTheme)
Ghost theme made by [Raphael Riegger](https://github.com/rriegger) am.

Noteworthy features of this Hugo theme are the integration of a comment-system
powered by Disqus, easy localization (l10n), support for RSS feeds, tags and categories,
syntax highlighting for source code and sharing options in the blog posts.

![](images/screenshot.png)

## Preview & Installation


### Installation

If you want to use this theme for an actual website create a new Hugo project and clone the theme:

    cd themes
    git clone https://github.com/digitalcraftsman/hugo-minimalist-theme.git

**Note:** make sure to remove `themesDir = "../.."` from the top of your config file if you copied it from `exampleSite/config.toml`. 
Otherwise, Hugo will be unable to find the theme.

For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### The Config File

Take a look inside the [`exampleSite`](https://github.com/coderade/coderade-minimalist-theme/tree/master/exampleSite) folder of this theme.
You'll find a file called [`config.toml`](https://github.com/coderade/coderade-minimalist-theme/blob/master/exampleSite/config.toml).

To use it, copy the [`config.toml`](https://github.com/coderade/coderade-minimalist-theme/blob/master/exampleSite/config.toml)
 to the root folder of your Hugo site.
Play around with the settings to tweak your site as you like.

## Localization (l10n)

Localization allows you to easily translate all strings in our website.
Within [`exampleSite/data`](https://github.com/coderade/coderade-minimalist-theme/tree/master/exampleSite/data) you'll find a file called [`l10n.toml`](https://github.com/coderade/coderade-minimalist-theme/blob/master/exampleSite/data/l10n.toml).
If you're not blogging in English replace all strings with their equivalents of your preferred language.

## Contributing

Did you find a bug or have an idea for a new feature?
Feel free to use the [issue tracker](https://github.com/coderade/coderade-minimalist-theme/issues)
to let me know. Or create a [pull request](https://github.com/coderade/coderade-minimalist-theme/pulls).
**Please create a seperate branch for your pull request.**

## License

This theme is released under the Apache License 2.0.
For more information read the [License](https://github.com/coderade/coderade-minimalist-theme/blob/dev/LICENSE.md).

## Acknowledgements

Thanks to 
        
- [Raphael Riegger](https://github.com/rriegger) for creating the original theme
- [digitalcraftsman](https://github.com/digitalcraftsman) for porting the original theme to Hugo
- [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project
