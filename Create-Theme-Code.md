# Create Theme Code
- Open the 3kh0 website
- Open Devtools and go to the Elements tab
- Click on the body element
- At to bottom you should see something like this 

![image](https://user-images.githubusercontent.com/81875430/213951460-b3142bf3-e212-4c15-b1b8-ae61e7eab4a9.png)

- Click on the color square to open a color picker
- Now paste it somewhere when you and done and change the name
- Below is an example of how it will look

```css
body[theme=poop] {
    --background: black;
    --theme: brown;
    --text: white;
    --text-secondary: white;
}
```

- This is how the example theme would look on the website

![image](https://user-images.githubusercontent.com/81875430/213951824-d71fe9c7-c14c-40b0-9320-d9f762b16526.png)

## What the values mean
`--background` - The background of the website

`--theme` - The color for buttons and the gradient at the top

`--text` - Normal text on the website

`--text-secondary` - Text with `--theme` as the background so basically buttons

<p align="center">
©3kh0 2023 | <a href="https://3kh0.github.io">3kh0.github.io</a>
</p>