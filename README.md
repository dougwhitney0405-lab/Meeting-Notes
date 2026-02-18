# Meeting Notes Updater (Web)

Browser-only app: upload a Word (.docx) meeting notes file + handwritten notes photo(s) -> OCR -> download updated .docx.

## Template placeholder (optional)
Put `[[HANDWRITTEN_NOTES]]` in your Word template where you want the OCR text inserted.

## Azure OCR (recommended)
Set env vars:
- AZURE_DOCUMENT_INTELLIGENCE_ENDPOINT
- AZURE_DOCUMENT_INTELLIGENCE_KEY

## Local run (optional)
pip install -r requirements.txt
python app.py
