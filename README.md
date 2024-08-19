# Resume Parser Backend

## Introduction

- Backend for resume parser application

## Commands for rebuilding image and pushing to GCP artifact registry service using Cloud Build

1.  ```bash
       gcloud builds submit --tag us-central1-docker.pkg.dev/resume-parser-backend-432600/resume-parser-backend-repo/resume-parser-backend
    ```
2.  After the image is pushed to artifact registry, navigate to Cloud Run to redeploy the server

## Technologies used

- Python, spacy, pdf-lib, pymupdf, FastAPI
