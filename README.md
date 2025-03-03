# JsProjectionMapping
Simple tool to do basic polygon projection mapping in a browser. Made completely with AI. Claude seems to do best.

Initial prompt was:
"I need a basic light-projection-mapping html and vanilla javascript program. the background of the whole screen should be black. on that program, i want to be able to draw different polygons. each polygon should have movable vertices. there should be a way to add and delete vertices. when i right click on a polygon, i want to be able to select the polygons color, or if i want the polygon to be filled with an animated color gradient. there should also me an option to export and download the polygons i created as a json file and to import them. all UI elements should only be visible when I press shift, and hidden otherwise. make sure i can draw new polygons when i want or delete polygons. the color gradients should be centered in the middle of the polygons."

https://claude.ai/share/5374c01a-2974-4c1c-9232-d55aa4189681

What I can't get it to do, because of context-window limits, is to 
"in the polygons context menu, please add an option to make the polygons edges dither to the background color. let me choose how many pixels wide this dithering or feathering area should be.
also, please let me choose the gradient start and end colors. 
seperate the code in a couple of different files. please give me the content of the first file."
