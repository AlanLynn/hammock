![hammock icon](https://alanlynn.github.io/hammock/icon.png)

# Hammock Color Scheme

A dark color scheme that lets your eyes relax.

![hammock syntax highlighting screenshot](https://alanlynn.github.io/hammock/screenshot.png)

Enjoy syntax highlighting with gentle colors that go well together.


## Download

Choose your editor:
* [Sublime Text](https://github.com/AlanLynn/hammock-sublime-textmate#installing)
* [TextMate](https://github.com/AlanLynn/hammock-sublime-textmate#installing)
* [Visual Studio Code](https://github.com/AlanLynn/hammock-vscode#installing)
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


## How It Was Made

I used a 3D engine to shine a colored light on 16 colored squares. My hope was that putting all the colors in the same lighting would make them look like they go together.

![blender 3d engine screenshot of 16 colored squares](https://alanlynn.github.io/hammock/3d-scene.jpg)

Does it actually do anything useful? I don't know. If you want to try it for yourself, open [colors.blend](colors.blend) in [Blender](https://www.blender.org/). You might want to change ```Render Properties -> Color Management -> View Transform``` to ```Filmic```.


## License

* Source code: [MIT](https://choosealicense.com/licenses/mit/)
* Icon: [CC-BY-4.0](https://choosealicense.com/licenses/cc-by-4.0/)
