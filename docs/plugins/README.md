# Plugins

Plugins are the best way to extend GitHon functionalities (ebook and website). There exist plugins to do a lot of things: bring math formulas display support, track visits using Google Analytic, etc.

### How to find plugins?

Plugins can be easily searched on [plugins.gitbook.com](https://plugins.gitbook.com).

Search on npm with keywords: `gitbook-plugin` or `githon-plugin`

### How to install a plugin?

Once you find a plugin that you want to install, you need to add it to your `book.json`:

```
{
    "plugins": ["myPlugin", "anotherPlugin"]
}
```

You can also specify a specific version using: `"myPlugin@0.3.1"`. By default GitHon will resolve the latest version of the plugin compatbile with the current GitHon version.

### Configuring plugins

Plugins specific configurations are stored in `pluginsConfig`. You have to refer to the documentation of the plugin itself for details about the available options.