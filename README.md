# Sublime & Sublime Plugin

> `sublime.py` and `sublime_plugin.py`

This repository stores the two Python files that Sublime Text distribtues for plugin developers.

That is, they are the Python modules that you import when writing a Sublime Text plugin.

```py
import sublime
import sublime_plugin
```

- Sublime Text 3
    - [`sublime.py`](./3/sublime.py)
    - [`sublime_plugin.py`](./3/sublime_plugin.py)
- Sublime Text 4
    - Python 3.3
        - [`sublime.py`](./4/python33/sublime.py)
        - [`sublime_plugin.py`](./4/python33/sublime_plugin.py)
    - Python 3.8
        - [`sublime.py`](./4/python38/sublime.py)
        - [`sublime_plugin.py`](./4/python38/sublime_plugin.py)

## Location

These files are shipped with Sublime Text. Usually they can be found at, for example,

- macOS

```
/Applications/Sublime Text.app/Contents/MacOS
```

## Sublime Text Versions

- Sublime Text 3

```
Version 3.2.2 (Build 3211) 1 October 2019
```

- Sublime Text 4

```
Version 4 (Build 4113) 14 July 2021
```
