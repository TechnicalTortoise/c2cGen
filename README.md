# c2cGen
Generates corner to corner (C2C) crochet patterns from an image. This a great technique for making blankets and such.
![Setting colourNames](/hedgehog.jpg)

# Usage

1. Open the Jupyter notebook "c2cGen.ipynb".
2. Set the imagePath and completedPatternPath appropriately
3. Run through the notebook until the "Assign names to the colours" section.
4. Run the first cell in this section.
5. In the next cell, enter names for the colours in the order they appear in the colourNames list, as shown below (yellow=Y, white=W, black=B). Note because of the randomness in the K-Means-Clustering process, these colours will not always appear in the same order.
![Setting colourNames](/colourName.png)
6. Run through the remaining cells in the notebook.
7. You're done! The full pattern should be located in the path you specified at the beginning.

# Requirements
1. Python (Confirmed working on version 3.9.7)
2. Numpy
3. Matplotlib
4. OpenCV (https://pypi.org/project/opencv-python/)

