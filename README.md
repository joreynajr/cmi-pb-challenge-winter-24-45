## Processing Steps
Download the data by using:
```
bash workflow/scripts/download_from_webpage_links.sh
```
Note: Don't use `workflow/scripts/download_from_ftp_server.sh`, not working due to certificate issues.

Aftewards run the standarizing notebook with Jupyter:
```
workflow/notebooks/development/Standardize_data.ipynb
```
