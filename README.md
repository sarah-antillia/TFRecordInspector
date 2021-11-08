# TFRecordInspector

This is a simple python <a href="./TFRecordInspector.py">TFRecordInspector</a> class to inspect a tensorflow tfrecord.<br>
This will parse an input tfrecord file, extract the images, labels, and bboxes from it, 
and write the annotated images to the files.<br>

For example, please run the following command<br>

<pre>
> python TFRecordInspector.py ./tfrecord/sample.tfrecord ./tfrecord/label_map.pbtxt ./output
</pre>

Note:<br>
  To run this script, you have to install tensorflow 2 and related packages.<br>
<br>
By running this script, a lot of image files which are originally included in the tfrecord
will be extracted and saved to the <b>output_dir</b> with annotations.<br>
Also, an objects_count csv file generated in <b>ouput/objects_count</b> folder.<br>

The images in output_dir will be shown as.<br>
<img src="./asset/images_in_output_folder.png"><br>

<br>
Sample images<br>
<img src="./output/0fd5dd22-f501-40d2-b402-2e45675997e3_0_668.jpg"><br><br>
<img src="./output/2ff122ba-e57f-41ca-829e-835fff52c117_0_6303.jpg"><br><br>
<img src="./output/2dce0990-6164-490f-920c-257445defaf1_0_2174.jpg"><br><br>
<img src="./output/03bf57ff-f5cb-43e9-a179-2b870a758385_0_7559.jpg"><br><br>
<img src="./output/4d31ad52-7383-41a4-bdba-3f99a7cd48f5_0_6793.jpg"><br><br>
<img src="./output/052b72a0-c5e1-474b-8a24-a254d64f5771_0_427.jpg"><br><br>
<img src="./output/60973d51-a092-4d44-b34c-6d281cff4332_0_9793.jpg"><br><br>
<img src="./output/2b148be8-7a12-4227-870e-d16c1ecfc71e_0_1469.jpg"><br><br>
<img src="./output/3b0e4103-6620-4971-9684-5b7e09d625d9_0_6847.jpg"><br><br>
<img src="./output/43cc3dda-2a8e-4e99-8a3f-cf70e8726e1f_0_1856.jpg"><br><br>
<img src="./output/b2500a69-ddfa-4303-9c04-8234469ad727_0_3063.jpg"><br><br>

Objects_count.csv <br>

<a href="./output/objects_count/objects_count.csv">objects_count.csv</a>
<br>

<img src = "./asset/objects_count.csv.png" width="1024" height="auto"><br>
You can see the imbalanced categories.<br>


