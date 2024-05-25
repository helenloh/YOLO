from ultralytics import YOLO

model = YOLO("yolov6n.yaml")
model.info()
results = model.train(data='coco.yaml',epochs=100,imgsz=648)
results = model('path/to/bus.jpg')
