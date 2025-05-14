How to use this repository:
1) needed files
2) code running/modification requirements

1) Needed Files
   To run the notebook, the following files are required, 'ma_od_main_JT00_2022.csv.gsv' and 'MassachussetsCensusTractData.csv',
   'ma_od_main_JT00_2022.csv.gsv' must be unzipped before running (the data is stored as file names).
    'altTransit.csv' is also required if you do not wish to create multiple API keys.
   While an attempt was made to include gpickle files to expedite the running of the code, these files were too large to be stored on github.
   Running the notebook cells in order should provide this data, however it may take a while to run certain cells.

2) code running/modification requirements
The file location of 'ma_od_main_JT00_2022.csv' should be updated in the first cell to wherever it is in your directory.
Other than that, code can mostly be run in order. The exception is cells with API calls. For these cells, the API key has been
removed for privacy. If you wish to run them, you can replace the API key with your own. If you do not wish to run these cells, you can simply skip to where
'altTransit.csv' is read into a dataframe as this will provide all data the API would have provided.
