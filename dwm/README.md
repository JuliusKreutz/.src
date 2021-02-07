# DWM
First of all. Dwm is a very simple [tiling window manager](https://en.wikipedia.org/wiki/Tiling_window_manager). 
Tiling windows managers really need you to use your keyboard instead of your mouse so here are some of the important keybindigs.
I set my [modkey](https://dwm.suckless.org/customisation/windows_key/) to the Windows key. I will use win as an abbreviation for the Windows key.

## Opening and closing
- win + shift + enter (Opens a new terminal window)
- win + shift + c (Closes window)
- win + p (Opens dmenu aka your search prompt)
- win + shift + q (Closes dwm)

## Navigation
- win + [1-9] (Switches to corresponding tag)
- win + shift + [1-9] (Moves window to corresponding tag)
- win + j (Focuscicle through the windows in stack order)
- win + k (Focuscicle through the windows in stack order reversed)
- win + . (Focuscicle through your monitors clockwise)
- win + , (Focuscicle through your monitors counterclockwise) <- Only useful with more than 2 monitors
- win + shift + . (Move window to next monitor clockwise)
- win + shift + , (Move window to next monitor counterclockwise) <- Only useful with more than 2 monitors

## Layouts
- win + t (tiling layout) <- default layout
- win + f (floating layout)
- win + m (middle layout)
- win + space (Switch back to last used layout)
- ### Tiling layout
  - win + enter (Makes window to master)
  - win + h (Moves the middle separation line to the left)
  - win + l (Moves the middle separation line to the right)
  - win + i (Increases amount of master tiles)
  - win + d (Dencreases amount of master tiles)
  - win + leftClick (Make window to floating window and move it)
  - win + rightClick (Make window to floating window and resize it)
- ### Floating layout
  - win + shift + space (Make floating window go back to tiling)

## Vanity
- win + + (Increase border between windows by 1 pixel)
- win + - (Dencrease border between windows by 1 pixel)
