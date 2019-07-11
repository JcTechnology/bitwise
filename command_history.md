# test the overfit tiny core

./darknet detector test bitwise/obj.data bitwise/yolo-obj.cfg bitwise/first-test-core-yolo-obj_20000.weights bitwise/test/40_scene01251.jpg

./darknet detector test bitwise/obj.data bitwise/yolo-obj.cfg bitwise/first-test-core-yolo-obj_20000.weights < bitwise/test.txt > bitwise/log.txt

