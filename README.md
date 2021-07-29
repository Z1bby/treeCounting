# treeCounting
Program that uses the main deepforest module to count the trees from the example image.


### Installation
Deepforest installation guide can be found here:
https://deepforest.readthedocs.io/en/latest/installation.html

Matplotlib installation:
```
python -m pip install -U pip
python -m pip install -U matplotlib
```
Jupyter notebook installation:
```
pip install notebook
```

### Running the program
Inside the project directory run the command:
```
jupyter notebook
```

### Description
The original image was cut to smaller segments around 300x300 px in order to raise efficiency of the module.
Each segment is preddicted and returned as plot with boxes drawn around each recognized tree.
Program shows all plots and number of trees that are inside it.
