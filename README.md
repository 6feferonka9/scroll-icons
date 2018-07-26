# Scrollable icons with pure CSS and SVG

Since Apple and modern web developers like to hide scrollbar when it is not active and it is not always easy to design content that will tell by its appereance "Hey, you can scroll me, I got more content outside viewport! I made this little css library.

This package let you use small SVG icons inside area, you want to tell is scrollable.

Horizontal and vertical icons in black and white color are available.

![horizontal](https://raw.githubusercontent.com/6feferonka9/scroll-icons/master/docs/horizontal.png)
![vertical](https://raw.githubusercontent.com/6feferonka9/scroll-icons/master/docs/vertical.png)

## Usage

1. Download minified CSS or SCSS source. Images are in base64 format inside css file so all you need is minified CSS.
2. Import CSS as any other CSS file.
3. Use classes :

| Class        | Result           |
| ------------- |:-------------:|
| scroll-icon-horizontal-black | black horizontal icon |
| scroll-icon-horizontal-white | white horizontal icon |
| scroll-icon-vertical-black   | black vertical icon   |
| scroll-icon-vertical-white   | white vertical icon   |

```html
<span class="scroll-icon-horizontal-black"></span>
```