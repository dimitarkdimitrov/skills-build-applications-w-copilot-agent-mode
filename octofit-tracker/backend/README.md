# OctoFit Tracker Backend

This folder will contain the Django backend for OctoFit Tracker.

## Setup

Create a Python virtual environment and install dependencies:

```bash
python3 -m venv octofit-tracker/backend/venv
source octofit-tracker/backend/venv/bin/activate
pip install -r octofit-tracker/backend/requirements.txt
```

Notes:
- The project intends to use Django, Django REST Framework, djongo and MongoDB (via djongo/pymongo) per the requirements file.
- Use Django's ORM for models and migrations; avoid direct MongoDB scripts for schema creation.
