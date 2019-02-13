# Vim for Muggles™

A two hours workshop on Vim.

Start the editor using the provided script to disable all user plugins
and arrow keys.

```bash
$ ./startvim.sh
```


## Exercises

Do the exercises in the following order:

  * files/moving_the_cursor.txt
  * files/dracula.txt  (Practice all the movements of the cheatsheet)
  * exercises/normal/operator_with_motion/\*
  * exercises/normal/actions/\*
  * exercises/normal/operator_with_text_objects/\*
  * exercises/insert/\*
  * exercises/visual/\*
  * exercises/command/\*

## The Cheatsheet

  * Front: Selection of operation commands (open files, move through
    windows...)
  * Back: Actions, operations and motions available, sorted by mode (see
    bellow)


## Modes

Understanding Vim modes is critical for the effective use of the editor. 

![](https://raw.githubusercontent.com/nilp0inter/Vim-for-Muggles/master/modes.png)


### Normal Mode

  * Is the default mode.
  * Allows fast movement through the text
  * Fast text modification
  * Switching to other modes


### Insert Mode

  * Modify the file inserting new text


### Visual Mode

  * Select part of the text to operate over it


### Command Mode

  * Editor basic operation (open, close, write...)
  * Bulk editing through `ex-commands`


## License

The cheatsheet is a derivative work of [Martin “BruXy” Bruchanov](http://gnulinux.guru/?about)'s [Vi IMproved cheatsheet](http://gnulinux.guru/?ViM) with permission of the author.

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/80x15.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
