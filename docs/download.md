---
title: Download
layout: page
---

# Download

<div class="hero has-text-centered" id="download">
<div class="myWrapper" markdown="1" align="left">

You can download the dataset from the following [link](https://drive.google.com/drive/folders/1sCiEkGLfMiWH6_RwNsCLVSP9KmZ2a-Tn). You can download each object datset individually.

</div>
</div>

# Format

<div class="hero has-text-centered" id="format">
<div class="myWrapper" markdown="1" align="left">

Inside each object dataset folder you will find everything except the test dataset that is kept private.

The json files have the same format as the original NeRF synthetic dataset.

| **Name**             | **Description**                                                                                                         |
| `train_images`       | The training dataset containing 1000 images                                                                             |
| `val_images`         | The validation dataset containing 500 images                                                                            |
| `train_all.json`     | The camera info of the training dataset for the split **Train 1000**                                                    |
| `train_all_500.json` | The camera info of the training dataset for the split **Train 500**                                                     |
| `train_all_250.json` | The camera info of the training dataset for the split **Train 250**                                                     |
| `train_all_100.json` | The camera info of the training dataset for the split **Train 100**                                                     |
| `val_all.json`        | The camera info of the validation dataset for the splits **Train 1000** / **Train 500** / **Train 250** / **Train 100** |
| `test_all.json`      | The camera info of the test dataset for the splits **Train 1000** / **Train 500** / **Train 250** / **Train 100**       |
| `train_0.json`       | The camera info of the training dataset for the sub-split **Train 0**                                                       |
| `train_1.json`       | The camera info of the training dataset for the sub-split **Train 1**                                                       |
| `train_2.json`       | The camera info of the training dataset for the sub-split **Train 2**                                                       |
| `train_3.json`       | The camera info of the training dataset for the sub-split **Train 3**                                                       |
| `train_4.json`       | The camera info of the training dataset for the sub-split **Train 4**                                                       |
| `train_5.json`       | The camera info of the training dataset for the sub-split **Train 5**                                                       |
| `train_6.json`       | The camera info of the training dataset for the sub-split **Train 6**                                                       |
| `train_7.json`       | The camera info of the training dataset for the sub-split **Train 7**                                                       |
| `val_0.json`         | The camera info of the validation dataset for the sub-split **Train 0**                                                     |
| `val_1.json`         | The camera info of the validation dataset for the sub-split **Train 1**                                                     |
| `val_2.json`         | The camera info of the validation dataset for the sub-split **Train 2**                                                     |
| `val_3.json`         | The camera info of the validation dataset for the sub-split **Train 3**                                                     |
| `val_4.json`         | The camera info of the validation dataset for the sub-split **Train 4**                                                     |
| `val_5.json`         | The camera info of the validation dataset for the sub-split **Train 5**                                                     |
| `val_6.json`         | The camera info of the validation dataset for the sub-split **Train 6**                                                     |
| `val_7.json`         | The camera info of the validation dataset for the sub-split **Train 7**                                                     |
| `test_0.json`        | The camera info of the test dataset for the sub-split **Train 0**                                                           |
| `test_1.json`        | The camera info of the test dataset for the sub-split **Train 1**                                                           |
| `test_2.json`        | The camera info of the test dataset for the sub-split **Train 2**                                                           |
| `test_3.json`        | The camera info of the test dataset for the sub-split **Train 3**                                                           |
| `test_4.json`        | The camera info of the test dataset for the sub-split **Train 4**                                                           |
| `test_5.json`        | The camera info of the test dataset for the sub-split **Train 5**                                                           |
| `test_6.json`        | The camera info of the test dataset for the sub-split **Train 6**                                                           |
| `test_7.json`        | The camera info of the test dataset for the sub-split **Train 7**                                                           |

</div>
</div>

# Training instructions

<div class="hero has-text-centered" id="download">
<div class="myWrapper" markdown="1" align="left">

You can submit your results for two categories:
- evenly distributed splits
- densely localized sub-splits

### EVENLY DISTRIBUTED SPLITS

For each object dataset, you have to train on the splits: `train_all.json`, `train_all_500.json`, `train_all_250.json`, `train_all_100.json`.
For each split you have to validate and test on `val_all.json`and `test_all.json`.

### DENSELY LOCALIZED SUB-SPLITS

For each object dataset, you have to train on all the 8 sub-splits `train_*.json`.
For each sub-split you have to validate and test on all the sub-splits `val_*.json` and `test_*.json`.

</div>
</div>