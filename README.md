# FRB American Cursive `sketchbook/` directory for Processing (Java version)

To build `make physics`, you'll need these files. The licenses of all the libraries are in their respective directories.

The `*utils/` library directories seem to be Processing default includes, and some of them, especially audio-related ones, are not in use. However, they are distributed to make the sketchbook useful for general Processing use as well.

If you do not want to put this in your `$HOME` as the directory `sketchbook`, which is Processing's default, you may edit `$HOME/.config/processing/preferences.txt` as such:

```diff
diff --git /home/fred/.config/processing/preferences.txt /home/fred/sketchbook/preferences.txt
index 51844e4..9cf8f0c 100644
--- /home/fred/.config/processing/preferences.txt
+++ /home/fred/sketchbook/preferences.txt
@@ -77,7 +77,7 @@ run.present.bgcolor=#666666
 run.present.stop.color=#cccccc
 run.window.bgcolor=#DFDFDF
 search.format=https://google.com/search?q=%s
-sketchbook.path.four=/home/fred/sketchbook
+sketchbook.path.four=/home/fred/Workspace/processing-sketchbook
 ui.font.family=Dialog
 ui.font.size=12
 update.check=true
```
