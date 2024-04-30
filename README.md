## 2D Texture Atlas importer plugin for other texture pack tools

My goal here is to update this 8-year-old package to work with Godot 4.x onwards, and provide instructions for how to implement it into Godot.

Load packed atlas texture to filesystem and can be used in godot.

#### Cureent support tools and formats
- TexturePacker : Generic XML
- TexturePacker : JSON hash
- [Attila](https://github.com/r-lyeh/attila) : JSON
- Kenney Spritesheet : Atlas from [Kenney assets](http://kenney.nl/assets)

As godot doesn't support rotated atlas, so don't rotate sprites when you pack pictures with above tools or you have to rotate them back manually.
