![hammock icon](https://alanlynn.github.io/hammock/icon.png)

# Hammock Color Scheme

A dark color scheme that lets your eyes relax.

![hammock syntax highlighting screenshot](https://alanlynn.github.io/hammock/screenshot.png)

The Hammock color scheme enables syntax highlighting with gentle colors that go well together. It was built using [Base16](https://github.com/chriskempson/base16).


## Download

Choose your editor:
* [Sublime Text](https://github.com/AlanLynn/hammock-sublime-textmate#readme)
* [TextMate](https://github.com/AlanLynn/hammock-sublime-textmate#readme)
* [Visual Studio Code](https://github.com/AlanLynn/hammock-vscode#readme)
* [Other - How to build](#building)


## Building

Get the templates for your desired editor(s) from https://github.com/chriskempson/base16#template-repositories

Set your directory structure up like this:

```
.
├──schemes
│  └── hammock
│      └── hammock.yaml
└── templates
    └── (template-name)
        └── templates
            ├── config.yaml
            └── default.mustache
```

Then run a Base16 builder from https://github.com/chriskempson/base16#builder-repositories


## License

* Source code: [MIT](https://choosealicense.com/licenses/mit/)
* Icon: [CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/)
