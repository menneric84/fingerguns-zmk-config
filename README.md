YOU MUST CHECK fingerguns.overlay TO ENSURE THE PROPER TRANSFORM IS CHOSEN

Please see the comments on line 3 of fingerguns.overlay.  In the 'chosen' node, you will need to adjust zmk,matrix-transform depending on if you are using the 12 column variant or the 10 column variant of the Fingerguns PCB.

The 12 column is represented by &default_transform
The 10 column is represented by &10col_transform


YOU MUST SELECT OR CREATE AN APPROPRIATE KEYMAP

In the ergomech community a keymap is an intensely personal thing.  That being said, I've included a 12 column and 10 column keymap in case you need somewhere to start.  Please note that fingerguns.keymap is intended for the 10 column variant.  A 12 column keymap is also included under the name fingerguns.keymap.12col.  If you wish to use 12 columns, simply append '.10col' to the default keymap and delete '.12col' from the other one.