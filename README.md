# Chainbreakers
SAMHAR COVID-19 Hackathon

We are developing an interactive solution to assist health professional to get speedy, accurate and latest insights from huge amount of COVID-19 literatures.

Given the large number of literature and the rapid spread of COVID-19, it is difficult for health professionals to keep up with new information on the virus. There are more than 44000 research articles already published and its growing. This is a very big challenge for a health care professional to get the speedy and accurate information from all the literature available in the world.  

In addition, there is a need for getting the insight quickly, which can accelerate the COVID-19 vaccination research. Our solution to provide speedy, accurate & latest information via a context aware Chat-bot which will do the data mining from given articles based on Abstract, Author, Publication, Vital keywords etc. The heart of the system will be a clustering algorithm, which would do the cluster of 44000 articles based on the key words and other user inputs. User interaction will be through context aware Deep NLP chat-bot, which would provide the generic information about corona/COVID-19 information (preventive measures, helpline, medical facilities etc) and article search for relevant topics. Also chat-bot can auto summarize the articles based on user demand, this will enhance the experience of health professional to get the summary of the literature quickly.
 ![alt text](https://github.com/vinilvadakkepurakkal/chainbreakers/blob/master/pic.jpg?raw=true)
**Approach**:

<<<<<<< HEAD
 
=======
Approach for the chatbot: 
	
	1. Communication channel 
		- The chatbot can be accessed by the following channels.
			* Web-based ( HTML ,CSS , AJAX Web technologies )
			* Social media ( Telegram )
	2. Display prompt ( Article , General queries ) 
		- Article search 
		- General queries
	3. Ask for query based on action
	4. Display output based on model genereated.
	5. Suggestion chips generated for the next cycle.

Approach for the Natural Language Processing -ML Algorithm: 

	1: User can specify the keyword on which he/she needs to know infotmation on.
	2: The huge database of publications, journals, books are then searched for 
					this relevant content using spaCy-NLP method.
	3:The data search can be of a) General information
				    b) drug related information
	4: The data is then clustered using clustering algorithms to send it back to the user.
	5: The user receives a message with relevant journals/publication information sorted on their weights.
	
