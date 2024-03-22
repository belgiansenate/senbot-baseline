# SenBot Baseline 🤖

The Belgian Senate is an important institution that generates a large quantity of official documents every year, such as laws, ordinances, declarations and reports. These documents contain valuable and often complex information that can be difficult for citizens to understand. This is where a specialized ChatBot can play an important role. Using the latest natural language processing technologies, this ChatBot aims to understand the questions asked by users and provide precise, clear answers based on the documents generated by the Belgian Senate.


# Approach

We decided to use an approach based on a Retrieval Augmented Generation (RAG) architecture which consists on having a datastore to store our relavant passages as embeddings, a retriever which consists on given a question as an input, it retrieves the most likely relevant passages from the datastore and finally we have a generator which takes a question and relevant passages as input and generate an answer in the output. The next figure shows how this can be designed.

![1695787886133](https://github.com/belgiansenate/senbot-baseline/assets/56476929/862d87fa-e806-41cd-bca0-3b8e6012b8a5)

(source: [https://www.linkedin.com/pulse/what-retrieval-augmented-generation-grow-right/](https://www.linkedin.com/pulse/what-retrieval-augmented-generation-grow-right/) )
