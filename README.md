# Nord-Hugo
A Hugo theme using the Nord colorscheme. 
Forked from/based on [Vaga's m10c theme](https://github.com/vaga/hugo-theme-m10c)


![HugoTest](https://user-images.githubusercontent.com/68812119/210877632-d0d13030-d472-4f35-b952-80570cbc316f.png)

### Basic configuration [From the original theme]

In your `config.toml` file, define the following variables in `params`:

- `author`: Name of the author
- `description`: Short description of the author
- `avatar`: Path of file containing the author avatar image
- `menu_item_separator`: Separator between each menu item. HTML allowed (default: " - ")
- `favicon`: Absolute path of your favicon.ico file (default: "/favicon.ico")

To add a menu item, add the following lines in `menu`:

```
[[menu.main]]
  identifier = "tags"
  name = "Tags"
  url = "/tags/"
```

[Read Hugo documentations](https://gohugo.io/content-management/menus/#readout) for more informations about menu

To add a social link, add the following lines in `params`:

```
[[params.social]]
  icon = "github"
  name = "My Github"
  url = "https://github.com/my-github"
```
