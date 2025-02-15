# MS Peak Detection & Processing

This Python script processes mass spectrometry (MS) data by applying smoothing, baseline correction, and peak detection. The results are exported as Excel files for further analysis.

## Features
- Loads MS data from an Excel file.
- Applies Savitzky-Golay smoothing to reduce noise.
- Performs baseline correction using wavelet decomposition.
- Detects peaks based on intensity prominence.
- Saves processed data and detected peaks to separate Excel files.
- Visualizes the raw, smoothed, and baseline-corrected spectra with detected peaks.

## Installation

Ensure you have Python installed (>=3.7). Install the required dependencies using:

```sh
pip install -r requirements.txt
```

## Usage

1. Place your MS data file (Excel format) in the same directory as the script.
2. Modify the `file_path` variable in `main()` to point to your data file.
3. Run the script:

```sh
python ms_peak_processing.py
```

## Output

- `Processed_MS_Data.xlsx`: Contains raw, smoothed, and baseline-corrected intensity values.
- `Detected_Peaks.xlsx`: Contains detected peak m/z values and their corresponding intensities.

## Example Data
An example dataset (`example_data.xlsx`) is provided for testing purposes.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- pywavelets
- scipy

## License
This project is open-source under the MIT License.

---

Feel free to modify the script to suit your specific needs!


