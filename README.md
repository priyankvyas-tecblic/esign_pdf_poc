# esign_pdf_poc

this POC is all about signing a PDF with cryptography

## setup project
```
git clone https://github.com/priyankvyas-tecblic/esign_pdf_poc
pip install -r requirements.txt
```
```
python3 sign_pdf.py --help
python3 sign_pdf.py --load
python3 sign_pdf.py -i "./static/sample.pdf" -s "BM" -x 300 -y 400
```
+ -h, --help            show this help message and exit
+ -l, --load            Load the required configurations and create the certificate
+ -i INPUT_PATH, --input_path INPUT_PATH
                        Enter the path of the file or the folder to process
+ -s SIGNATUREID, --signatureID SIGNATUREID
                        Enter the ID of the signature -p PAGES, --pages PAGES
                        Enter the pages to consider e.g.: [1,3]
+ -x X_COORDINATE, --x_coordinate X_COORDINATE
                        Enter the x coordinate.
+ -y Y_COORDINATE, --y_coordinate Y_COORDINATE
                        Enter the y coordinate.
