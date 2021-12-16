# **MATH2020 - Discrete Mathematics - Mini Project**
##### **Project title**: A lyric-based genre classification – A Naïve Bayes approach from naïve students.
##### **Team**: Grindset
##### **Members**
- Nguyễn Đại Nghĩa - 20nghia.nd@vinuni.edu.vn
- Bùi Đức Khánh An – 20an.bdk@vinuni.edu.vn
- Khau Liên Kiệt – 20kiet.kl@vinuni.edu.vn
- Vương Đỗ Tuấn Thành – 20thanh.vdt@vinuni.edu.vn

---
The key concept of the project is to implement Naïve Bayes’ Theorem for classifying song into the genres through the lyrics. The work procedure divides into three steps: 
- Handling raw data
- Featurizing
- Implementing Naïve Bayes’ Theorem

In terms of raw data handling, the dataset is obtained from [Tmthyjames](https://github.com/tmthyjames/cypher), which contains the song name, the lyrics, the year published, the artist, the genre, etc. The dataset will be pre-processed and featurized into planned datatypes for later uses. Regarding the featurizing, its main function is to calculate the frequency of words in each genre to calculate the likelihood. The third procedure is to apply the Naïve Bayes’ Theorem that gives prediction to the song which likelihood of the genre to be fallen into.
