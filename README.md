# bg3txt README

bg3txt aims to provide basic syntax support and foldable blocks to the text files of Baldur's Gate 3 mods.

## Features



Describe specific features of your extension including screenshots of your extension in action. Image paths are relative to this README file.

For example if there is an image subfolder under your extension project workspace:

![foldable comments](./docs/showcase.gif)

- Basic syntax highlighting
- Foldable block with comments

### Foldable comments

You can create foldable blocks if you surround your code with:
- a start comment: `//-- {your text here} {//}`
- an end comment: `//--{as many dashes as you want}//`

Working examples:
```
//-- My super header -----------------//
my code goes here
//------------------------------------//

//-- My super header 2
my code goes here
//--
```

Non-working example:
```
// -- (I put a space before dashes, oops)
my code goes here
//-- (forgot the dashes at the end and put a space in there!)
```


## Known Issues

This is very barebones. Don't hesitate to ask me for features, and I'll add them if possible!

## Release Notes


### 1.0.0

Initial release of the bg3txt langage support

**Enjoy!**