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

[1_1_Text_Summarization_SpaCy_pytextrank.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/1_1_Text_Summarization_SpaCy_pytextrank.ipynb)

[1_2_Text_Summarization_gensim.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/1_2_Text_Summarization_gensim.ipynb)


### 2_Text Summarizaton Using Tf Idf

https://youtu.be/LYnyekMKR5g

[2_0_Text Summarizaton_Tf-Idf.ipynb](https://github.com/ciepielajan/NLP_Text-Summarization/blob/main/2_0_Text_Summarizaton_Tf_Idf.ipynb)

### 3_Text Summarizaton_Word_Frequency

zawiera też Tf-IDF oraz Streamlit App https://towardsdatascience.com/text-summarization-using-tf-idf-e64a0644ace3  

Można porównać z modelem nr2(wcześniejszym)

__Term Frequency__
__Term frequency (TF)__ is how often a word appears in a document, divided by how many words there are.

TF(t) = (Number of times term t appears in a document) / (Total number of terms in the document)

__Inverse document frequency__
Term frequency is how common a word is, inverse document frequency (IDF) is how unique or rare a word is.

IDF(t) = log_e(Total number of documents / Number of documents with term t in it)

__Example,__ Consider a document containing 100 words wherein the word apple appears 5 times. The term frequency (i.e., TF) for apple is then (5 / 100) = 0.05.

Now, assume we have 10 million documents and the word apple appears in one thousand of these. Then, the inverse document frequency (i.e., IDF) is calculated as log(10,000,000 / 1,000) = 4.
Thus, the TF-IDF weight is the product of these quantities: 0.05 * 4 = 0.20.


