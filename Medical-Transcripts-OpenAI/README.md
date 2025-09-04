# Medical Transcripts OpenAI API

### Deliverables
1. [Jupyter Notebook Analysis](https://github.com/mauro-cesar-bh/AI-projects/blob/main/Medical-Transcripts-OpenAI/notebook.ipynb)

### Tasks
- OpenAI API request
- API authentication using API keys
- Tools (Function Call)
- Add column to DF using OpenAI output

### Context
Medical professionals often summarize patient encounters in transcripts written in natural language, which include details about symptoms, diagnosis, and treatments. These transcripts can be used for other medical documentation, such as for insurance purposes, but as they are densely packed with medical information, extracting the key data accurately can be challenging.  

You and your team at Lakeside Healthcare Network have decided to leverage the OpenAI API to automatically extract medical information from these transcripts and automate the matching with the appropriate ICD-10 codes. ICD-10 codes are a standardized system used worldwide for diagnosing and billing purposes, such as insurance claims processing.

## The Data
The dataset contains anonymized medical transcriptions categorized by specialty.

## transcriptions.csv
| Column     | Description              |
|------------|--------------------------|
| `"medical_specialty"` | The medical specialty associated with each transcription.  |
| `"transcription"` | Detailed medical transcription texts, with insights into the medical case. |
