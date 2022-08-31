# inv-proc-autom
Invoice Processing Automation Program
Background: This program is being used for generating the invoices for Prikaway Pvt. Ltd. which is a vendor for Government of India. My friend owns the company and he asked my help to setup the tech part of the operations. I have created the database for the company and developed the system of invoice generation using google sheets. It took approximately 8-9 hours earlier genearting the invoices for a batch of 200 students as the macro script had to be run manually for each student. Post that multile pivots had to be applied in order to create the cover pages
</n>Objective: This program aims at automating the invoice generation process as per the requirements received from the client
Caution: This program takes the data from the google sheet which contains the sales data of the students. It also requires the json file generated via the google cloud platform to access the data. Also, there is a header file which is embedded in each of the invoices
Benefits: 
   1- The entire process of invoice generation for 200 students now takes approximately 30-35 seconds. A single pdf file is generated having individual invoices on each page, which can be printed easily (Print All Pages) thus saving a lot of time and effort
   2-The cover pages can also be printed without applying any additional pivots. A sepearte pdf file called covers is generated which contains summary of the entire bill house-wise and item-wise
   3-There is also an option to print a single invoice incase of any errors found later on
   4- Upon running the program a window interface pops up thus easing up the use and anyone even with limited knowledge can use it
   5- The program automatically drops the students which have appied for Transfer/ Leave in the academic year. This was a specific requirement from the client
   6- Program does multiple calculations and grouping on its own, thus eradicating the multiple edits if required in the google sheets file
Conclusion: This program has helped in generating bills flawlessly and made the life easier for the employees of the company as well as the client. This program is used by people who have very primitive knowledge of computers and utmost care has been taken to make the entire user experience pretty smooth. If you want to adopt my code do let me know and I shall be happy to collaborate on it.
