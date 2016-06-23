# Download all scripts from imsdb.com

This repository contains python code to download (and clean) all 
scripts on the website [http://www.imsdb.com](http://www.imsdb.com).

## To download

```
git clone https://github.com/j2kun/imsdb_download_all_scripts
cd imsdb_download_all_scripts
virtualenv venv && source venv/bin/activate
pip install -r requirements.txt
python download_all_scripts.py
```

Takes about 15 minutes, downloads about 1,100 scripts.
