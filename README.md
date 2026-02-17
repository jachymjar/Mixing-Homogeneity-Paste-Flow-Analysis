# Mixing-Homogeneity-Paste-Flow-Analysis

Source code for software developed for research on automated approaches to high-throughput sample mixing and computer vision piston rheometry is provvided in this repository. The code was developed for a Master's thesis at the food process engineering Department at Wageningen University.  

### 1. CV Program (Paste Flow Tracking)
The Computer Vision application for tracking paste displacement is designed to run locally (e.g., in **VSCode**),  with the required imports:
```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import os
from tkinter import *
from tkinter import filedialog, messagebox## Environment & Setup
```
### 2. All Other Code Blocks (Analysis)
These were used for image homogeneity analysis and fitting phenomenological models to CV data, and can simply be pasted into google colab. 
