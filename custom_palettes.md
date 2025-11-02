# How to create your own color palettes

This script uses the [curses library](https://docs.python.org/3/howto/curses.html) for adding basic color to the terminal, and uses `xterm-256color' for added color ranges.

> [!IMPORTANT]
> The script should detect if the terminal you're using supports 256 color mode, however, this might now always work (SSH is known to do this). 
If you want to maintain compatability, use the 8 curses colors only. Otherwise you can enable 256 color mode, depending what terminal you use.

## Layout of palette template

```python
    {
        "name": "My Custom Template",
        "bg": background color,
        "label": text color,
        "highlight": text highlight color,
        "input": text input color,
        "log": logbook entries color,
        "footer": footer color,
        "reverse_highlight": False,
    }
```

## Available colors

### Curses
- curses.COLOR_BLACK
- curses.COLOR_RED
- curses.COLOR_GREEN
- curses.COLOR_YELLOW
- curses.COLOR_BLUE
- curses.COLOR_MAGENTA
- curses.COLOR_CYAN
- curses.COLOR_WHITE

### xterm-256color
[This is a link](https://upload.wikimedia.org/wikipedia/commons/1/15/Xterm_256color_chart.svg) to the chart pictured below in higher resolution.
> [!TIP]
> Use the number in the bottom of the square you want to use.
<img width="500" height="730" alt="image" src="https://github.com/user-attachments/assets/c9167550-5ef4-47c5-95c9-29dc2af5c98b" />
