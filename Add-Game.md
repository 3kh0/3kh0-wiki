## Add a game to 3kh0

1. If you want to add a game you will need to create a push request in the [3kh0-Assets](https://github.com/3kh0/3kh0-Assets) repository with the files of your game in a folder. Make sure that you have an thumbnail for the game in the folder you created.

2. Now create a fork of this repository and find the file `/assets/json/games.json`.

In that file you should see a json list looking something like this:
```json
[
  {
    "name": "1",
    "root": "1",
    "file": "index.html",
    "img": "meta/apple-touch-icon.png"
  },
  {
    "ect."
  }
```
If that is not the case try updating your fork to a newer version.

4. Once you have found the file scroll down to the bottom of the file and add the following snippet (remember to replace what it says with actual values):
```json
{
  "name": "the name the game you are adding",
  "root": "the folder you created for your game",
  "file": "the main file for your game (usually index.html)",
  "img": "the path to the thumbnail for your game"
}
```

5. Once you have done all of the steps above, create a pull request in this repository with the updated games.json file.
6. Wait for a contributor with write access to approve your changes and add the game to 3kh0.

<p align="center">
©3kh0 2023 | <a href="https://3kh0.github.io">3kh0.github.io</a>
</p>