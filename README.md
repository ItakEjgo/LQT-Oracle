# LQT-Oracle
### This repo contains the link of terrain datasets and code of LQT-Oracle. The LQT-Oracle is an indexing-based data structure for efficent arbitrary point-to-arbitrary point shortest distance queries on terrain surfaces. We do not impose any assumption on the query points and the terrain faces could be either weighted or unweighted.

### The terrain datasets we use are from **Distance Oracle on Terrain Surface. SIGMOD Conference 2017: 1211-1226** and **Close Weighted Shortest Paths on 3D Terrain Surfaces. SIGSPATIAL/GIS 2020: 597-607**. Here is the link of the datasets we use: https://drive.google.com/drive/folders/1HMhKqvZRO3d7LX2TtShlp3cGoUa4JIpT?usp=sharing. All datasets are .off format. Please refer to https://en.wikipedia.org/wiki/OFF_(file_format) for details of the format.
1) The BH (BearHead), EP (EaglePeak) and SF (San Francisco) datasets from the paper: Distance Oracle on Terrain Surface, SIGMOD Conference 2017. The files with surfix high are high resolution datasets and has millions of faces. The files with surfix are relative low resolution datasets with about 0.3 million faces. To generate a partition of high resolution terrain dataset, we use a simple partition method and please refer to our code for details and usages.
2) The sigspatial2020_processed_TINs.zip contains the processed dataset from the paper: Close Weighted Shortest Paths on 3D Terrain Surfaces, SIGSPATIAL/GIS 2020. The origional datasets are not .off format and we processed the original data to .off format. These datasets are relative small with about 4000 faces for each.
3) These terrain surfaces does not contain the face weight information and please refer to our code for face weight generation part.

### The code of LQT-Oracle is in https://github.com/ItakEjgo/weighted_distance_oracle. We will opensource the code of LQT-Oracle later.

