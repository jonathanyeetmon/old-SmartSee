
git clone https://github.com/jonathanyeetmon/logo-detection/
cd LogoDet
pip install -r requirements.txt
```

```python
# Weights will be auto-downloaded
from predictor import predictor

image_paths = [image_1.jpg, image_2.png, ...]

predictions = predictor(image_paths)

```

**Notes**:

1. the current release is limited to [these 292 logos](https://github.com/notAI-tech/LogoDet/releases/download/292_classes_v1/classes.txt) due to hardware constraints.

