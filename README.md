# Neurofeedback EEG Data Analysis Pipeline

## Overview

This repository contains the pipeline for analyzing neurofeedback EEG data from the [Faller et al. (2019) study](https://ieee-dataport.org/open-access/regulation-arousal-online-neurofeedback-improves-human-performance-demanding-sensory).

## Data Availability

### Raw Data

The raw EEG data used in this pipeline can be found in the `Faller_et_al_2019_PNAS_EEG_Neurofeedback_VR_Flight/` directory. You can download the directory [here](https://ieee-dataport.s3.amazonaws.com/open/8627/Faller_et_al_2019_PNAS_EEG_Neurofeedback_VR_Flight.zip?response-content-disposition=attachment%3B%20filename%3D%22Faller_et_al_2019_PNAS_EEG_Neurofeedback_VR_Flight.zip%22&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJOHYI4KJCE6Q7MIQ%2F20241112%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20241112T204407Z&X-Amz-SignedHeaders=Host&X-Amz-Expires=86400&X-Amz-Signature=02fb53fd3e231d8633b2d7c4af2b670df03898e06445d7a86318e70d627b0dd9). 

### Preprocessed Data

The preprocessed data files are stored in the `preprocessed_data/` directory. These files are essential for running parts of the analysis pipeline efficiently without reprocessing from raw data.

**Note**: The `preprocessed_data/` directory is not included in the repository due to its size. You can download the preprocessed data from the following Google Drive link:

[Placeholder for Google Drive Link]()

Once downloaded, place the `preprocessed_data/` folder in the root directory of this repository.

## How to Use
1. **Clone the repository**:
```
git clone https://github.com/your-username/neurofeedback_analysis_pipeline.git
cd neurofeedback_analysis_pipeline
```
2. **Download the raw data**: The raw EEG data can be accessed from the provided source (e.g., an academic dataset repository). Once downloaded, place it in the `Faller_et_al_2019_PNAS_EEG_Neurofeedback_VR_Flight/` directory.
3. **Download the preprocessed data**: Preprocessed data files are available for faster analysis. Download them from the provided source. After downloading, place the `preprocessed_data/` folder in the root directory of the repository.
4. **Run the pipeline**: Once the data is in place, execute the notebook in the root directory. 

## Contact

For any issues or questions, please contact the following people:
- Michael Zhou (mgz2112@columbia.edu)
- Sophie Yangyi (yy3389@columbia.edu)
- Anirudh Natarajan (amn2225@columbia.edu)
- Zhiyu (Century) Sun (zs2710@columbia.edu)



