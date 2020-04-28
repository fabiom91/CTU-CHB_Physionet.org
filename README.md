# CTU-CHB_Physionet.org
Data analysis of CTU-CHB Intrapartum Cardiotocography Database v1.0.0 physionet.org database: https://physionet.org/content/ctu-uhb-ctgdb/1.0.0/

## Usage

1. Download the data from here (https://physionet.org/content/ctu-uhb-ctgdb/1.0.0/)[] and rename the folder `physionet_data`
2. then move the folder into the repository folder:
```
CTU-CHB_Physionet.org/
  ...
  physionet_data/
    1001.dat
    1001.hea
    ...
```
3. run the main python 3 script: `python create_csv_database.py` or `python3 create_csv_database.py`

The script will create a file: `database/ann_db.csv` with all annotations and a `.csv` file for each signal recorded in: `database/signals/<RECORDNAME>.csv`
