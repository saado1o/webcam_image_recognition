# AI Image Recognition System

## Setup Instructions

1. Clone the repository
2. Create virtual environment: `python -m venv .venv`
3. Install dependencies: `pip install -r backend/requirements.txt`
4. Download the trained model:
   - Train using `model/train_model.ipynb` in Google Colab
   - Download `custom_model.h5` and place in `trained_model/` folder
5. Run: `cd backend && python app.py`

## File Structure
- `backend/` - Flask application
- `trained_model/` - Model files (add your trained model here)
- `model/` - Training notebook
