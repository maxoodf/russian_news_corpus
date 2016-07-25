##Russian mass media normalised texts corpus

Russian mass media (27 top on-line sources) articles collection for the period of 01.04.2016 - 25.07.2016.
Texts are normalised and separated by '\n' dilimeter.

* Size:           ~ 1.5 GB
* Articles:       ~ 505 000
* Words:          123 093 058
* Vocabrary size: 513 375 (144 784 with freguency > 5)

The corpus could be usefull in NLP projects, [word2vec](https://github.com/maxoodf/word2vec) models training and other ML algorithms developing.

####HOWTO
The file is compressed by bzip2 utility and splitted to 49M parts. You need to do the following to get the corpus in txt format:
```bash
git clone https://github.com/maxoodf/russian_news_corpus.git
cd ./russian_news_corpus
cat ./russian_news.txt.bz2_a* | bzip2 -d > ./russian_news.txt
```

##Корпус нормализованных текстов российских СМИ

Корпус нормализованных текстов российских СМИ (27 ведущих он-лайн порталов) за период 01.04.2016 - 25.07.2016.
Все тексты нормализованы и разделены символом '\n'.

* Размер корпуса: ~ 1.5 GB
* Статей:         ~ 505 000
* Слов:           123 093 058
* Размер словаря: 513 375 (144 784 встречающихся более 5 раз)

Назначение данного корпуса - исследования, связанные с машинной обработкой текстов, создание [word2vec](https://github.com/maxoodf/word2vec) моделей, алгоритмов машинного обучения и т.д.

####Как загрузить корпус
Файл с содержимым корпуса сжат и разбит на части по 49М. Необходимо выполнить следующие команды для получения исходного файла в текстовом формате:
```bash
git clone https://github.com/maxoodf/russian_news_corpus.git
cd ./russian_news_corpus
cat ./russian_news.txt.bz2_a* | bzip2 -d > ./russian_news.txt
```
