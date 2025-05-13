# Max Life Insurance Cross Sell Prediction — Vehicle Insurance


## **Project Summary**

Insurance companies provides vehicle insurance to its customers just like other insurance, medical insurance, life insurance, etc.

An insurance policy is an arrangement by which company undertakes provider guarantee of compensation for specific loss, damage, illness or death in return for the payment of specified premium. Customers need to pay regularly to an insurance company for this guarantee. The amount of money provided by company depends upon the policy agreement.


In vehicle insurance customer needs to pay a premium of certain amount every year to the insurance provider company so that in case of an unfortunate accident happens the vehicle insurance will cover financial loss as the insurance company will provide compensation to the customer.
So the objective is to build a model which can predict that the customer would be interested in buying vehicle insurance. So they can reach the customers in advance and optimise its business model and revenue.


In order to predict the customer would be interested in vehicle insurance we have a dataset of certain demographics which contains gender, age, region code, vehicle age, damages, previous insurance, policy, etc.


## A small insights from the problem statement and data description

### Insurance firm?

* An insurance firm is a company that provides financial protection or reimbursement against losses or damages, typically in exchange for payment of a premium.

### Probability of buying an insurance?

* The probability of buying insurance depends on various factors including individual risk perception, financial situation, and the perceived value of the insurance coverage. It varies from person to person and is influenced by factors such as age, health, lifestyle, and the specific type of insurance being considered.

### Insurance firm can protect its customers?

* An insurance firm can protect its customers by providing various types of insurance coverage tailored to their needs, offering financial reimbursement or assistance in case of covered losses or damages. Additionally, they can provide excellent customer service, transparent policies, and prompt claims processing to ensure customer satisfaction and peace of mind.

### Importance of insurance and how it is helpful?

* Lets say about four in 10 men describe themselves as being very knowledgeable about life insurance.  As in the problem statement, about 2 or 3 get hospitalized out of 100, which means 2 to 3 percent claim the insurance. This way everyone shares the risk of everyone else.


So we need to building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue. Now, we need to predict whether the customer would be interested in Vehicle insurance or not.


## **Dataset description**

* ***id:*** Unique ID for  customer.
* ***Age:*** Age of the customer.
* ***Driving_License:*** Customer has DL or not.
* ***Region_Code:*** Unique code for the region of the customer.
* ***Previously_Insured:*** Customer already has Vehicle Insurance or not.
* ***Vehicle_Age:*** Age of the Vehicle.
* ***Vehicle_Damage:*** Past damages present or not.
* ***Annual_Premium:*** The amount customer needs to pay as premium.
* ***PolicySalesChannel:*** Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.
* ***Vintage:*** Number of Days, Customer has been associated with the company.
* ***Response:*** Customer is interested or not.
