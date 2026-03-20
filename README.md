# SolidState

A [Statiq Web](https://statiq.dev/web) theme based on the [Solid State](https://html5up.net/solid-state) design by [HTML5 UP](https://html5up.net), converted from the [Wyam SolidState theme](https://github.com/Wyamio/Wyam/tree/develop/themes/Blog/SolidState) using [CleanBlog](https://github.com/statiqdev/CleanBlog) as a template.

## Usage

Add this theme to your Statiq Web project by referencing it as a theme. See the [Statiq documentation](https://statiq.dev/web/themes) for details on using themes.

## Settings

The following settings can be configured in your `settings.yml`:

| Setting | Default | Description |
|---------|---------|-------------|
| `SiteTitle` | `My Blog` | The title of the site |
| `Description` | | A short description shown in the banner on the home page |
| `Intro` | | An intro text shown below the description in the banner |
| `Copyright` | `Copyright © {year}` | Copyright text in the footer |
| `PostSources` | `posts/**/*` | Glob pattern for post source files |
| `PageSources` | `pages/**/*` | Glob pattern for page source files |

## Front Matter

Posts and pages support the following front matter keys:

| Key | Description |
|-----|-------------|
| `Title` | The title of the post/page |
| `Published` | The publication date |
| `Tags` | A list of tags |
| `Lead` | A short description/subtitle |
| `Image` | A background image URL |
| `ShowInNavbar` | Whether to show this page in the navbar (default: true for pages) |
| `NavbarTitle` | Custom title in the navbar |
| `Order` | Sort order in the navbar |
| `CommentEngine` | Comment engine to use (e.g., `giscus`) |

## Credits

- [Solid State](https://html5up.net/solid-state) by [HTML5 UP](https://html5up.net) ([@ajlkn](https://twitter.com/ajlkn)) - CCA 3.0 license
- Converted from [Wyam SolidState theme](https://github.com/Wyamio/Wyam/tree/develop/themes/Blog/SolidState)
- Template structure based on [CleanBlog](https://github.com/statiqdev/CleanBlog) by [Statiq](https://statiq.dev)
