<div align="center">
  <img src="project_logo.png" alt="Sentiment Analysis Project Logo">
</div>

# Sentiment Analysis Project

Uncover the Emotions Behind Text with Sentiment Analysis! 📊

Welcome to our Sentiment Analysis Project, where we dive into the fascinating world of Natural Language Processing (NLP) to unravel the sentiments hidden within text. This README will be your guide to understanding the significance, structure, and technical prowess of our project.

## :sparkles: Why Sentiment Analysis Matters

Sentiment analysis isn't just about words – it's about emotions, opinions, and the pulse of the digital world. In this project, we embark on a journey to decode the sentiment behind tweets, particularly those revolving around COVID-19 vaccination and healthcare. Harnessing the incredible power of BERT, a top-tier NLP model, we're poised to uncover insights that words alone can't reveal.

## :file_folder: Project Structure

Our sentiment analysis endeavor is meticulously organized:

- **Introduction:** Delve into the magic of NLP sentiment analysis and get a sneak peek into our dual goals: crafting a formidable bert-base-cased NLP model and crafting a user-friendly Gradio app for tweet sentiment analysis.

- **EDA (Exploratory Data Analysis):** The data is the heart of sentiment analysis. With histograms, distribution plots, and word clouds, we'll paint a picture of our tweet dataset, unveiling its hidden treasures.

- **Model:** We're unleashing the power of BERT! Discover why the bert-base-cased model is the knight in shining armor for sentiment analysis.

- **Tokenizer:** The autotokenizer from BERT is our trusty scribe, transmuting raw text into model-friendly magic.

- **App:** Behold the Gradio app! Witness how our BERT-based sentiment analysis model connects with the real world, predicting sentiment in real-time as you type.

- **Data/:** The vault where our data resides, essential for training and testing the BERT model.

- **README.md:** You're here! This comprehensive guide to the project's grandeur, complete with installation instructions, usage guidelines, and all things marvelous.

- **Requirements.txt:** The secret recipe – all the Python libraries and dependencies needed to savor the project's flavors.

## :rocket: The Tech Chronicles

### Introduction

Sentiment analysis isn't just an NLP task; it's decoding the human essence in text. Our mission? Empower BERT to understand the emotions resonating in tweets about COVID-19 vaccination and healthcare.

### EDA (Exploratory Data Analysis)

Before the model waltzes in, let's sway with our data. Histograms, distribution plots, and bewitching word clouds – all to unveil the soul of our tweet dataset.

#### Distribution Plot for Label Column

```python
sns.displot(df['label'], color='green', kde=True, rug=False)
plt.xlabel('Label', fontsize=15)
plt.ylabel('Frequency', fontsize=15)
plt.title('Distribution of Labels', fontsize=15)
plt.show()

