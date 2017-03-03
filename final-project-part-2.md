# CFPB And Income

### Project Problem and Hypothesis
The Consumer Finance Protection Bureau (CFPB) provides a database of all complaints. This includes the product, the complaint reason, the company, location, company response, etc. This rich data set is used by the CFPB to identify companies and products to investigate, clarify regulations, create new regulatory rules, and levy fines for egregious behavior. I am interested in what demographic factors go into a complaint and its resolution. My hypothesis is that lower income groups are underrepresented in the database, and to the extent that they are represented in the database, have worse outcomes (i.e., more untimely responses, more disputed responses, lower rates of compensation from the companies represented in the database, etc). 

### Datasets
* Consumer Finance Protection Bureau Complaint Database (https://cfpb.github.io/api/ccdb/fields.html)
* American Community Survey 2015 Economic Characteristics (https://factfinder.census.gov/faces/tableservices/jsf/pages/productview.xhtml?pid=ACS_15_5YR_DP03&src=pt)

From the ACS I plan on using only a few things, like income--possibly joining up

### Domain knowledge
* My employer's core business is in consumer finance regulations. We also have
* Does it relate or help inform the project in any way?

* What other research efforts exist?
    * My employer has published reports on the CFPB (prior to my being employed there).
    * The CFPB also publishes research (https://www.consumerfinance.gov/data-research/research-reports/).
    * Deliotte has a report (https://www2.deloitte.com/content/dam/Deloitte/se/Documents/financial-services/CFPBConsumerComplaintDatabase091913US_FSI_.pdf)

### Project Concerns
* I'm not sure whether the data is comprehensive enough to support the hypothesis--that is, since I'm aiming to show that lower income groups are underrepresented, I need to assume that they have at minimum the same complaint rate as other groups, but the most complained about product is mortgages, which not all communities have equal access to, so a lower complaint rate in low income communities isn't necessarily indicative of their being underrepresented in the database--they would simply have fewer complaints per capita.
* The data set is only those who complained to the CFPB, not all those who had problems. How does the CFPB market itself? How do consumers discover that the CFPB will listen to their complaints?
* What are the risks to the project?
    * Potential Costs: If the model is incorrect, we're going to either be missing existing bias or discovering nonexistent bias, but if it is correct, we'll have learned something important about how companies deal with complaints and provide actionable information to improve their processes.
    * The CFPB doesn't vet the accuracy of the complaints, just that there is a real business relationship. The company response data is likely to be accurate, but consumer provided values could be very inaccurate (the consumer may misunderstand the nature of the product or complaint they want to make and so the database would reflect that even if the company's resolution doesn't).

### Outcomes
* I would aim to build a classifier (or a set of classifiers) that could help predict whether an outcome is to the consumer's benefit, and a classifier to help predict whether the consumer disputes the outcome.
* Users should have, eventually, the ability to construct their own hypothetical complaints and use the predictor--along with an analysis of the most important features (probably including some sort of choropleth and some other accompanying visualizations to help decision-makers understand the data).
* I expect per capita income to be a very large determiner of outcome.
* A successful model will give us information about how complaints vary across income groups--that is, we'll be able to discern how different income groups complaints are structured and how they are handled.
