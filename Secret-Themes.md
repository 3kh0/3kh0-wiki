# Secret Themes

### Typing secret theme
This is a build in easy way to make a custom theme. Users will type a message and your theme will appear.
- Obtain theme code from [Create Theme Code](https://github.com/3kh0/3kh0.github.io/wiki/Create-Theme-Code)
- Add your code at the bottom of [/css/themes.css](https://github.com/3kh0/3kh0.github.io/blob/main/css/themes.css)
- Edit the file [/settings.html](https://github.com/3kh0/3kh0.github.io/blob/main/settings.html)
- To make a button for your theme use the code below as a template
```html
<button hidden class="button" onclick="setTheme('poop')">POOP THEME</button>
```
- Make sure the `setTheme()` is the name of your theme. You can replace the text `POOP THEME` to whatever your want
- Add your code inside the `.buttons` div
- Wait for the site to update and enjoy!
- Open [js/index.js](https://github.com/3kh0/3kh0.github.io/blob/main/js/index.js)
- To make your custom theme work use the code below as a template.
```js
createSecretThemeType("poop", ["s", "h", "i", "t", "!")
```
- Replace the first argument with your theme name and the 2nd with an array of letters the user needs to press.
- You can use special keys such as `ArrowRight` see [Key values for keyboard events](https://developer.mozilla.org/en-US/docs/Web/API/UI_Events/Keyboard_event_key_values) for a full list.
- Add your code to the bottom of the file and wait for the website to update.
- Make sure to test it out first and enjoy!

### Custom secret theme
To make a custom secret theme you need more knowledge of javascript.

- Obtain theme code from [Create Theme Code](https://github.com/3kh0/3kh0.github.io/wiki/Create-Theme-Code)
- Add your code at the bottom of [/css/themes.css](https://github.com/3kh0/3kh0.github.io/blob/main/css/themes.css)
- Edit the file [/settings.html](https://github.com/3kh0/3kh0.github.io/blob/main/settings.html)
- To make a button for your theme use the code below as a template
```html
<button hidden class="button" onclick="setTheme('poop')">POOP THEME</button>
```
- Make sure the `setTheme()` is the name of your theme. You can replace the text `POOP THEME` to whatever your want
- Add your code inside the `.buttons` div
- Wait for the site to update and enjoy!
- Open [js/index.js](https://github.com/3kh0/3kh0.github.io/blob/main/js/index.js)
- Use to following two commands to make your custom theme
```js
secretThemeButton("poop")
```
- Set the value to your theme name
- This will show the secret button on the settings page when the secret theme is active

```js
foundSecretTheme("poop")
```
- Set the value to your theme name
- This will activate the theme and show to button on the settings page.
- Add `secretThemeButton` to the bottom of the file
- Use `foundSecretTheme` on button click or whenever you want the theme to show
- Test it out and enjoy!

<p align="center">
©3kh0 2023 | <a href="https://3kh0.github.io">3kh0.github.io</a>
</p>