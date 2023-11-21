# IntellectPath

The above project IntellectPath which is recommender system based on OpenAI's LLM supporting features such as "OpenAIEmbeddings" and "Transformer (GPT-3)" model.

The main objective of the project is to help the college students who are in the dilemma of choosing the domain and those who wanted have a strong foundation in their domain. It works in a way of testing the user with their prior knowledege on a particular domain. The workflow of the project moves from the starting point of collecting the user's perspectives on different domains collectively based on MCQs asked to them, then the major domain and substream of that particular domain has been given to the user, after this user is directed to the next page with genarated questions based on the "Transformer" model. The user has to give their text responses for the questions asked. The OpenAIEmbedding model works to give the vector embeddings for the user's responses. The dataset has been extracted from Kaggles's "edx_course.csv" and "coursera.csv".

 The data is preprocessed and clustered based on domains. The course descriptions are concatenated and summarised. The description is preprocessed and it is vectorised using OpenAIEmbedding. In the array of entirely vectors ,the description which is nearer to (based on the distance) has been considered and suggested to the user as the most preferred course. 
