# ČSOB.sk Unofficial PDF to JSON transformer

## Requirements
- pdfminer package (`pip install pdf2txt`)

## Usage
`pdf2txt.py exportFileName.pdf > output`
`csob2json.py output > csob.json`

## Known limitations
Semantic is correctly parsed only for card payments.

## Why 
Seems like CSOB.sk is no longer providing any other means of export for regular customers than PDF.