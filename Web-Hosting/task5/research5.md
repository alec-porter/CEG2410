<h1>Alec Porter Task 5</h1>

Sites to confirm if domain is available:<br>
https://www.name.com/<br>
https://www.register.com/<br>

The name of my business is Building Better Cookies so I looked at the following domain name options:<br>
buildingbettercookies<br>
bettercookies<br>

buildingbettercookies.com and bettercookies.com are both available.<br>
bettercookies.com is considered a premium domain name with an initial cost of $4700 to $5400 depending on the site you purchase it from. bildingbettercookies.com is not considered a premium domain name so there is no initial cost to purchase it. Given this is a small start up business and the there is a domain name available that matches the business name, I would go with buildingbettercookies.com.<br>
The cost for the bettercookies.com domain for 5 years is $85 to $90.  That cost does not include any security, SSL certificates, etc.  All those items can be bought at additional monthly or annual costs.

To point my domain name to the dedicated server's IP address I need to create an A record with the company I'm leasing that domain name from.  The company name.com has a guide: https://www.name.com/support/articles/115004893508-adding-an-a-record.<br>

The business model will dictate the type of certificate.  If the web page hosts information on the company but dosn't need to handle sensative data (i.e. credit cards) then an DV or OV SSL certificate will suffice. If the company wants to sell cookies and requires processing of sensative data (credit cards, address, etc.) then I would select a EV SSL certificate.<br>

There are a lot of opinions on certificate authorities on the internet. Let's Encrypt was often mentioned if you don't need an OV or EV because it's a free and run by a non-profit. I checked several small businesses around me and most of them that had simple website that presented information on the business used Let's Encrypt.  If Building Better Cookies only wants a page with business hours, location, menu options, etc. then I would go with Let's Encrypt.  If they want to take orders and process sensitive information (credit cards, addresses, ect.) then I would go with an EV certificate. I narrowed down the EV certificate options to Comodo and Sectigo.  Both offer a single domain EV SSL certificate for 5 years for $700.  I saw enough mention of businesses using them in forums to see them as viable options.  The larger and more recognized certificate authorities like DigiCert or Symantec were $600+ per year.

Assuming I go with Comodo to purchase an EV certificate, their web site lists the process a receive and validate the certificate:<br>
https://help.comodosslstore.com/support/solutions/articles/22000218717-extended-validation-ev-<br>
Step 1 - Fill out the Enrollment Form and return it to the CA.<br>
Step 2 - The CA verifies that the company is a legitimate legal entity that is registered and active in the local municipality. Business registration documents are one option to fulfill this requirement.<br>
Step 3 - Provide operational existence.  The requirements for this vary depending on how long the business has been operating.  If the business has been operating for less than 3 years then a bank confirmation letter fulfills this requirement.<br>
Step 4 - Verify physical address.<br>
Step 5 - Verify business telephone number.<br>
Step 6 - CA confirms that your company legally owns the domain that was submitted with the order.<br>
Step 7 - The CA must speak with the business using the verified business telephone number in order to confirm the details of the order.<br>
<br>
Per Comodo, the entire EV SSL process takes between one business day and 5 business days.  This assumes all the documents are in order and ready.<br>




