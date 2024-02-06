# Flappy Bird Project in Python

This is a project to implement the Flappy Bird game in Python using the Pygame library. The goal of this project is to create a simplified version of the famous Flappy Bird game, where a bird must navigate through flying pipes and accumulate points.

## Project Description

The project consists of a complete implementation of the Flappy Bird game, including the game logic, bird physics, pipe generation, collision detection, scoring, and graphical rendering.

### Technologies Used

- Python
- Pygame

### Project Structure

The project is structured as follows:

- `FlappyBird.py`: The main file containing the game implementation.
- `imgs/`: Folder containing the images used in the game.
- `README.md`: This file providing information about the project.

### Replacement of Absolute Paths

One notable modification in this project is the replacement of the `os` library for path manipulation with direct absolute paths for the game's images. This was done to make the project simpler and easier to understand, allowing other developers to quickly grasp where the images are located and make modifications as needed.

Here's an example of how the images are loaded in the project:

```python
IMAGE_PIPE = pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\pipe.png'))
IMAGE_GROUND = pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\base.png'))
IMAGE_BACKGROUND = pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\bg.png'))
IMAGES_BIRD = [
    pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\bird1.png')),
    pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\bird2.png')),
    pygame.transform.scale2x(pygame.image.load('e:\\DESKTOP_2\\FlappyBird\\Projeto_Flappy_Bird\\imgs\\bird3.png')),
]

This modification allows developers to easily customize the image paths according to their directory structure or preferences.

### How to Use the Project
To use this project, follow these steps:

Make sure you have Python and the Pygame library installed on your system.
Clone this repository to your computer.
Open a terminal in the folder where the project is located.
Execute the FlappyBird.py file using the command python FlappyBird.py.
Contribution
Feel free to contribute improvements or modifications to this project. If you wish to replace the os library with absolute paths in other parts of the code, you are welcome to do so and submit a pull request.

License
This project is distributed under the MIT License.
