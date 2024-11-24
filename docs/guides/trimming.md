# Trimming the Layers

Overlapping edges of layers cause messy mosaics, so a mask must be added to each layer to remove its margins. These masks should all be contiguous (sharing adjacent borders and vertices) so it is best to handle them at the volume-level, not by masking each layer individually.

![The multitrim interface.](../_assets/images/multitrim.gif)