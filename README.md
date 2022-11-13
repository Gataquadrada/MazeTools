Here is where you can download most utilities apps I created/use.

<br>

# Summary

-   [Listening to your Mouse and Keyboard](#listening-to-your-mouse-and-keyboard), and saving the last Event into a text file.

<br />
<br />

# Listening to your Mouse and Keyboard

[This utility](kbm-events-to-file/) will listen to your Mouse and Keyboard, and save the last Event of both into files names `mouse.txt` and `keyboard.txt`.

That way, you can hook Stream Deck / Touch Portal Events to those files and add more depth to your overlays.

<br>

## Preview

![kbm-events-to-file-1.gif](img/kbm-events-to-file-1.gif)

<br>

## Before starting

Just run the app once, so it can create it's files.

<br>

## Settings

Edit the `settings.json` file, to change the following:

```json
{
    "listen_mouse_press": false, // listen to pressing mouse buttons?
    "listen_mouse_release": false, // listen to releasing mouse buttons?
    "listen_keyboard_press": false, // listen to pressing keyboard buttons?
    "listen_keyboard_release": false // listen to releasing keyboard buttons?
}
```

<br>

## Ideas

Hide/show sources based on the contents of the files (latest events).

![kbm-events-to-file-2.png](img/kbm-events-to-file-2.png)
