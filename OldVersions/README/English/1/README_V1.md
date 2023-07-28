
***

# Twit-Tac-Toe documentation

`🐦️🅾️❎️📖️ The official documentation source repository for Twit-Tac-Toe.`

- [:octocat: `Go back to home repository`](https://github.com/seanpm2001/Twit-Tac-Toe/)

# Additional documentation

## Unused/extra assets

There are some non-required assets that can be used in the game:

- [`TTT_Board1.png` (a raster Tic-Tac-Toe board, which is inferior to the vector version`](/Twit-Tac-Toe/Assets/Board/TTT_Board1.png/)

For those who enable background images in the game, 3 default images are included (you can add more if needed)

- [`Twitter1.png`](/Twit-Tac-Toe/Assets/Background/Twitter1.png)
- [`Twitter2.png`](/Twit-Tac-Toe/Assets/Background/Twitter2.png)
- [`Twitter3.png`](/Twit-Tac-Toe/Assets/Background/Twitter3.png)

## Challenges

Here are some challenges that you can do with friends/people nearby (as a party game/dispute resolution process)

### X Challenge

Get 2 players, one of them has to think that Twitter should be called X (they will control the X logo) and one of them has to think Twitter should be Twitter (they will control the Twitter logo) play 3 times (draws don't count towards the final goal) whoever gets 2 or more wins is the victor in the argument for the next 24 hours.

## Settings

The game has some built-in settings. For example, you can change the wallpaper/make it change wallpapers after each round, change the player logos, add a time limit, keep/manage scores, and set usernames. 

### Built-in background images

If `wallpaperOn` equals `true` and `wallpaperTransitions` is equal to `true` you will be able to see 3 different wallpapers upon each game ending. If you change `backgroundNumLimit` to 4 or higher, the game will look for additional wallpapers. If they are not found, it will default to the first one. If you set the value to 1, wallpapers will never transition. If you set the value to 0 or lower, the game will load the background as solid black (or white, depending on your system theme of dark or light) changing `BackgroundNum` will change the background, although the game will do this on its own.

1. [Twitter1]

<img src="/Twit-Tac-Toe/Assets/Background/Twitter1.png" alt="Background 1 failed to load" width="854" height="480">

2. [Twitter2]

<img src="/Twit-Tac-Toe/Assets/Background/Twitter2.png" alt="Background 2 failed to load" width="854" height="480">

3. [Twitter3]

<img src="/Twit-Tac-Toe/Assets/Background/Twitter3.png" alt="Background 3 failed to load" width="854" height="480">

## About page

The about page currently can only be called in the console while the about page is active by typing `A` or `ABOUT` it will run at the start of launching the program, but has not yet been programmed to run outside of this.

## Game status

The game operates with a string called `game` which always has one of these 6 values:

- `new` - This is the start of a new game.
- `ongoing` - The current game is ongoing
- `X Won` - Player 2 (X) won by getting 3 in a row.
- `O Won` - Player 1 (O) won by getting 3 in a row.
- `draw` - The game ended in a draw
- `ended` - The current game ended, and is waiting for the program to start a new game, or terminate the game session

## Other languages

I will test this game in other programming languages in the future when it is deemed necessary.

## Programming goals

The goal is to have the program written in 140 lines or less. This number is in reference to the previous Twitter character limit. It should be less than 100, I will optimize it further as I go.

***

# File info

**File version:** `1 (2023, Thursday, July 27th at 7:18 pm PST)` - This file was written a day before it was published.

***
