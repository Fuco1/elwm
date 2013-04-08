elwm
====

Lightweight window manager for emacs.

This is mostly collection of functions my own configuration, from [http://www.emacswiki.org/](EmacsWiki), and all over the web.

Doesn't try to be extremly smart :)

You can:
* transpose buffers in windows (with the next/previous window or with "master area" window)
* rotate buffers (move all buffers clockwise to the next window)
* jump to next/prev/master window (somwwhat like `C-x o`)

Right now supports two layouts:

    tile-vertical-left
    
    +-----------+-------------+
    |           |      1      |
    |           +-------------+
    |  master   |      2      |
    |           +-------------+
    |           |      3      |
    +-----------+-------------+
    
    
    tile-horizontal-top
    
    +-------+---------+-------+
    |   1   |    2    |   3   |
    |       |         |       |
    +-------+---------+-------+
    |                         |
    |         master          |
    +-------------------------+
