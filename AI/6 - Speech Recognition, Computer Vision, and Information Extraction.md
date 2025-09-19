# Chapter 6: Speech Recognition, Computer Vision, and Information Extraction

## Speech Recognition and Synthesis

### Speech Recognition

- Converts spoken language (audio signals) into text.
- Key components:
    1. **Acoustic Model:** Converts audio signals into phonemes (basic sound units).
    2. **Language Model:** Maps phonemes to meaningful words and phrases.

### Speech Synthesis

- Generates spoken output (text-to-speech).
- Converts text back into natural-sounding audio.

### Azure AI Speech Services

- Provides:
    - Speech-to-text (transcription)
    - Text-to-speech (voice generation)
    - Speech translation (real-time spoken language translation)

---

## Computer Vision

Computer vision enables machines to interpret and understand visual data such as images and videos.

### Core Capabilities

1. **Image Analysis:** Detects, classifies, captions images, and extracts insights.
2. **Spatial Analysis:** Detects people’s presence and movements in real time.
3. **Facial Recognition:** Recognizes and verifies human identities.
4. **Optical Character Recognition (OCR):** Extracts printed and handwritten text from images.

### Filters and Convolutional Filtering

- **Filters:** Modify pixel values to create visual effects.
- **Filter Kernel:** Arrays applied to images.
- **Convolutional Filtering:** Slides the filter kernel over images to detect features.

### Convolutional Neural Networks (CNN)

- Deep learning models specialized for image tasks.
- Use filters to extract feature maps.
- Commonly used for image classification and recognition.

---

## Multi-Modal Models

- Combine vision and language understanding.
- Inspired by Transformer architecture.
- Use image encoders to extract features and language encoders for text embeddings.
- Trained on large datasets of captioned images without fixed labels.

---

## Azure AI Vision Services

- **Azure AI Vision Image Analysis:** Object detection, tagging, captioning, and OCR.
- **Azure AI Face:** Detects and analyzes human faces.

---

## AI-powered Information Extraction

Extracts structured data from both structured and unstructured content to generate insights.

### Content Types

- **Structured Content:** Consistent format (e.g., tax forms, tables).
- **Unstructured Content:** No fixed format (e.g., images, audio, video, emails).

### Information Extraction Process

1. **Source Identification:** Locate where data resides.
2. **Extraction:** Use ML to pull data from sources.
3. **Transformation and Structuring:** Convert data into structured formats (e.g., JSON, tables).
4. **Storage and Integration:** Store data in databases, lakes, or analytics systems.

---

## Document Intelligence

- Processes documents to extract semantic meaning.
- Example: Extracting invoice details from images.

### Knowledge Mining Pipeline

1. **Document Cracking:** Extracts raw text from documents.
2. **AI Enrichment:** Adds metadata and captions.
3. **Knowledge Store:** Stores enriched data for further use.

---

## Azure AI Services for Information Extraction

1. **Azure AI Vision Image Analysis:** Detects objects, generates captions, extracts text.
2. **Azure AI Content Understanding:** Multimodal, schema-based field extraction from structured/unstructured data.
3. **Azure AI Document Intelligence:** Extracts fields from digital forms and documents with prebuilt/custom models.
4. **Azure AI Search:** AI-assisted indexing and search across structured/unstructured data; integrates with other AI skills for deep insights.

---

## Azure AI Search Components and Workflow

- **Indexer:** Ingests data from sources like Azure Storage.
- **Index:** Stores searchable content fields.
- **Skills:** AI-powered enrichment tasks (vision, content understanding, document intelligence).

### Indexer Process

1. Data ingestion.
2. Document cracking (extract text/images).
3. Apply AI skills to extract and enrich information.
4. Persist extracted fields in an index.

### Knowledge Store

- Stores data assets like:
    - Tables of extracted fields
    - Document images
    - JSON files

---
