How to Execute ?

I have submitted two folders part1 and part_2_3_4 where part1 has white trainagles rendered part and part_2_3_4 has Blinn phong illumination, texturing and transformation.

In part1 folder, I have placed head.obj, vase.obj and part1.html files.

In order to test it, double click on part1.html and in the browser, to the url append this string "?objfile=Input_file" where Input_file can be head.obj or vase.obj

In part_2_3_4 folder I have placed all the input .obj files, .mtl files and .bmp images.
In order to test it, double click on the part_bp.html file and in the browser append this string "?objfile=Input_file" where Input_file can be head.obj or vase.obj.

I wrote the logic to take its corresponding .mtl and .bmp images. So we need not pass .mtl and .bmp images as parameters.

For Blinn Phong illumination I have hardcoded values for eye_vector, light vector and Ka, Ks values.

My code doesn't handle multiple textures for vase. So it takes the first .bmp and it will be used as a texture for the whole vase. In head, there is no such problem as it has only one texture image.

My code handles transformations when you press arrows, Q,Z,X alphabets.

Citations:

Below are the sources from which I used the code for this assignment

Lesson4 and lesson 6 in : https://github.com/gpjt/webgl-lessons

For handling Transformation logic: http://stackoverflow.com/questions/5597060/detecting-arrow-key-presses-in-javascript

for reading and parsing a file : http://stackoverflow.com/questions/14446447/javascript-read-local-text-file

