# Emacs Cheatsheet

### Navigating in the screen

* C-v moves forward one screen
* M-v moves backward one screen
* C-l centers the text around the current cursor position
* C-a moves to beginning of line
* C-e moves to end of line
* M-\* does the same as the prev two with sentences.
* M-&lt; moves to the beginning of the whole document
* M-&gt; moves to the end of the whole document

#### Arrow key substitutes

```text
 C-p
```

C-b C-f C-n

Use M-\* instead of C to navigate by word instead of letter.

### Stopping a command

A command can be stopped or Emacs can be stopped with C-g.

### Window Management

* C-x 1 makes the current window full screen and deletes the others

### Text input

Both commands and inserted text can be repeated with `C-u #` where `#` is the number of times that the character would be repeated.

#### Deletion

* `<DEL>` removes prev character
* `M-<DEL>` kills previous word.

The previous character can be removed with `<DEL>` \(backspace\) and the previous word can be removed with `M-<DEL>`.

