# ITS_LIVE-and-CautoRIFT-glacier-velocities
Lindsay Summers
Boise State University - Department of Geosciences

## Correspondence
lindsaysummers@u.boisestate.edu

## Description
Code to calculate glacier surface velocity by extracting CautoRIFT cross-platform velocities, imorting ITS_LIVE velocities, and combining them. Also code to calculate and weight average monthly velocities. 

## Requirements
- velocity outputs from CautoRIFT (https://github.com/jukesliu/CautoRIFT)
- csv containing lon/lat locations for velocity calculations

## Basic Workflow
1. import and activate environment (ITSLIVE_ENVIRONMENT.yml)
2. (optional) extract_cautorift_velocities.ipynb
3. combine_and_weight_cautorift+itslive.ipynb
