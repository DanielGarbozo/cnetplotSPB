# Research Networks and Scholar Profiles Project

This project includes scripts to generate network plots of researchers' areas of interest and to fetch Google Scholar profiles. Additionally, a function is provided to clean and translate areas of interest in an Excel file.

## Requirements

- Python 3.x
- Additional packages specified in `requirements.txt`

## Installation

Clone the repository:

```sh
git clone https://github.com/DanielGarbozo/cnetplotSPB.git
cd 'directory'
```

Install the dependencies:

```sh
pip install -r requirements.txt
```

## Usage

### Generate Network Plot

```sh
python get_network_plot.py <path_to_excel_file> <path_to_save_image>
```

Example:

```sh
python get_network_plot.py input_file.xlsx output_image.png
```

### Get Google Scholar Profiles

```sh
python get_scholar_profiles.py <input_file> [<output_file>]
```

Example:

```sh
python get_scholar_profiles.py names_test.txt profiles.xlsx
```

### Process and Translate Research Profiles

```sh
python setup_interest.py <input_file> <cleaned_file> <translated_file> [--lang <target_language>]
```

Example:

```sh
python setup_interest.py input_file.xlsx translated_file.xlsx --lang es
```

## Contributing

1. Fork the project.
2. Create a new branch with your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License

MIT License

Copyright (c) 2024 Daniel Garbozo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

