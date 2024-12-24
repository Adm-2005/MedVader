---
title: Med Vader
emoji: ![Darth Vader](assets/images/darth_vader.png)
colorFrom: black
colorTo: black
sdk: gradio
sdk_version: 5.0.1
app_file: app.py
pinned: false
license: mit
short_description: The dark side of medication, uncovered for you.
---
# MedVader

MedVader is a RAG agent that helps users get information about the adverse effects of a medicine.

## 📂 Project Structure
```bash
MedVader/
├── assets/
│   ├── images/
│   │   ├── darth_vader.png    
├── modules/
│   ├── data_fetching.py    # Communicating with API
│   ├── rag_pipeline.py     # Generating LLM response
├── .gitattributes
├── .gitignore
├── app.py                  # Entry point
├── LICENSE.md              # MIT license file
├── README.md               # Project documentation
└── requirements.txt        # Project dependencies     
```

## 🛠️ Technologies Used
- **Gradio:** Agent interface
- **LangChain:** RAG pipeline
- **RxNorm:** Drug Database

## 📎 Important Links
- **GitHub Repository**: [Click Here](https://github.com/Adm-2005/MedVader)
- **HuggingFace Space**: [Click Here](https://huggingface.co/spaces/akshat-mishra/Med-Vader)