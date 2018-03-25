# PhpStorm Tweaks For Laravel Projects

> This is a collection of minor PhpStorm tweaks for Laravel projects.

## Markdown Style

In case you're using the
[Markdown Navigator Plugin](https://plugins.jetbrains.com/plugin/7896-markdown-navigator) (which I
think you should) it has an option to customize the stylesheet.

### Styles Available

| Style            | File                                               | What it is                                                                   |
|:-----------------|:---------------------------------------------------|:-----------------------------------------------------------------------------|
| Laravel          | [md/laravel-2018.css](md/laravel.css)              | The original laravel.com/docs style (except for the copyrighted Whitney font |
| Laravel Readable | [md/laravel-readable.css](md/laravel-readable.css) | The laravel.com/docs style with improved readability                         |
| Vanilo           | [md/vanilo.css](md/vanilo.css)                     | vanilo.io/docs style                                                         |

### Setting Styles For Markdown Documents

> Install the
> [Markdown Navigator Plugin](https://plugins.jetbrains.com/plugin/7896-markdown-navigator) if you
> haven't done it yet.

1. In PhpStorm go to Settings => Languages and Frameworks => Markdown => Preview
2. Set **Preview Browser** to _JavaFX WebView_
3. Tick **Grayscale Font Smoothing**
4. Navigate to the Stylesheet pane on the left
5. Set **Scheme** to _Default_ (so that document bg is white)
6. Set **Stylesheet** to _Default JavaFX Stylesheet_
7. Tick **Apply Custom CSS text**
8. Copy and paste the content of one of the CSS files linked above

#### Laravel Markdown Style

![Markdown Navigator Laravel Style](md/preview_laravel.png)

#### Laravel Readable Markdown Style

![Markdown Navigator Laravel Readable Style](md/preview_laravel-readable.png)

#### Vanilo Markdown Style

![Markdown Navigator Vanilo Style](md/preview_vanilo.png)
