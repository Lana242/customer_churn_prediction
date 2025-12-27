# customer_churn_prediction
"Customer churn is the number of existing customers lost, for any reason at all, over a given period of time.
It provides companies with an understanding of customer satisfaction and customer loyalty,
and can identify potential changes in a company’s bottom line."
~IBM

so as you see in the definition of the IBM about customer churn you kinda understand what it is, but let me make it even more simple for you.

let's assume you have a comapny, and you have a customer who uses your product and after a whils they stop buying from you, and you may start counting
how much you gonna lose if this customer stops buying from you. ok ladies and gentlmen this is called customer's churn.

so as a comapy to prevent that from happening, a good way to help is by customer churn prediction, which helps you to guess if the customer is 
about to leave, if so you could try to prevent it.
so here for writing a customer churn prediction we will start from our data.

we first organize and clean our data, after we are done with our data we will be using different models and see how it performs
then by evaluating all the models using Recall, F1-score, precion, accuracy we will choose the best model. so basically it will look like this

Data cleaning ---> building models ---> evaluating our models ---> choosing the best model.




<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/b8a816a3-bdb6-46dc-ba09-fe14883d543b" />


<img width="580" height="455" alt="image" src="https://github.com/user-attachments/assets/13399a5b-8498-486e-ad56-c7002613eb5c" />


<img width="1392" height="951" alt="image" src="https://github.com/user-attachments/assets/6736d2ab-ed56-4954-80af-cb3c63a1a10d" />

	<img width="1280" height="458" alt="image" src="https://github.com/user-attachments/assets/4ac48e3c-28a7-4097-8129-ef0e47e456f1" />


so as you can in this case our best model is Logistic Regression

	<img width="1280" height="994" alt="image" src="https://github.com/user-attachments/assets/fb95137d-af78-4904-8233-1649ee4440cd" />


accuracy	0.793177
precision	0.674627
recall	0.553922
f1_score	0.608345


