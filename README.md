# MedAI Nexus

**MedAI Nexus** is an innovative AI-powered solution designed to detect, recognize, and extract meaningful information from handwritten doctor prescriptions. It leverages cutting-edge Deep Learning and Natural Language Processing (NLP) techniques to enhance patient safety, streamline healthcare workflows, and ensure accurate interpretation of prescriptions.

## 🚀 Features

- 🔍 **Handwritten Text Detection & Recognition**  
  Utilizes transformer-based encoder-decoder models (e.g., TrOCR) for accurate interpretation of handwritten text in prescription images.

- 🧠 **Intelligent NLP Processing**  
  Named Entity Recognition (NER) using BERT and spaCy to extract and categorize critical entities such as medicine names, dosages, and usage instructions.

- 🎯 **Post-Processing & Refinement**  
  Implements custom scripts for noise reduction, fuzzy matching, error correction, and structured formatting of recognized text.

- 💻 **User-Friendly Web Interface**  
  A React-based frontend allows users to upload prescription images and view extracted medical information in a clean, intuitive interface.

- ⚙️ **Backend Architecture**  
  Built with PyTorch for model training and inference, leveraging GPU acceleration for high performance.

## 🏗️ System Architecture

1. **Preprocessing & Text Localization**  
   Feature extraction and bounding box detection isolate relevant text regions from input images.

2. **Text Recognition**  
   A transformer-based encoder-decoder model processes localized image regions to generate structured text.

3. **Named Entity Recognition (NER)**  
   Contextual embeddings via BERT identify and classify key medical entities like drug names and dosages.

4. **Post-Processing Pipeline**  
   Custom scripts clean noisy text, correct OCR errors, and enhance output readability using fuzzy string matching.

5. **Frontend & Visualization**  
   ReactJS interface displays extracted prescription details to users and healthcare providers in real time.

## 🧰 Tech Stack

| Category                | Tools & Frameworks                     |
|------------------------|----------------------------------------|
| Deep Learning          | DBNet,TrOCR,CRNN                       |
| NLP                    | Bio BERT,Biom BERT                     |
| Frontend               | ReactJS                                |
| Backend/API            | Python, Flask/FastAPI (optional)       |
| Image Processing       | OpenCV, PIL                            |
| Development Tools      | Visual Studio Code, Git, GitHub        |

## 📷 Example Use Case

1. User uploads an image of a handwritten prescription.
2. The system detects and extracts text from the image.
3. Extracted content is processed to identify medicines, dosages, and instructions.
4. Final output is displayed clearly on the web interface for both patients and providers.

## 🛠️ Installation

> **Note:** Ensure you have Python 3.8+, Node.js, and Git installed.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/medai-nexus.git
   cd medai-nexus
## Snaps of Project

# Hero page
  ![Homepage](https://github.com/user-attachments/assets/7f5d4a58-6182-41a0-9518-8f26f4ce4a4f)

# Signup and Login page

  ![signupmed](https://github.com/user-attachments/assets/e01d9b99-34c7-4349-ac65-0c5fa1d09a46)

  ![LoginMed](https://github.com/user-attachments/assets/27e9aaf9-c14e-4e7d-a354-67553ad6466a)

# Main page

  ![Mainpagemed](https://github.com/user-attachments/assets/6fe0a50c-a371-4801-bfba-6cbb7065f344)

# Sample output 
   
  ![OutputMed](https://github.com/user-attachments/assets/648f1ed6-2afa-4c3e-a18a-7e0cef9012c9)





