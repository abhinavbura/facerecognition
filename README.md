# Face Recognition Program

This project is a simple face recognition program built using Python. It utilizes the `face_recognition` module to detect and recognize faces from a set of images. The program compares face features from a new image with those stored in a folder of labeled images and identifies matches.

## Features
- **Face Detection and Recognition**: Extracts facial features from images and compares them with a new image to identify matches.
- **Training with New Faces**: Easily add new images to the `images` folder to train the model with new faces.
- **Easy to Run**: The project includes a Jupyter Notebook (`facereco.ipynb`) that contains all the necessary code. Simply run all the cells to execute the program.

## Prerequisites
Before running the program, make sure you have the following libraries installed:

- `face_recognition`
- `dlib`
- `cmake`

You can install these dependencies using pip:

```bash
pip install face_recognition dlib cmake

```

## How to Use

1. **Clone the Repository**:
```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

```

2. **Add Training Images**:
- Place your training images in the `images` folder.
- Ensure that each image file is named after the person it represents (e.g., `john_doe.jpg`).

3. **Run the Jupyter Notebook**:
- Open `facereco.ipynb` in Jupyter Notebook.
- Run all the cells to extract facial features from the images and compare them with a new image.
- The program will output the name of the person if a match is found.

## Adding New Faces
To add new faces to the recognition system:
- Simply add new images to the `images` folder.
- Run the Jupyter Notebook again to extract features from the new images.

## Contributing
Feel free to submit issues or pull requests if you find any bugs or want to improve the project.


