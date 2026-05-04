# PixelsSuite.com Testing Project - IT23175198

This repository contains the functional and usability testing suite for [PixelsSuite.com](https://www.pixelssuite.com/), as part of Assignment 1 (Option 2).

## Project Structure
- `IT23175198_image_preview_test.py`: Automated Playwright script for verifying image preview functionality.
- `IT23175198_execution_results.csv`: Automated test execution results.
- `IT23175198_Manual Test Cases for Option 2.xlsx`: 35 manual test scenarios for various website features.
- `results/`: Directory containing execution screenshots.
- `sample.png`: Sample image used for the automated test.
- `IT23175198_Git_Repository_Link.txt`: Link to the public Git repository.

## Features Tested
1. Document conversion
2. PDF editing
3. Image resizing
4. Cropping
5. Compression
6. Image format conversion
7. Meme generation
8. Color picker
9. Image rotation
10. Image flipping

## Prerequisites
- Python 3.11 or higher
- Google Chrome browser

## Installation
1. Clone this repository:
   ```bash
   git clone [PASTE_YOUR_LINK_HERE]
   ```
2. Install the required dependencies:
   ```bash
   pip install playwright openpyxl
   playwright install chromium
   ```

## Running the Tests
To run the automated preview test scenario:
```bash
python IT23175198_image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
```
The results will be automatically updated in `IT23175198_execution_results.csv` and a screenshot will be saved in the `results/` folder.

## Author
- **Registration Number**: IT23175198
