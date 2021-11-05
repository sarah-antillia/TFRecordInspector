# TFRecordInspector

This is a simple python <a href="./TFRecordInspector.py">TFRecordInspector</a> class to inspect a tensorflow tfrecord.<br>
This will parse an input tfrecord file, extract the images, labels, and bboxes from it, 
and write the annotated images to the files.<br>

For example, @lease run the following command<br>

<pre>
> python TFRecordInspector.py ./tfrecord/sample.tfrecord ./tfrecord/label_map.pbtxt ./output_dir
</pre>

Note:<br>
  To run this script, you have to install tensorflow 2 and related packages.<br>
<br>
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

