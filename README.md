
# CompanyInfo-Chatbot
A basic DNN based Chatbot that  provide essential information about the company, such as its name, mission, products or services, contact details, and any other relevant information. 

Model was built using tensorflow newural network with 3 layers ( 2 (10 neuron layers) + 1softmax layer) .
Model was trained using the intents(with around 7 classes) file on which I tried to apply tokenisation and stemming techinques for creating the training data.

To preprocess user queries , this notebook contains 4 fuctions namely-clean_up_sentence(for token creating ),bow(for bagging similar words),classify(to categorize the query) and response(final bot's response).Use of which is demonstrated at the end of this notebook.

Taking the project further , I created a flask web application with some basic html and css(see images) that acts as an interface for user to use the chatbot. 




Here's a demonstation of Chatbot on local host!





https://github.com/abhayshanbhag2003/CompanyInfo-Chatbot/assets/100664539/55413df0-d240-42c1-8470-db765adfc7ca




![ChatBot demonstration](https://github.com/abhayshanbhag2003/CompanyInfo-Chatbot/assets/100664539/68ac8f1d-f99c-434e-97b9-88d4c99706ff)
