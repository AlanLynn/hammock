![hammock icon](https://alanlynn.github.io/hammock/icon.png)

# Hammock Color Scheme

A dark color scheme that lets your eyes relax.

![hammock syntax highlighting screenshot](https://alanlynn.github.io/hammock/screenshot.png)

Enjoy syntax highlighting with gentle colors that go well together.


## Download

Choose your editor:
* [Sublime Text](https://github.com/AlanLynn/hammock-sublime-textmate#readme)
* [TextMate](https://github.com/AlanLynn/hammock-sublime-textmate#readme)
* [Visual Studio Code](https://github.com/AlanLynn/hammock-vscode#readme)
* [Other - How to build](#building)


## Building

Hammock is built using [Base16](https://github.com/chriskempson/base16).

1. Get the templates for your desired editor(s) from the [Base16 template repositories](https://github.com/chriskempson/base16#template-repositories).

2. Set your directory structure up like this:
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

3. Run a Base16 builder from the [Base16 builder repositories](https://github.com/chriskempson/base16#builder-repositories).


## License

* Source code: [MIT](https://choosealicense.com/licenses/mit/)
* Icon: [CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/)
