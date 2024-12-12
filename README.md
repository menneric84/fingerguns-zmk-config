YOU MUST CHECK fingerguns.overlay TO ENSURE THE PROPER TRANSFORM IS CHOSEN

Please see the comments on line 3 of fingerguns.overlay.  In the 'chosen' node, you will need to adjust zmk,matrix-transform depending on if you are using the 12 column variant or the 10 column variant of the Fingerguns PCB.

The 12 column is represented by &default_transform
The 10 column is represented by &10col_transform