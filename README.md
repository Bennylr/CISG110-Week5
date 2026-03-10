# CISG110-Week5
## Devlog
1.) I think the period (.) is like a connector or a "pathway" that lets you reach inside an object to grab a specific trait. Using this example, "House.DoorColor" the dot narrows down exactly what part of the sprite we want to change. From the documentation and experimenting in the inspector, I learned that modulate acts like a "tint" or a colored lens placed over the node. Unlike a paint tool that replaces colors, it multiplies them, if you set it to red, the sprite doesn't just turn red, but all its existing colors are filtered through a red light. When messing with the visibility foldout, I noticed that changing the modulate property affects not just the Player node, but everything attached to it. This makes sense for the code Color(r, g, b), which is a mix of red, green, and blue. By giving this new color to _sprite.modulate, the code is "re-staining" the character’s appearance in real-time. My guess is that this line is used to make the player flash a certain color maybe turning red when they take damage or green when they are healed.

## Open-Source Assets
- [Cat sprites](https://toffeecraft.itch.io/cat-pixel-mega-pack)
- [Kenny's abstract platformer set](https://kenney.nl/assets/abstract-platformer)
- [Rainy Hearts font](https://www.dafont.com/rainyhearts.font)
