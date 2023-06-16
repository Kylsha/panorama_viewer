# Panorama Viewer
Plugin for QGIS to view 360-degrees panoramic photos

## Technologies
Project is created with:
* Python
* [Panellum js library](https://pannellum.org/)

## Quick guide
Install plugin in QGIS, then create or open a new layer of any geometry type. You need to have at least one string type field.
Add direct file or web links to string fields of your layer.
This is a sample of how your layer table should be.

![Table loook](https://pereverzev.info/random_pics/table_look.png)

Now open plugin, select layer and field. Then manually select some object of your layer.
By pressing "View panorama" button you will see it appearing in a plugin view.

![Plugin view](https://pereverzev.info/random_pics/plugin_look.png)

By checking "Auto-update view" panorama will load automatiaclly.
