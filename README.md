# Traffic
- Implemented cv2 resizing .resize
- Implemented get_model. Used handwriting.py as an Example. 
    - Result: accuracy: 0.0548 - loss: 3.5011
- Added one more convelutional + Max pooling layer. Also, deleter input shape for the second layer.
    - Result: accuracy: 0.9641 - loss: 0.1371
- Added one more convelutional + Max pooling layer
    - Result:  accuracy: 0.9431 - loss: 0.2013
- Delete one more convelutional + Max pooling layer
    - Result: accuracy: 0.9547 - loss: 0.1539
- Update Conv2D first parameter. Set 64 to detect more deverse patterns:
    - Result: accuracy: 0.9682 - loss: 0.1179
- Add one more Conv2D layer with 128:
    - Result: accuracy: 0.9693 - loss: 0.1092


