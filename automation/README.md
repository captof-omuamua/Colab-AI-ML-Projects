# Automation

| Notebook | What it covers | Stage |
| --- | --- | --- |
| [16_language_aware_article_and_pdf_discovery.ipynb](16_language_aware_article_and_pdf_discovery.ipynb) | HTML article extraction, language-based text folders and PDF-link discovery. | Prototype |
| [17_s3_object_storage_uploads.ipynb](17_s3_object_storage_uploads.ipynb) | MinIO/S3-compatible object listing, file manifests and recursive image uploads. | Prototype |

## Running these notebooks

Requests, Beautiful Soup and langdetect for HTML experiments; MinIO for object storage. Supply your own endpoints, credentials, input folders and site-specific selectors before running network operations.

Open one notebook in Colab or Jupyter, read its setup cells, set the input paths, and then run the sections you need. Training and network operations are not run automatically by this repository.

Object storage reads `MINIO_ENDPOINT`, `MINIO_BUCKET`, `MINIO_ACCESS_KEY`, `MINIO_SECRET_KEY`, `UPLOAD_SOURCE_DIR` and optional `UPLOAD_PREFIX` from environment variables. Object-deletion examples are disabled unless `ALLOW_OBJECT_DELETION=YES` is explicitly set. No storage service was contacted during review.
