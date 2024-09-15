### TR:

Metin Temizleme ve Tamamlama Sistemi  
Bu proje, verilen bir metin içinde hakaret ve argo içeren kelimeleri algılayıp siler ve ardından metnin devamını oluşturmak için bir model kullanır. Doğal dil işleme teknikleriyle metindeki uygunsuz ifadeleri temizleyerek mantıklı ve akıcı bir metin oluşturmaya devam eder.  
**Kullanılan Teknolojiler:**
- TensorFlow  
- LSTM (Long Short-Term Memory)  
- NLTK (Natural Language Toolkit)

Projede, hakaret içeren kelimeleri bulmak için bir model eğitilmiş ve daha sonra farklı bir fake_or_real_news veri seti ile metin tamamlama modeli eğitilmiştir. Hakaret içeren kelimeler tespit edilip silinir ve metin mantıklı bir şekilde devam ettirilir.

---

### EN:

Text Cleaning and Completion System  
This project detects and removes offensive and slang words from a given text and then uses a model to continue the text. It applies natural language processing techniques to clean the text of inappropriate expressions and generate a coherent and fluent continuation.  
**Technologies Used:**
- TensorFlow  
- LSTM (Long Short-Term Memory)  
- NLTK (Natural Language Toolkit)

A model was trained to detect offensive words, and a text completion model was trained using a different dataset, the fake_or_real_news dataset. Offensive words are identified and removed from the text, and the text is logically continued.
