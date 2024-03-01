
---



## Description

Themed Animation Creator is a Python application designed to generate custom, themed animations. Users can input text, select a theme, and the script generates a GIF animation with styled text transitions and background effects tailored to the chosen theme. Themes include Nintendo, Rainbow, Acid, and Original, each offering a unique visual experience.

## Features

- **Custom Text Inputs**: Add a title and subtitle to personalize your animation.
- **Theme Selection**: Choose from predefined themes to style your animation.
- **Adjustable Frame Rate**: Configure the animation's frame rate.
- **Output Control**: Save the generated animation to a specified directory.

## Getting Started

### Prerequisites

- Python 3.6 or higher
- Pillow (PIL Fork)
- ImageIO
- NumPy

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/Ruphxs/NintendoBootLogoGen
cd NintendoBootLogoGen
```



2. **Install the required packages**

```bash
pip install pillow imageio numpy
```

### Usage

1. **Prepare Your Assets**

- Place any required PNG images in the designated assets folder. For example, for the Nintendo theme, ensure you have the necessary Nintendo-themed PNGs in `pics/nintendo.png`. Should be already done though.

2. **Configuration**

- It will ask you for your input for each text when running the program.

3. **Running the Script**

Execute the script from the terminal:

```bash
python themed_animation_creator.py
```

Follow the interactive prompts to select your theme and input any required information.

### Output

Animations will be saved in the `outputs` directory with the name format `<TITLE>.gif`.

## Customization

To customize themes or add new ones, refer to the theming section of the script. Theme-specific parameters like color palettes and transition effects can be modified directly in the code.


## License

This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments

- Thanks to the Pillow, ImageIO, and NumPy communities for their valuable libraries.

---


