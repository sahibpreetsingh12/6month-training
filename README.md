# 6month-training
This Repo Contains all the Projects I did in My Last Semester

# 1. NETFLIX CONSUMPTION ANALYSIS 
present [HERE](https://www.kaggle.com/sahib12/netflix-analysis)


![here](netflix1.gif)

This Notebook contains various Insights and Interesting Patterns of Binge watching that people have adopted
Since 2008 That Includes:-
- [x] Penetration Of <font color="red">**Netflix**</font> in Globally from 2008.
- [x] Preferrable Movie Duration of People In Different countries.
- [x] Countries for which <font color="red">**NETFLIX**</font> makes **most** of the content.

.... and other very interesting insights.


# 2. Custom Document Embeddings Techniques.

So this project was personally my favorite instead of using **DOC2VEC** from **GENSIM** One day I thought of Creating my own 
**DOCUMENT EMBEDDINGS**.

Implemented [here](https://www.kaggle.com/sahib12/document-embedding-techniques)

In this project I Tried to Use **TFIDF**(i.e Term Frequency and Inverse Document Frequency) and
**Word2vec** from **Google** I didn't Trained **Word2vec** on my Training Data(Just wanted to See the Results).

These Techniques were :-

## Technique1 :-
I tried to try to use word2vec for each word embeddings in a sentences and then sum those embedding to get document embedding for that document.

![here](https://lh3.googleusercontent.com/Zc4lDvcto_IHdNYNOaKA5qCaNvQsd6dxuopNvK05K6T6GkGCOA7ErYaxG3GvxuMDBqR-QcvSiEOii5dx4lPCxTIR58g2sDzarwFQUggA8vOROykJqbN4YMyoZu4ySM_Nch4BRrBjawXKzEG0GWHeZMScAEMPnaWmLFYoSlpRDGN26_gwN4rSOEZaNmMCb4YFfwLYaHdiDWTY0IisqSgE_37DIusi8xxE0hXUAdIYmjaQdVscVIWeJlYQf7iQD9eZHzFOHpfq79cBN8k0g-ZE8CxadEysr_HdV3_q6vyqBmUZ4NYi9QYy60wwN27FlKB3au-j-RNdUW_RxXeABXm0fE88_rxl3Zj4-FdCwRaLuXNbh5hhn85DqndwqSGVt09WMQhpudjw3O2yWWpt5hGYNFHHLvhuXNyML4uDMbqpUXM-gGuQQmtJsN0cAaxHeb5ZC-V1WZNDgIpPrybAHYxNkHRwnp5r0sNwBYpd2G5kxbudbX97rUBdgnKA9bYnHR2ZNtPo0s-2JH_II8XvCvzwWN6KFw1eZogTTVJwGpLd3gwXmQLILH6FBTIoFxfXJUlna2iNJt7pkSbO3YOuf_HBN10zmew8pP8Jc3G4_S7HqoGWbmDa4vLxZpnkwtVB_EHtRBqMqGFKHl5W5jOERTR3dsbuL4RycQrJDF19d5ENZS0-1W4udjlwPpknMA1lEjg=w682-h908-no)

## Technique 2
I used TfIdf for finding weight of each word in a document and then multiplied it to word vector created by word2vec for that word
And finally summed all word vectors to get document embedding for that document.

![here](https://lh3.googleusercontent.com/95qatVb0QyAX1Az379DXBtriuNL1aJI8kOz4WFVjIqK4uSemZ-7gCrQxOBmMT4CKmNKWSnbNx_sFuH4ksq1KG7DCCXwpAQB8XgRmrqjqyffL__7xes1ZnUUXwUPcxzmP5_d9PnLRSu7skqbtX-ic5GWPnxGsFI_fFte5g4C4drXel0821NTMQKnHDnSSlql4JFZwhdv7keB89wKR727-nmxZBCySn0P5PMks0XFB_Lr7m4DqwGz6v1O7Y6ndC5HzJvWJH_-4etQkxm84LP5vQK8M6UEGf49T8DC5-iXZ-XaT9-W5qn0j3AbgXvADBfcSSNplcYILm4j0AsKQVIkkfcYSM11usLMbUhW_2poYgRdHl3NILgNIzAKEzPTzYx2-M_dZPyeQj6XL0BY4JRD_gdMNj5F01kKK67Eumj7HTQ2_GVNudI3z7X-MY28ahfVIJ2Z7MwVphC4aGdkyYzv8D8W90IVLFa2G3MYVpRyRcpcb3eZtVjfcJLLKhwZXzZfryuVq4-eVAb-HpiaQJQ2DdVuTx400WewhMZeiKHrHCld-6fVtgbN8_9xfctTDlfqVgyurDukpNBUdTwsEXT0vEUXSRsP2POrs6l1s1eql8LL8wI1RC5Hz5sD4UoWX2O4JllYTPAfSB9Kok504C_354Ybm1AdtPgZ74QAIuuSfCWXkrVXquip7MYW0UTBWJX8=w682-h908-no)



### Surprisingly These Techniques Got me in Top 30 % of this [Competition](https://www.kaggle.com/c/nlp-getting-started)




![here](https://cdn.memegenerator.es/imagenes/memes/full/3/25/3254012.jpg)
