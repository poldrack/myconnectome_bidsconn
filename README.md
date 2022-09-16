## BIDS-connectivity example for myconnectome dataset

This is an example of one session of functional connectivity data from the MyConnectome project, based on the raw data in [OpenNeuro ds000031](https://openneuro.org/datasets/ds000031).  This example follows (roughly) the scheme outlined in [BIDS BEP017](https://docs.google.com/document/d/1ugBdUF6dhElXdj3u9vw0iWjE6f_Bibsro3ah7sRV0GA/edit#).

The files currently contain data; before uploading to BIDS-examples, the files will be emptied to save space.

The structure of the files is as follows:

```
ds000031
└── derivatives
    ├── atlas-aseg
    │   └── aparc+aseg_reg2wasu333.nii.gz
    ├── atlas-russome
    │   ├── atlas-russome_hemis-left_dseg.gii
    │   └── atlas-russome_hemis-right_dseg.gii
    ├── funcconn
    │   ├── code
    │   │   └── funcconn.py
    │   └── sub-01
    │       └── ses-014
    │           └── func
    │               ├── sub-01_ses-014_corrmat.json
    │               ├── sub-01_ses-014_corrmat.tsv
    │               ├── sub-01_ses-014_nodelabels.json
    │               └── sub-01_ses-014_nodelabels.tsv
    └── parcellation
        └── sub-01
            └── ses-014
                └── func
                    ├── sub-01_ses-014_timeseries.json
                    └── sub-01_ses-014_timeseries.tsv
```

