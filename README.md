# FaceDetectionDemo
- Install Caffe
- Download image database and convert image annotation in PASCAL VOC format
- Training command:
	/caffe train -solver="solver.prototxt" -gpu 0  2>&1 | tee -a log/log.log
- Evaluation will require .caffemodel and .prototxt file generated from training