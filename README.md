# Minutes Item Generation

This is a basic repository to use
when working on minutes item generation model prototyping.

## Setup

1.  Clone this repository

2.  Download the dataset ZIP file from the following Google Drive link
    and place it withing the cloned repository directory:
    [https://drive.google.com/file/d/1QKeVDlFK08ErUM3pD-bBxwy0OmbtcovR/view?usp=share_link](https://drive.google.com/file/d/1QKeVDlFK08ErUM3pD-bBxwy0OmbtcovR/view?usp=share_link)

3.  Unzip the downloaded dataset in the same directory.
    Once unzipped, your cloned repository directory should have the following structure:

    ```
    ├── cdp-minutes-item-generation-dataset
    │   ├── dataset.parquet
    │   └── transcripts
    │       ├── 001f1a4e4e3c.csv
    │       ├── 008f4e8d253c.csv
    │       ├── 015dd602acce.csv
    │       ├── 01a6d09dd442.csv
    │       ├── ...
    ├── cdp-minutes-item-generation-dataset.zip
    ├── example-data-usage.ipynb
    ├── README.md
    └── requirements.txt
    ```

3.  Create and activate a new conda environment and install
    basic dependencies with `pip install -r requirements.txt`.

4.  Review the basics of using the dataset in the `example-data-usage.ipynb` notebook.

## Notes

Only Seattle City Council meetings are included in this example dataset.
If we have a model showing promise we will get a larger dataset.

## Work

Please push your work as often as possible.
Don't worry about being "done", focus on incremental progress!

trial