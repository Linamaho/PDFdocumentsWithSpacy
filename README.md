# PDFdocumentsWithSpacy

#This is a 

## How to install the Spacy PDF reader

First we need to install the required packages. From command line run

```python pip install spacypdfreader[pytesseract]
```

I got some warnings about dependency conflicts, even though it worked ok. This package was written some years ago and requires a version of Spacy 3.4.0 but I’m currently using Spacy 3.6.1

UserWarning: [W095] Model 'en_core_web_sm' (3.3.0) was trained with spaCy v3.3.0 and may not be 100% compatible with the current version (3.6.1). If you see errors or degraded performance, download a newer compatible model or retrain your custom model with the current spaCy version. For more details and available updates, run: python -m spacy validate
  warnings.warn(warn_msg)

Also, if you are running the SpacyPDFreader on Google Colab, you will need to manually install the SpacyPDFreader package. For that, just run the same installation command line.

After that, the most “difficult” part is over. 

To test the pdf reader I’ll use the PDF document that comes as an example. You need to download it to the same folder where your jupyter notebook is located. 

The PDF reader package was created by Sam Edwardes. Check his Github: https://github.com/SamEdwardes
