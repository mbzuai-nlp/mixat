# Mixat: A Data Set of Bilingual Emirati-English Speech <a href=''> <a href='https://arxiv.org/pdf/2405.02578'><img src='https://img.shields.io/badge/paper-Paper-red'></a> 

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

Mixat is a dataset of Emirati speech code-mixed with English. The dataset consists of 15 hours of speech derived from two public podcasts featuring native Emirati speakers. The data collection process, annotation, and dataset statistics are described in detail in the accompanying paper. If you use this data set, please cite the following paper:

```
@inproceedings{al-ali-aldarmaki-2024-mixat,
    title = "Mixat: A Data Set of Bilingual Emirati-{E}nglish Speech",
    author = "Al Ali, Maryam Khalifa  and
      Aldarmaki, Hanan",
    booktitle = "Proceedings of the 3rd Annual Meeting of the Special Interest Group on Under-resourced Languages @ LREC-COLING 2024",
    month = may,
    year = "2024",
    address = "Torino, Italia",
    publisher = "ELRA and ICCL",
    url = "https://aclanthology.org/2024.sigul-1.26",
    pages = "222--226"
}

```


## Data Set Statistics
- Total duration: 15 hours
- Number of sentences: 5,307
- Percentage of code-switched sentences: 36%
- Average Code Mixing Index (CMI): 0.11
  
#### Breakdown by podcast:
  - ##### Mixat - Part 1: [Download](https://github.com/Maryam-AlAli/Mixat-dataset/blob/main/Mixat%20-%20Part%201.zip?download=)
    This part consists of conversational, multi-speaker utterances from The Direction podcast. 
    - Total sentences: 3,723
    - Code-switched sentences: 1,258
  - ##### Mixat -  Part 2: [Download](https://github.com/Maryam-AlAli/Mixat-dataset/blob/main/Mixat%20-%20Part%202.zip?download=)
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
