# Mixing-Homogeneity-Paste-Flow-Analysis

Source code for software developed for research on automated approaches to high-throughput sample mixing and computer vision piston rheometry.


## Environment & Setup

### 1. CV Program (Paste Flow Tracking)
The Computer Vision application for tracking paste displacement is designed to run locally (e.g., in **VSCode**),  with the required libraries installed 

**Required Libraries:**
Ensure you have the following installed in your Python environment:
```bash
import cv2
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
import os
from tkinter import *
from tkinter import filedialog, messagebox
