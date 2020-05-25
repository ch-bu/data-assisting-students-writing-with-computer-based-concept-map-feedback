# Analysis of the structural indicator

This README describes how the structural indicators can be calculated from the raw data of the reliability and validity study.

## Steps

1. Make sure that you have installed all files of the [RFTagger](https://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/). The files should be stored in the folder `analysis/structural_indicators/RFTagger`. For reference of the required files see `analysis/structural_indicators/constants.py`.
2. Make sure that you have installed all the necessary python packages. The python files were written in Python 2.7.
3. Update the path of the raw data files for the reliability and validity study. The raw data files can be found in their respective folders:  `data/study1` for the reliability study, and `data/study2` for the validity study. To analyze the structural indicators for the reliability study update the path in the file `analysis\structural_indicators\reliability_study_structural_indicators.py`. To analyze the structural indicators for the the validity study update the path in the file `analysis\structural_indicators\validity_study_structural_indicators.py`. 
4. Run the scripts with `python analysis\structural_indicators\reliability_study_structural_indicators.py` or `python analysis\structural_indicators\validity_study_structural_indicators.py`.

