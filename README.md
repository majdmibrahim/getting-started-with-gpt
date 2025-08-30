# GPT-Powered Customer Review & Sentiment Analysis

This project demonstrates how to use **OpenAI GPT models** to analyze customer feedback and movie reviews.  
It combines **topic extraction** from user reviews and **sentiment classification** using the IMDB dataset.

---

## Features
- Extracts **main topics** from customer reviews (e.g., "great place", "comfortable stay").
- Performs **sentiment analysis** (positive/negative) on movie reviews.
- Uses the **IMDB Dataset of 50K Movie Reviews** from Kaggle.
- Implements the workflow directly in **Google Colab** with Pandas + OpenAI API.

---

## Dataset
We use the IMDB dataset available on Kaggle:  
👉 [IMDB Dataset of 50K Movie Reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

For Colab integration, the dataset can be uploaded to Google Drive and loaded via:
```python
file_id = "1Z_cxXwJN1hgLUu4Hucu76C-xkwAGQmhv"
csv_file = f"https://drive.google.com/uc?id={file_id}"
df = pd.read_csv(csv_file)

---

## Configuration in Google Colab
Set your OpenAI API key directly in a code cell in Colab:

```python
OPENAI_API_KEY = "your_key_here"

Note: The current API key might have expired. Replace it with a valid one.


