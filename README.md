# ArXiv Pdf To Text
A project that uses **ArXiv** API to download and read PDF files according to the search keywords, and formats them to text for NLP purposes

**ArxivDownloader.py** file lets you do a search from ArXiv's API and downloads the PDF files into the download folder, under a subfolder with the
search terms used.

After the download you can run the **pdfReader.py** with the same search terms, and the reader outputs the PDF content to the console.

## Known Issues:

* Database connection is local.
* Read PDF is only outputted to the console.
* Not Handling or keeping track of already donwloaded PDF's from DB.
* Search keywords are written inside the code.

### Note
Some info about setup can be found in **Setup.txt**.
