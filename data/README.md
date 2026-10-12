# CareCost AI — Hospital Datasets

## Data Sources

This project uses publicly available hospital price-transparency datasets from three Houston hospitals.

| Hospital | File format | Approximate size |
|---|---|---|
| Houston Methodist | JSON | 68.7 MB |
| Memorial Hermann – Texas Medical Center | CSV | 34.5 MB |
| Baylor St. Luke's Medical Center | JSON | 244.2 MB |

## Dataset Access

The original hospital datasets are stored separately because of GitHub file-size limitations.

The datasets were obtained from the hospitals' publicly available price-transparency resources. Direct download links will be added to this README.

## How to Run the Notebook

1. Download the three hospital datasets.
2. Open Google Drive using your Google account.
3. Create a folder named `CareCost_AI`, with a subfolder named `data`.
4. Upload the three hospital files into the `data` folder, keeping their original filenames.
5. Open the CareCost AI notebook in Google Colab.
6. Mount Google Drive and run the notebook cells in order.

**Important:** The notebook reads datasets from `/content/drive/MyDrive/CareCost_AI/data`. Users must place the files in that location before running the data-loading cells.

## Disclaimer

Hospital prices are published estimates and may not represent a patient's final bill. Insurance coverage, plan benefits, and actual costs should be confirmed with the hospital and insurance provider.
