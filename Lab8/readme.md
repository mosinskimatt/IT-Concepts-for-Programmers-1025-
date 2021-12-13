## Matt Mosinski 12-11-12

## Executive Summary 
 Data is raw bits of information that are converted to knowledge which is its useful form. Data has evolved to big data, which are massively large data sets that conventional data procession technologies do not have the sufficient power to analyze. Data is typically entered into databases that organize the data so that it can be analyzed. Databases are then converted to a UML, Unified Modeling Language so that it can be integrated into code and made useful.
	SQL (Structured Query Language) analyzes, manipulates, and communicates databases. Almost all applications that work with databases make use of SQL. Data analytics has also evolved to data visualization, which makes it easier for viewers to read and understand the data by implementing charts, graphs, maps, etc., to help organize the data.  Large amounts of data are stored in data warehouses by organizations.
	As information technology evolved, ethics and legal standards became a necessity. These standards outline acceptable behaviors. Copyright laws protects media content to condemn illegal recreation and/or distribution. Patents were created to protect ideas of new products and processes, so that others than the individual who created the product or the idea cannot claim it as their own. Privacy issues arose with the web and collection of information. Trademark ensures others cannot steal someone’s brand Keeping PPI (personal identifiable information) protected is a required by law.

## Data, Information and Knowledge
### Compare and contrast data, information and knowledge
Data- Data is pieces of information lacking context. It can be represented as quantitative data with numeric values representing counts, measurements, and/or calculations. Data can also be qualitive, which does not include numeric values, but includes descriptions.
Information- is data with context or data that has gained a meaning.
Knowledge- is information that has been analyzed so it can be used to make decisions, particularly with regards to business matters.

### Relational Data
If one created a database for a small company that included two tables: customers and order, the following would be elements of the relational data
#### Primary Key:
The primary key of the table of customers would be the customer identification, whether it be the customer’s name, username, legal name, or an assigned number. The primary key would be the same for both tables and would be the column where both tables begin.

#### Relationship between customers and orders:
The relationship between the tables is that they both identify the customer. The customer table builds a profile of the customer. The order table takes applies similar information known as fields from the customer table and applies those to the corresponding order number, which is the primary key of the order table. The table now have the ability to reference each other.

#### Foreign key of orders table:
The foreign key of the orders table would be the customer identifier, perhaps a contact method, and the order or invoice number.

### Field Data Types
It is important to properly define the data type in a table to eliminate confusion. The records (rows) of a table contain data, which as we define data, it is information lacking context. Data without fields is nothing more than random numbers and/or descriptions, that have no relation. Fields make the data relatable and gives the data purpose, converting the data into information that can be analyzed into knowledge which decision can be made from.

### Big Data
#### Four "V"s of Big Data
The four V’s of big data are characteristics that data must possess in order to consider it to be big data:
Volume- Describes the mass quantity of data involved in big data.
Variety- Defines different types of data, structured and unstructured.
Velocity- Speed at which the data is generated.
Variability- Inconsistency shown by the data

#### Technology Driving the need for Big Data
Technology that has driven the increased need for big data is social media (500TB of new data ingested into facebook/day), airlines (jet engines generate 10TB of data in 30 mins of flight time), the NYSE (1TB of data/day), and retail. Employers such as Costco process millions of transactions a day. The data is stored in very large databases, day after day for years, so that it can be analyzed for future decision making intended to grow the business.

## Structured Query Language (SQL) 
### RDBMS and SQL
SQL is Structured Query Language that is used for managing data in relational database management systems. Allows the user to update and communicate databases and tables.

RDBMS - Relational Database Management System -  is the basis for SQL and modern database systems such as Oracle, and Microsoft Access. RDBMS stores data into tables which is a collection of related data entries consisting of columns and rows.
### Relationship, Primary and Foreign Keys
## SQL Injections
SQL injection is one of the most common security threats that could destroy a database by injecting malicious SQL statements through web page inputs. For example, a webpage gives the visitor an option to input a username, and the viewer injects malicious code, the malicious code will run on the database and potential harm the database. 
Programmers that maintain a website can use parameters to implement more control on what a visitor can submit into an input field. The engine checks that the input is correct prior to executing the input, thus limiting the possibility of malicious SQL injection. Some websites prohibit certain characters in username and password fields to avoid malicious SQL injection.

## Ethical and Legal Implications
### Code of Ethics
The purpose of a code of ethics is to outline operational expectations for all involved in an organization. Those who wish to be involved must agree to the code of ethics which outlines acceptable and unacceptable conduct that may result in violation of the code. ACM (Association for Computing Machinery) developed a code of ethics for computing discipline to outline ethical conduct for those who use computers, so that all can benefit. Although ethics are not law and are largely arbitrary because of different perspectives, ethics aim to be beneficially for all members of an organization. If violations occur, members can be reprimanded or expelled from the organization.
### Intellectual Property
Intellectual Property is something innovative that someone has created through the process of thought. The creation could be an idea, an image, a good or service, etc. Whereas physical property is something that physically belongs to someone. Trademarking intellectual property is important in that it protects the brand, name, and/or logo idea so that no one else can steal it or use it without permission in order to collect capital gains. 

### Information Collection
COPPA, FERPA, AND HIPAA make it illegal to share Personally Identifiable Information to unprivileged parties, through any medium, including the internet. These are very strict laws and if an organization is found in violation of these laws, strict legal recourse can be taken in order to compensate victims of the violation.

## Conclusion
Structuring and storing data so that its organized, readable, and relevant is a good practice. Data is a crucial element in the IT industry and ensuring the protection and proper handling of it through the individual, organizations, and legal implications is a must.
