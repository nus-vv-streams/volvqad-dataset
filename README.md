## VOLVQAD: 

VOLVQAD is a volumetric video quality assessment dataset consisting 7,680 ratings from 120 users on 376 video sequences. The volumetric video sequences are encoded with MPEG V-PCC using 4 different avatar models and 16 varying quality.  The volumetric video sequences are then rendered into test videos for quality assessment using 2 different background colors and 16 different quality switching patterns.  

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

A paper on this dataset is published in ACM MMSys'23.  If you use the ratings data from our paper, please cite

```
@InProceedings{
    title = "VOLVQAD: An MPEG V-PCC Volumetric Video Quality Assessment Dataset",
    author = "Samuel Rhys Cox and May Lim and Wei Tsang Ooi",
    booktitle = "Proceedings of the 14th ACM International Conference of Multimedia Systems (MMSys)",
    year = 2023,
    month = June,
    address = "Vancouver, Canada",
}
```

## Test Video Sequences

The 376 test video sequences are derived from the [8i Voxelized Full Bodies (8iVFB v2) Point Cloud Dataset](http://plenodb.jpeg.org/pc/8ilabs/) ([license](http://plenodb.jpeg.org/pc/8ilabs/license.pdf))

> Eugene d'Eon, Bob Harrison, Taos Myers, and Philip A. Chou, "8i Voxelized Full Bodies - A Voxelized Point Cloud Dataset," ISO/IEC JTC1/SC29 Joint WG11/WG1 (MPEG/JPEG) input document WG11M40059/WG1M74006, Geneva, January 2017.

The test sequence is about 1.5 GB.  Request to access the test video sequence can be made to [ooiwt@comp.nus.edu.sg](ooiwt@comp.nus.edu.sg)

