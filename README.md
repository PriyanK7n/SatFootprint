# SatelliteFootprintDetection
> This Project aims to be used for Footprint Detection of Buildings in Satellite Images by using semantic segmentation.

## Dataset Used:
- This open source dataset includes 24 images (one per month) covering ~100 unique geographies. 
- The dataset will comprise over 40,000 square kilometers of imagery and exhaustive polygon labels of building footprints in the imagery, totaling over 10 million individual annotations. 
### The Dataset is available on [kaggle](https://www.kaggle.com/amerii/spacenet-7-multitemporal-urban-development)

### The Dataset is available on  AWS as a Public Dataset:

> Training Data
 To download ~4km x 4km imagery data cubes with associated buildings footprint labels:

- aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_train.tar.gz . 
- aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_train_csvs.tar.gz . 
> Testing Data
- aws s3 cp s3://spacenet-dataset/spacenet/SN7_buildings/tarballs/SN7_buildings_test_public.tar.gz . 


![](https://github.com/PriyanK7n/SatFootprintDetection/blob/main/images/s7.gif)

The Data – ~100 locations, spread out across the globe and contains:

![](https://github.com/PriyanK7n/SatFootprintDetection/blob/main/images/details.png)


## Models:
The Models trained are stored in [GoogleDrive](https://drive.google.com/file/d/10Hk2q_D_9Y13tzT41e5o3-sLuO3gRWV2/view?usp=sharing)


Installation:
~~~~~~~~~~~~

GIT:

.. code-block:: bash

  git clone https://github.com/PriyanK7n/SatFootprintDetection
  cd SatFootprintDetection
  pip install -r requirements.txt
  pip install -e .


