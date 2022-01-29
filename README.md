# **MATH2020 - Discrete Mathematics - Mini Project**
##### **Project title**: A lyric-based genre classification – A Naïve Bayes approach from naïve students.
##### **Team**: Grindset
##### **Members**
- Nguyễn Đại Nghĩa
- Bùi Đức Khánh An
- Khau Liên Kiệt
- Vương Đỗ Tuấn Thành

---
The key concept of the project is to implement Naïve Bayes’ Theorem for classifying song into the genres through the lyrics. The work procedure divides into three steps: 
- Handling raw data
- Featurizing
- Implementing Naïve Bayes’ Theorem

In terms of raw data handling, the dataset is obtained from [Tmthyjames](https://github.com/tmthyjames/cypher), which contains the song name, the lyrics, the year published, the artist, the genre, etc. The dataset will be pre-processed and featurized into planned datatypes for later uses. Regarding the featurizing, its main function is to calculate the frequency of words in each genre to calculate the likelihood. The third procedure is to apply the Naïve Bayes’ Theorem that gives prediction to the song which likelihood of the genre to be fallen into.
