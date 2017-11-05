# expenseTrackingPython
Extract information from retail receipts and monitor your expenses.


* The `-i` flag enables interactive mode, where you will be prompted to click and drag the corners of the document. For example, to scan a single image with interactive mode enabled:
```
python3 scan.py --image sample_images/receipt.jpg -image_name receipt.jpg -i


Step 1: Put image in sample_images folder to be parsed.
Step 2: python3 scan.py --image sample_images/receipt.jpg -image_name receipt.jpg -i
Step 3: It will generate processed image in outputs folder. 
Step 4: After image preprocessing you will be presented by a processed image windows on which you can interact with the image and select the required area and close the window. 
Step 5: Finally in the terminal you will be able to see the extracted text from the receipt and the Amount spent by the user,Along with the date.




