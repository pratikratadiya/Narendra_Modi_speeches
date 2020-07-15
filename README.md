# Narendra Modi speech transcript dataset

A collection of the speeches delivered by Mr. Narendra Modi, the current Prime Minister of India. The repository contains transcripts of speeches delivered by the Prime Minister in both English and Hindi.

- **175 English speeches**: Delivered by the Mr. Modi at different venues from 2014-18. The raw transcripts have been taken from [here](https://www.github.com/mgupta1410/pm_modi_speeches_repo).

- **50 Hindi speeches**: Manually scraped from the [personal website](https://www.narendramodi.in) of Mr. Modi. The transcripts of 50 speeches selected at random from those delivered by the Prime Minister in 2019.

For further analysis, a transliterated version of the Hindi speeches is also provided.

## Repository overview
```
├── Preprocessing notebooks: Jupyter notebooks containing the code used 
                             for preprocessing the raw speech transcripts
├── Processed speech transcripts: Final preprocessed transcripts of speeches
                              in English and Hindi (Devanagari and Transliterated)
├── Raw speech transcripts: Original raw transcripts of the speeches
└── README.md
```

## Dependencies

- indic_transliteration
- pandas
