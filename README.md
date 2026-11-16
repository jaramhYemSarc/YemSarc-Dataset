# YemSarc: A Multimodal Benchmark Dataset for Sarcasm Detection in Yemeni and Related Arabic Dialects

## 📌 Overview
**YemSarc** is the first multimodal (text, audio, and video) benchmark dataset for sarcasm detection in Yemeni dialectal Arabic and seven additional Arabic dialects. 

It comprises **630 balanced utterances** (315 sarcastic, 315 non-sarcastic) drawn from naturally occurring conversational exchanges across eight Arabic dialects: *Mahwiti, Ibbi, Adeni, Sanaani, Dhamari, Saudi, Egyptian, and Taizzi*. 

Each target utterance is paired with its preceding conversational context and is represented across three synchronized modalities:
- 📝 **Text**: Written transcript (Arabic).
- 🔊 **Audio**: Extracted speech segments.
- 🎥 **Video**: Frame sequences.

## 📂 Dataset Structure
The dataset is organized as follows:
- `metadata.csv`: Contains the 16 technical fields including segment identifiers, corrected transcripts, speaker information, sarcasm labels (0/1), and dialect labels.
- `/text/`: Contains `.txt` files for the transcripts.
- `/audio/`: Contains `.wav` audio files.
- `/video/`: Contains `.mp4` video files or frame sequences.

*(Note: You can update this section based on how you actually name your folders).*

## 🏗️ Construction & Annotation
The dataset was constructed from two widely popular Yemeni comedic drama series (*Bayt Al-Madaliz* and *Khuruj Nihai*). Annotation was carried out through a structured three-phase protocol by three expert academic linguists, achieving a final inter-annotator agreement of **Fleiss' Kappa = 0.7473**.

## 📜 License
This dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. It is intended for non-commercial academic research purposes.

## 🔗 Permanent Repositories & DOI
For long-term archiving and citation, the dataset is also available at:
- **Mendeley Data**: [https://doi.org/10.17632/n2bp7yfmr7.1](https://doi.org/10.17632/n2bp7yfmr7.1)
- **Zenodo**: [https://doi.org/10.5281/zenodo.23622433](https://doi.org/10.5281/zenodo.23622433)

## 📖 Citation
If you use this dataset in your research, please cite our manuscript:

> Jaramh, R., Al-Gaphari, G., & Al-Ansi, I. A. (2026). *YemSarc: A Multimodal Benchmark Dataset for Sarcasm Detection in Yemeni and Related Arabic Dialects*. [Manuscript submitted for publication].

## 📧 Contact
For any questions or inquiries, please contact:
**Radwan Jaramh** (Corresponding Author)
- Email: radwan@alqadaeh.com
- Institution: Sana'a University, Yemen
