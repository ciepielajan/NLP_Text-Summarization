# Podsumowanie tekstu / summarization text
proces destylacji najważniejszych informacji z tekstu źródłowego.

## Rodzaje 
### Na podstawie typu danych wejściowych
- Podsumowanie pojedynczego dokumentu (__Single-document summarization__) generuje podsumowanie z pojedynczego dokumentu źródłowego.
- Podsumowanie wielu dokumentów(__Multi-document summarization__) to automatyczna procedura mająca na celu wyodrębnienie informacji z wielu tekstów napisanych na ten sam temat.

### Na podstawie typu wyjścia
- Ekstrakcji podsumowania (__Extractive summarization__) polega na wybieraniu ważnych zdań, akapitów itp. Z oryginalnego dokumentu i łączeniu ich w krótszą formę.
- Podsumowanie abstrakcyjne (__Abstractive summarization__) polega na zrozumieniu głównych pojęć zawartych w dokumencie, a następnie wyrażeniu tych pojęć w jasnym języku naturalnym.

### W oparciu o cel
- Podsumowania specyficzne / dziedzinowa (__Domain-specific summarization__) Techniki dla domeny wykorzystują dostępną wiedzę specyficzną dla dziedziny tekstu. Na przykład automatyczne badanie podsumowujące tekstów medycznych na ogół próbuje wykorzystać różne źródła skodyfikowanej wiedzy medycznej i ontologii.
- Podsumowanie oparte na zapytaniach (__Query-based summarization__) czasami nazywane podsumowaniem związanym z zapytaniem, podsumowuje obiekty specyficzne dla zapytania.
- Podsumowanie ogólne (Generic summarization) koncentruje się na uzyskaniu ogólnego podsumowania lub streszczenia zbioru dokumentów lub zestawów obrazów lub filmów, wiadomości itp.

_________________________________

### 1_Text_Summarization_using_spaCy_pytextrank_gensim

https://youtu.be/qtLk2x59Va8

- TextRank
- Page Rank for TextRank

[1_1_Text_Summarization_SpaCy_pytextrank.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/1_1_Text_Summarization_SpaCy_pytextrank.ipynb)  NIE DZIAŁA

[1_2_Text_Summarization_gensim.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/1_2_Text_Summarization_gensim.ipynb)

Result:
>

### 2_Text Summarizaton Using Tf Idf

zawiera też oraz Streamlit App https://towardsdatascience.com/text-summarization-using-tf-idf-e64a0644ace3  

[2_0_Text Summarizaton_Tf-Idf.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/2_0_Text_Summarizaton_Tf_Idf.ipynb)

Result:
>It is seen as a part of artificial intelligence. A core objective of a learner is to generalize from its experience. The bias–variance decomposition is one way to quantify generalization error. There are two kinds of time complexity results. Other methods are based on estimated density and graph connectivity. It is a learning with no external rewards and no external teacher advice. The system is driven by the interaction between cognition and emotion. There is neither a separate reinforcement input nor an advice input from the environment. Classic examples include principal components analysis and cluster analysis. The method is strongly NP-hard and difficult to solve approximately. An artificial neuron that receives a signal can process it and then signal additional artificial neurons connected to it. The weight increases or decreases the strength of the signal at a connection. These decisions rely on objectivity and logical reasoning.

### 2_1Text Summarizaton Using Tf Idf but calculate only for noun and verb 
[2_1_Text Summarizaton_Tf-Idf_only_noun_verb.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/2_1_Text%20Summarizaton_Tf-Idf_only_noun_verb.ipynb)

Result:
>It is seen as a part of artificial intelligence. is replaced with the question "Can machines do what we (as thinking entities) can do? A core objective of a learner is to generalize from its experience. Instead, probabilistic bounds on the performance are quite common. The bias–variance decomposition is one way to quantify generalization error. There are two kinds of time complexity results. It is a learning with no external rewards and no external teacher advice. The system is driven by the interaction between cognition and emotion. There is neither a separate reinforcement input nor an advice input from the environment. The method is strongly NP-hard and difficult to solve approximately. The weight increases or decreases the strength of the signal at a connection. Typically, artificial neurons are aggregated into layers. In decision analysis, a decision tree can be used to visually and explicitly represent decisions and decision making. These decisions rely on objectivity and logical reasoning.

|   id |   ilosc znakow |   ilosc slow |   ilosc zdan |
|-----:|---------------:|-------------:|-------------:|
|  2_1 |           1011 |          157 |           14 |


### 3_Text Summarizaton_Word_Frequency
[3_0_Text_Summarizaton_Word_Frequency.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/3_0_Text_Summarizaton_Word_Frequency.ipynb)

Result:
> In the early days of AI as an academic discipline, some researchers were interested in having machines learn from data. Some statisticians have adopted methods from machine learning, leading to a combined field that they call statistical learning. If the complexity of the model is increased in response, then the training error decreases. The data is known as training data, and consists of a set of training examples. The algorithms, therefore, learn from test data that has not been labeled, classified or categorized. In machine learning, the environment is typically represented as a Markov decision process (MDP). In supervised feature learning, features are learned using labeled input data. It is one of the predictive modeling approaches used in statistics, data mining, and machine learning. In machine learning, genetic algorithms were used in the 1980s and 1990s. Usually, machine learning models require a lot of data in order for them to perform well.






