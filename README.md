# PDF_Table_into_Excel_extractor
Python Based script to extract all the tables in PDF into excel file

#Requirements<br>
Linux Ubuntu <br>
Python >=3.X <br>
Linux pdftk tool kit (Install poppler tools using apt OR brew) <br>
Use pip3 command to install camelot ie. : pip3 install camelot-py[cv] <br>
Install other dependencies using pip3 <br>


#USAGE <br>
python3 pdf_table_extractor.py <PDF_FILE> <br>
OR <br>
./pdf_table_extractor.py <PDF_FILE> <br>


To remove password from pdf :
import pikepdf
pdf = pikepdf.open('my.pdf',password='pass')
pdf.save('new.pdf')
