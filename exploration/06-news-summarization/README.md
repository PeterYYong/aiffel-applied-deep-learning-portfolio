# Abstractive and Extractive News Summarization

> **Category:** Training project
> **Curriculum unit:** AIFFEL Research Program / Exploration / Ex06
> **Notebook:** [`abstractive-extractive-news-summarization.ipynb`](abstractive-extractive-news-summarization.ipynb)

This course project compares two approaches to English news summarization using the `news_summary_more.csv` dataset from the [News Summary dataset repository](https://github.com/sunnysai12345/News_Summary).

## Methods demonstrated

- Text cleaning, contraction normalization, stop-word handling, sequence-length analysis, and train/validation splitting
- Tokenization, vocabulary filtering, integer encoding, and sequence padding
- Abstractive summarization with an encoder–decoder LSTM, attention, teacher-forced training, and a separate inference decoder
- Qualitative comparison of reference headlines and generated summaries
- Extractive summarization experiments using `summa.summarizer`

The notebook contains executed preprocessing, model-training output, loss curves, and example summaries. These outputs document course execution but are not presented as a validated benchmark or research result.

## Authorship and contribution note

The original repository README was an unfilled peer-review template: it did not identify a coder, reviewer, provided baseline, or individual modifications. The notebook also retains course instructions and evaluation criteria. It should therefore be described conservatively as an executed AIFFEL training notebook. Sole authorship and the precise contribution beyond the course scaffold remain undocumented and should be clarified before this project is featured in a CV or research portfolio.
