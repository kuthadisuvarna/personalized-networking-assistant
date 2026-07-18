# Solution Architecture

## Project Title
Personalized Networking Assistant

## Architecture

User
   │
   ▼
Streamlit Frontend
   │
   ▼
FastAPI Backend
   │
   ├── Event Analyzer (DistilBERT)
   ├── Topic Generator (GPT-2)
   ├── Fact Checker (Wikipedia API)
   ├── History Logger (JSON)
   └── Feedback Logger (JSON)

## Technologies Used
- Python
- FastAPI
- Streamlit
- DistilBERT
- GPT-2
- Wikipedia API
- JSON Storage
- GitHub