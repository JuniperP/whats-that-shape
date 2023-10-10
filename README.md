# [What's That Shape?](https://github.com/shupik123/whats-that-shape/)
A neural network to figure out whether a shape is a circle, square, or triangle.

- **THIS PROJECT IS NO LONGER MAINTAINED**
- **This was a project from 9th grade that was my first experience with neural networks. There are no intentions to maintain this project.**
 
This project is based on a [tutorial](https://towardsdatascience.com/a-beginners-tutorial-on-building-an-ai-image-classifier-using-pytorch-6f85cb69cba7) by Alexander Wu.

![Circle](https://github.com/shupik123/whats-that-shape/blob/master/shapes/train/circle/drawing(1).png)
![Square](https://github.com/shupik123/whats-that-shape/blob/master/shapes/train/square/drawing(1).png)
![Triangle](https://github.com/shupik123/whats-that-shape/blob/master/shapes/train/triangle/drawing(1).png)
## How to open and edit
Update pip: `python -m pip install --upgrade pip`

Install Jupyter Notebook: `pip3 install jupyter` or `python -m pip install jupyter`

Open the notebook: `jupyter notebook` or `python -m jupyter notebook`

You can then navigate to the directory this repository is stored in and click on the `whats-that-shape.ipynb`.
## Running the code
### Required:
- [Latest 3.7.x Python](https://www.python.org/downloads/)
- [PyTorch](https://pytorch.org/get-started/locally/) latest stable (Select your: OS and CUDA)
- NumPy: `pip install numpy`
- Matplotlib: `pip install matplotlib`
- Pillow: `pip install pillow`
### Variables:
It is recommended to edit:
- `batch_size=` to as high as possible without getting a memory error (restart kernel if you get error).
- `learning_rate=` between 1e-4 and 1e-5.
- `epochs=` however long you want to run it.
## Results
`batch_size=16`
`learning_rate=3e-5`
`epochs=200`

![Beginning](https://github.com/shupik123/whats-that-shape/blob/master/images/resultsBeginning.png)

![End](https://github.com/shupik123/whats-that-shape/blob/master/images/resultsEnd.png)

![Graph](https://github.com/shupik123/whats-that-shape/blob/master/images/resultsGraph.png)
