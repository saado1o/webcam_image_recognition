# ============================
# AI IMAGE RECOGNITION PROJECT
# ============================

# Python
__pycache__/
*.pyc
*.pyo
*.pyd
.Python
.env
.venv
venv/

# Model Files (Large - don't commit)
*.h5
*.hdf5
*.pb
saved_model/

# Training Data (Large - don't commit)
data/
training_data/
*.zip
*.jpg
*.jpeg
*.png

# Temporary Files
*.tmp
*.temp
.DS_Store
Thumbs.db

# IDE
.vscode/
.idea/
*.swp
*.swo

# Logs
*.log
logs/

# OS
.DS_Store
Desktop.ini

# ============================
# KEEP THESE FILES
# ============================

# Application code
!backend/app.py
!backend/model_utils.py
!backend/requirements.txt

# Frontend files
!backend/templates/index.html
!backend/static/css/style.css
!backend/static/js/script.js

# Configuration
!backend/trained_model/class_names.json
!backend/trained_model/model_summary.json

# Training notebook
!model/train_model.ipynb

# Documentation
!README.md