# Hospital-Management-System
Operations management in large-scale businesses is crucial for the organization’s smooth functioning. Healthcare industry is a vast industry in which there are various components to be looked into during its functioning. Advancements in technology in the healthcare sector improve the quality of patient care, reduce operational costs and shape the entire process in a proper manner. These management systems make business activities function smoothly and assist in efficient patient’s appointment scheduling and medical billing.
With a motive to help healthcare providers make more accurate clinical and medical decisions and stimulate innovation, we have developed a database that gathers data about doctors, patients, vaccination records and billing details. A management system that offers a hospital different ways to analyze patient care and billing services and stabilize the organization’s services is replicated in this database.

## Database Design 
There are four primary tables in the database which are i)Patient ii)Hospital iii)Receipt iv)Billing. These tables act as the parent tables to a few child tables to which they are connected. The parent and child tables are interconnected with each other with necessary foreign key constraints and form the basis of this whole management system. Our tables do not have any transitive dependencies for non-prime attributes making them exist in Third-Normal Form(3NF). 

## Data Collection
We have manually inserted the required data into our tables keeping in mind the foreign key constraints of the tables. Scraping data from the web is also one of the methods to feed the tables with data. This data needs to be preprocessed and cleaned before they are entered into the tables. When this database system is used on a regular basis, it needs some automation and in such cases methods like Web Scraping can be used.


