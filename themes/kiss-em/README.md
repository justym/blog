# Kiss'Em

Kiss'Em is a fork of the [Kiss](https://github.com/ribice/kiss) Hugo theme. It is **E**ven **M**ore simple (hence the name Kiss'**Em**), because I stripped all JavaScript and removed any analytics/social integration. At least, I hope I did...

I use it for my own blog, which can be found [here](https://blog.pavel-pi.de "Pi's Blog").

## Translation

Right now, the theme supports the two languages English and German, which can be set with the `defaultContentLanguage` parameter within the `config.toml` file. 

## Site Configuration


To align images, add #c for center, #r/l for right/left.

```md
![](/img/1/image.jpg#c)
```

#### Changing Social Menu Icons Order

If you want to change the order of the social menu icons, modify the `[params.social.config]` section of your `config.toml` file:

```toml
[params.social.config]
platforms = ["github","facebook","twitter","instagram","email","codepen","linkedin"]
```

The social menu icons will appear in the order you specify in the `platforms` array.


## Related Articles

To include related articles in the bottom of the content, set params.info.related to true.
By default up to 5 articles will be shown (can be changed by cloning related.html) and only older ones.

To change the behaviour of how related articles are generated, check [official docs on Related Content](https://gohugo.io/content-management/related/).

## Creating Articles


Create a new blog post:

```
$ hugo new blog/my-first-blog-post.md
```

Create a new microblog post:

```
$ hugo new micro/my-first-microblog-post.md
```

## License

Kiss'Em is licensed under the MIT license. Check the [LICENSE](LICENSE.md) file for details.


## Author

[Pavel Pi](https://blog.pavel-pi.de)