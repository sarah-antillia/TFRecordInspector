# TFRecordInspector

This is a simple python <a href="./TFRecordInspector.py">TFRecordInspector</a> class to inspect a tensorflow tfrecord.<br>
This will parse an input tfrecord file, extract the images, labels, and bboxes from it, 
and write the annotated images to the files.<br>

For example, @lease run the following command<br>

<pre>
> python TFRecordInspector.py ./tfrecord/sample.tfrecord ./tfrecord/label_map.pbtxt ./output_dir
</pre>

Note:
  To run this script, you have to install tensorflow 2.