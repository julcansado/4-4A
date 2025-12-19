# 4-4A - Cloud and cloud-shadow masks pipeline for CBERS4A with four spectral bands

## INTRODUCTION

The CBERS-4A image collections do not provide cloud or cloud-shadow mask products, nor metadata that allow users to filter scenes based on cloud coverage. This ongoing project enables users to process single or multiple scenes of interest, generating masks and metadata for the selected images. The method relies on simple band operations using only the blue, green, red, and near-infrared bands, and is reproducible for other products with similar characteristics.

## OBJECTIVE
Propose a simple pipeline to process CBERS-4A images and generate metadata, cloud and cloud-shadow masks.

The access to imagery is done using STAC (Spatial Temporal Asset Catalogue). You can access and explore CBERS-4A collections in [BDC STAC](https://data.inpe.br/bdc/explorer/explore)

Below is an application example of part of the 'CBERS_4A_WPM_20230130_206_130_L4' STAC item:
<br>
<img width="1237" height="718" alt="Image" src="https://github.com/user-attachments/assets/1edd29d3-5a6f-4719-9333-2ca8d01a8f2b" />

<br>

## RESULTS
The proposed pipeline was applied to 100 scenes over the state of Goiás in 2025, and the resulting cloud and cloud shadow masks are in the following [folder](https://drive.google.com/drive/folders/1GXFCXJ6jKAy1Yet8ruZtUHL6jDqBJD8i?usp=drive_link)

The quality of the masks vary greatly - this is still an ongoing project and any suggestions are greatly appreciated!
