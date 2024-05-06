# Mixat: A Data Set of Bilingual Emirati-English Speech
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Mixat is a dataset of Emirati speech code-mixed with English. The dataset consists of 15 hours of speech derived from two public podcasts featuring native Emirati speakers. The data collection process, annotation, and dataset statistics are described in detail in the accompanying paper. If you use this data set, please cite the following paper:

```
@inproceedings{mixat,
  title={Mixat: A Data Set of Bilingual Emirati-English Speech},
  author={Al Ali, Maryam and Aldarmaki, Hanan},
  booktitle={SIGUL 2024: 3rd Annual Meeting of the ELRA/ISCA Special Interest Group on Under-resourced Languages, a Satellite Workshop of LREC-COLING 2024},
  year={2024}
}
```



## Data Set Statistics
- Total duration: 15 hours
- Number of sentences: 5,307
- Percentage of code-switched sentences: 36%
- Average Code Mixing Index (CMI): 0.11
  
#### Breakdown by podcast:
  - ##### Mixat - Part 1:
    This part consists of conversational, multi-speaker utterances from The Direction podcast. 
    - Total sentences: 3,723
    - Code-switched sentences: 1,258
  - ##### Mixat -  Part 2:
    This part consists of narrated utterances by a single female speaker, from the Think With Hessa podcast. 
    - Total sentences: 1,584
    - Code-switched sentences: 805

## Usage 
The Mixat dataset is publicly available for research purposes. We recommend using Part 1 for training, and Part 2 for testing. 

## File Structure
- `Mixat - Part 1.zip` contains the audio files, in .wav format, for Part 1.
- `Mixat - Part 2.zip` contains the audio files, in .wav format, for Part 2.
- `metadata.csv`  contains the text transcriptions for both parts. 

## License
This dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

## Acknowledgement
We thank Mr. Mohammad Al Awadhi, host of The Direction podcast, and Ms. Hessa Alsuwaidi, host of Think With Hessa podcast for allowing us to use their content for creating a dataset to support  academic research on Emirati speech. 


[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
