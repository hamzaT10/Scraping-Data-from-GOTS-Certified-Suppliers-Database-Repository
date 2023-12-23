Data Sources and Collection :
Our data collection process hinges on the intricate practice of web scraping, a sophisticated method employed to extract comprehensive information from websites. To execute this method, we
leverage Selenium WebDriver, an invaluable tool designed for automating web browser interactions. Specifically, we target the primary website "https://global-standard.org/find-suppliers-shops-andinputs/certified-suppliers/database/search" to orchestrate our data gathering. Within this virtual
environment, our automated scripts meticulously simulate user-initiated actions by navigating through various sections, clicking buttons, and extracting targeted data. During the web scraping process, Selenium becomes the linchpin, utilizing its robust functionalities to meticulously navigate HTML elements. By harnessing XPath expressions and element locators such as By.XPATH, we precisely pinpoint and interact with buttons and links embedded within the webpage. For instance, the initial button click within the provided web page's
search results initiates our scraping process. Upon moving to subsequent pages, Selenium recognizes the set limit of 50 through XPath expressions, considerably expanding the breadth of accessible data within the table. Subsequently, we carefully locate and extract the table that contains links situated in the last column, methodically
accumulating an all-encompassing list. We then proceed to click on the "next" icon, enabling navigation to subsequent pages, ensuring the continuous extraction of relevant data until we attain
1000 company links. This compilation of links acts as our pathway for obtaining additional data from individual company pages. As we progress to these company-specific detail pages, our scraping methodology escalates
in complexity. Selenium's precision enables us to isolate and extract key HTML elements housing
pivotal information, including company, brand_name, country, product_category, contact_name, email_address, Address, license_number, pdf, certification_body, expiry_date, product_details. This
meticulous extraction of data is then organized and structured into a CSV file format, primed for future analysis and interpretation. In essence, this technical approach harnesses Selenium's formidable capabilities,
orchestrates intricate element selections, and systematically navigates web pages to meticulously harvest pertinent data from the target website. The fusion of precise configurations, automated
scraping methodologies, and data structuring lays the groundwork for deriving actionable insights from online sources.
II- Description of the Database:
The database used in this study is a collection of data describing a portfolio of 1000 details
about certifications related to various companies. Moving on to examine the structure of our
database, we note that it is organized in the form of a table comprising twelve distinct columns.The database contains these columns:
 Company: Represents the name of the certified company listed in the database.
 Brand Name: Refers to the specific brand associated with the certified company.
 Country: Indicates the country where the certified company is located or operates from.
 Product Category: Specifies the category of products associated with the certified company.
 Contact Name: Provides the name of the primary contact person within the certified
company.
 Email Address: Includes the email contact associated with the certified company or contact
person.
 Address: Provides address details of the certified company.
 License Number: Represents the unique identification assigned to the certified company.
 PDF: Contains the link or reference to the PDF document associated with the certified
company or its certification details.
 Certification Body: Refers to the organization or entity responsible for issuing the
certification to the company.
 Expiry Date: Specifies the date when the certification linked to the company is set to expire.
 Product Details: Includes specific details related to the products offered by the certified
company.
