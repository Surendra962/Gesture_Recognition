# Gesture_Recognition

**Model Summary**

**Conv3D**

**Model-1:**
- Epochs: 30
- Batch size: 20
- Filters: 32 and 64
- Kernel size: 333
- Filter used in the model: 16, 32, 64, 128 SGD optimizer
- Accuracy: 85%
- Validation Accuracy: 83%
- Remarks: This is a good model of all.

**Model-2:**
- Epochs: 20
- Batch size: 20
- Filters: 64, 128, 256, 256
- Filter used in the model: 64, 128, 256, 256 with SGD optimizer
- Remarks: This model is not running due to overflow.

**Model-3:**
- Filters: 64, 128, 256, 256
- Dense layer: 512 with SGD optimizer
- Accuracy: 96%
- Validation Accuracy: 67%
- Remarks: This model is overfitting.

**Model-4:**
- Epochs: 20
- Batch size: 20
- Filters: 64, 128, 256, 256
- Dense layer: 512 with SGD optimizer
- Accuracy: 89%
- Validation Accuracy: 71%
- Remarks: Good result still overfitting.

**Model-5:**
- Epochs: 20
- Batch size: 30
- Image size: 80x80
- Filters: 64, 128, 256, 256
- Dense layer: 512 with SGD optimizer
- Accuracy: 90%
- Validation Accuracy: 59%
- Remarks: This is also an overfitting model.

**CONV2D + GRU
Model-6:**
- Image size: 100x100
- Frames: 30
- Batch size: 20
- Epochs: 20
- Filters: 16, 32, 64, 128 with SGD optimizer
- Accuracy: 97%
- Validation Accuracy: 74%
- Remarks: This is also an overfitting model.

**Working Group**
1. Surendra Mehta
2. Daksha Kanungo
3. Shashank Kumar Pandey
