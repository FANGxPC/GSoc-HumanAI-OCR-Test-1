# GSoc-HumanAI-OCR-Test-1

Test I: Optical Character Recognition of printed historical sources.

## Project goal
This repository contains a notebook-based MVP pipeline for:
- extracting pages from a PDF source,
- isolating text blocks with OpenCV,
- running OCR with Tesseract (Spanish model),
- preparing a cleanup prompt for an LLM step,
- and reporting OCR quality with Character Error Rate (CER).

## Main artifact
- `/home/runner/work/GSoc-HumanAI-OCR-Test-1/GSoc-HumanAI-OCR-Test-1/GSoc_HumanAI_OCR_Test_1.ipynb`

## Expected runtime environment
The notebook is written for Google Colab and uses `/content/dataset/...` paths.

## Quick usage flow
1. Upload one or more PDFs to `/content/dataset/pdfs`.
2. Run the notebook cells in order.
3. Inspect cropped images in `/content/dataset/cropped_text`.
4. Review OCR output and CER evaluation in the final cell.
