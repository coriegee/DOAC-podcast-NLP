# DOAC Podcast Episode Title Keyword Analysis

### Notebook

[DOAC_podcast_episode_title_keyword_analysis.ipynb](https://github.com/coriegee/DOAC-podcast-NLP/notebooks/DOAC_podcast_episode_title_keyword_analysis.ipynb): This notebook aims to analyse the "Dairy of a CEO" podcast by episode **title keyword frequency** (using TF-IDF) and it's correlation to episode view count.


### Dataset

[DOAC_youtube_dataset.xlsx](https://github.com/coriegee/DOAC-podcast-NLP/data/DOAC_youtube_dataset.xlsx): This dataset was scraped from Youtube on 11th Aug 2023. It contains all of the 215 videos uploaded by @TheDiaryOfACEO channel. Each row represents a single video, with 3 pieces of information: `Title`, `URL` and `Views` for this simple NLP analysis (note URL isn't required).


### Local installation

This project requires python==3.7

```shell
conda create --prefix C:\path\to\env python=3.7
```

Activate the new environment and install the packages in the [requirements.txt]https://github.com/coriegee/DOAC-podcast-NLP/requirements.txt) file

This project also requires downloading the spacy 'en_core_web_sm' model:

```shell
python -m spacy download en_core_web_sm
```