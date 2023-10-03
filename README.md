# ISSI_groundmag_review
ISSI review paper on the interpretation of ground magnetic field measurements


To read list of IMAGE magnetometers with Python, use
```
g = pd.read_table("IMAGE_magnetometers.txt", sep=" ", skipinitialspace=True, header=None, names=["number", "code", "name", "glat", "glon", "mlat", "mlon", "provider", "network", "start_date", "end_date", ], index_col=0, )
```