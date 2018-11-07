# Hooke's law
### Track the weights and record its position after the flash
<img src="https://github.com/thtang/Computation-in-Data-Science/blob/master/Numerical%20Linear%20Algebra/Hookes%20Law/demo.gif">

### Dependencies
`Dlib` `OpenCV`

### Useage
```
cd ./object-tracker-master
python object-tracker-single.py -v <path-2-video-file>
```
Once you trigger the program, press <kbd>p</kbd> to puase the movie and draw a bounding box of the weight.
Then press <kbd>p</kbd> again. The output would be a numpy array with shape (2, number of frames),  where **2** indicates the x, y of the bounding box centroid.<br>
*Note: The video should contain flash moment for the starting time point of position recording.*

## Reference
bikz05/object-tracker [[1]](https://github.com/bikz05/object-tracker)
