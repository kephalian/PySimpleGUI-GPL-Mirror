# PySimpleGUI-GPL-Mirror

Mirored version of my favorite GUI python module PySimpleGUI.


# PySimpleGUI 4.64.61.0.206 Mirror

This repository is a mirror of the PySimpleGUI version 4.64.61.0.206. The original PySimpleGUI library has transitioned to a commercial model. This version, however, was released under the LGPL-3.0+ license, and this repository republishes it under the same license.

## Overview

PySimpleGUI is a Python package that enables the rapid development of GUIs for applications. It aims to simplify the GUI creation process and make it accessible to beginners and experienced developers alike.

## Features

- **Simple API**: Easy to understand and use, even for those new to Python GUI programming.
- **Cross-Platform**: Works on Windows, Mac, and Linux.
- **Flexible Layouts**: Allows creating complex layouts easily.
- **Wide Range of Widgets**: Supports buttons, sliders, input fields, and more.
- **Integration**: Can be integrated with other Python libraries such as Matplotlib, OpenCV, and others.

## Getting Started

### Installation

To install this version of PySimpleGUI, you can use the following command:

```sh
pip install PySimpleGUI==4.64.61.0.206
```

### Example Usage

Here is a simple example to demonstrate how to create a basic window using PySimpleGUI:

```python
import PySimpleGUI as sg

layout = [[sg.Text("Hello from PySimpleGUI")], [sg.Button("OK")]]

window = sg.Window("Demo", layout)

while True:
    event, values = window.read()
    if event == sg.WIN_CLOSED or event == "OK":
        break

window.close()
```

## Documentation

For detailed documentation and tutorials, refer to the original PySimpleGUI documentation: [PySimpleGUI Documentation](https://pysimplegui.readthedocs.io/en/latest/)

## License

This version of PySimpleGUI is released under the LGPL-3.0+ license. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Please open issues or pull requests for any enhancements, bug fixes, or other improvements.

## Acknowledgements

- [PySimpleGUI](https://github.com/PySimpleGUI/PySimpleGUI) - The original library and inspiration for this project.

## Contact

For any queries or support, feel free to open an issue in this repository.

---

****This repository is not affiliated with or endorsed by the original PySimpleGUI project.****

```

