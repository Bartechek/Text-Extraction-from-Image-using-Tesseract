# Text-Extraction-from-Image-using-Tesseract
Use Tesseract OCR to extract text from images.
from PIL import Image
import pytesseract

image = Image.open('image.png')
text = pytesseract.image_to_string(image)

print(text)
