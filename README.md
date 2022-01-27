# NLP-SentimentAnalysis-Python

Bu çalışmada, IMDB yorumları veri setine doğal dil işlemenin bir alt kümesi olan duygu analizi yöntemi ile bazı iyi bilinen makine öğrenimi yaklaşımları ve sözlük tabanlı
yaklaşımları karşılaştırmaktır. Denetimli makine öğrenmesi algoritmalarından Random Forest (RF) sınıflandırıcısı, 
Multinominal Navie Bayes (MNB) sınıflandırıcısı, Support Vector Machine (SVM) sınıflandırıcısı ve Logistic Regression (LR) sınıflandırıcısı kullanılmıştır. 
Sözlük tabanlı tekniklerden Valence Aware Dictionary and Sentiment Reasoner (VADER) ve TextBlob kullanılmıştır. 
Stanford IMDB Movie Rewiew veri kümesi üzerinde belirtilen algoritma ve tekniklerin performansını araştırılmıştır.
</br>
</br>
Veri kümesi bu linkten indirilebilir: https://ai.stanford.edu/~amaas/data/sentiment/
</br>
</br>
Makine öğrenme algoritmaları üzerinde aşağıdaki teknikler karşılaştırılmıştır;
<ul>
<li>TF-IDF ve Bags-of-words</li>
<li>Lemmatization ve Stemming</li>
<li>1-gram, 2-gram ve 3-gram</li>
</ul>

</br>

Sözlük tabanlı araçlar üzerinde aşağıdaki teknik karşılaştırılmıştır;
<ul>
<li>Lemmatization, Stemming ve Temel(veri ön işlemesiz)</li>
</ul>
</br>
Support vector machine ve Vader için sonuç aşağıda gösterilmiştir. Diğer sonuçlar için kod dosyalarına bakılabilir.
</br>
</br>

![Screenshot_20220128_035928](https://user-images.githubusercontent.com/57114695/151452437-0217997f-1469-41be-92b2-b4b239eed387.png)
</br>
</br>
![Screenshot_20220128_035953](https://user-images.githubusercontent.com/57114695/151452755-8374a668-61f9-4a3e-9d54-5afccd8efe72.png)
