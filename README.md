## VOLVQAD: 

VOLVQAD is a volumetric video quality assessment dataset consisting of 376 video sequences and 7,680 ratings from 120 users. The volumetric video sequences are encoded with MPEG V-PCC using 4 different avatar models and 16 varying quality.  The volumetric video sequences are then rendered into test videos for quality assessment using 2 different background colors and 16 different quality switching patterns.  

## Test Video Sequences

The 376 test video sequences can be found in the Google Drive here: 

https://drive.google.com/drive/folders/1tSBaNDE5XPGp-qpAwMMkcPR8nSZLs62r?usp=sharing

## Ratings

The user ratings can be found in the file `ratings.csv` in this repo.

The file contains six columns:

- User ID: P001 to P120.
- Point Cloud Model: **loot**, **redandblack**, **soldier**, and **longdress**
- Quality Switching Pattern: **ConstantR$x$, **Cascade**, **InverseCascade**, **SpikeR$x$**, and InverseSpikeR$x$**
- Quality Feature: **geometry** (for varying geometry quality only), **texture** (for varying texture quality only), or **both** (for varying both geometry and texture quality)
- Background Color: **black** or **gray**
- Rating: User rating of this video

## Paper

This dataset is described in a paper under submission.  If you wish to cite our dataset in the meantime, please email us at ooiwt@comp.nus.edu.sg.

