# Automated-Podcast-Transcription-and-Topic-Segmentation
# 🎧 Podcast Topic & Sentiment Analyzer

An AI-powered application that automatically transcribes, analyzes, and searches podcast content using state-of-the-art NLP and speech-processing models.

---

## 🚀 Features

* 🎤 **Automatic Transcription** using OpenAI Whisper
* 🧩 **Smart Topic Segmentation** (e.g., 40-minute podcast → 21 meaningful segments)
* 🔑 **Keyword Extraction** with KeyBERT
* 📝 **Automatic Summarization** using BART
* 😊 **Sentiment Analysis** with DistilBERT
* 🔍 **Full-Text Search** with MM:SS timestamps
* ⏭️ **Jump to Specific Segments** in the audio player
* 📥 **Export Results** as JSON or CSV

---

## 🎯 Usage

### Basic Workflow

1. Click **Upload Podcast** and select an MP3 or WAV file.
2. Click **Process Podcast**.
3. Wait for processing to complete (typically 5–10 minutes for a 40-minute podcast).
4. Explore the results through the available tabs:

#### 📊 Overview

* Podcast statistics
* Processing metrics
* Visual charts and insights

#### 🔍 Search

* Search transcripts using keywords
* View matching timestamps (MM:SS)
* Navigate directly to relevant sections

#### 🧩 Segments

* Browse automatically generated topic segments
* View summaries, keywords, sentiment, and transcript text

5. Export results as **JSON** or **CSV**.

---

## 🔎 Core Features

### Search Tab

* Keyword-based transcript search
* Timestamp-based navigation
* Instant result filtering

### Segments Tab

For each segment, view:

* Topic keywords
* AI-generated summary
* Sentiment score
* Complete transcript text

### Audio Player Integration

* Click any segment
* Automatically jump to the corresponding timestamp in the audio

---

## 🏗️ Tech Stack

| Component          | Technology                           |
| ------------------ | ------------------------------------ |
| Frontend           | Streamlit                            |
| Transcription      | OpenAI Whisper (Base)                |
| Embeddings         | Sentence Transformers (MiniLM-L6-v2) |
| Keyword Extraction | KeyBERT with MMR                     |
| Summarization      | BART (facebook/bart-large-cnn)       |
| Sentiment Analysis | DistilBERT (SST-2)                   |
| Data Processing    | Pandas                               |
| Visualization      | Plotly                               |
| Audio Processing   | Pydub                                |
| ML Utilities       | Scikit-learn                         |
| Tokenization       | NLTK                                 |

---

## 📚 Libraries Used

* streamlit
* faster-whisper
* transformers
* sentence-transformers
* keybert
* pandas
* plotly
* pydub
* scikit-learn
* nltk

---

## 🤖 Pre-trained Models

### Speech Transcription

* **Whisper Base** – OpenAI Whisper

### Semantic Embeddings

* **all-MiniLM-L6-v2** – Sentence Transformers

### Summarization

* **facebook/bart-large-cnn**

### Sentiment Analysis

* **distilbert-base-uncased-finetuned-sst-2-english**

---

## 📁 Output Format

Each processed podcast includes:

* Full transcript
* Topic segments
* Extracted keywords
* Generated summaries
* Sentiment labels and scores
* Segment timestamps

### Export Options

* JSON
* CSV

---

