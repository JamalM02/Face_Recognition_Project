# Face Recognition Project – Knesset Faces

This project performs face recognition on a dataset of Israeli Knesset members using DeepFace and OpenCV. It uses facial embeddings to identify individuals and supports similarity comparisons between known and unknown faces.

---

## 📁 Google Drive Resources

Due to file size and structure, all datasets, outputs, and the original development notebook are stored in a shared Google Drive folder:

👉 **[Google Drive – Knesset Face Recognition](https://drive.google.com/drive/folders/1F23B6jyWdH7Jr8JQRq0XIAfBjygHXQv6)**

### Contents:
- `Kneset_face_rec.ipynb` – Main Colab notebook
- `embedding_db.pkl` – Facial embedding database
- `bio.csv` – Biographical data scraped from Hebrew Wikipedia
- `known_faces/` – Folder of labeled face images
- `דוגמא להרצאה.mp4` – Demo video (Hebrew)
- `פרויקט זיהוי פנים.docx` – Full Hebrew documentation
- `inconsistency_report.csv` – Log of name/embedding mismatches

---

## 🔧 Features

- Automated image collection using Google Image Search
- Biography extraction from Hebrew Wikipedia
- DeepFace embedding generation and facial recognition
- Cosine similarity–based identity prediction
- Dataset and results hosted on Google Drive for reproducibility
