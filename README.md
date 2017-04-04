## **Russian mass media stemmed texts corpus**
Russian mass media (27 top on-line sources) articles collection for the period of 04.2016 - 03.2017. Articles are stemmed and separated by '\n' char delimiter.  
Also, the original collection (without stemming) can be downloaded [here](https://drive.google.com/file/d/0B1shHLc2QTzzZGJFWTRQUUNrem8/view?usp=sharing).
- Size:            ~ 4.5 GB
- Articles:        ~ 1 500 000
- Words, total:    ~ 360 000 000
- Words, unique:   ~ 5 178 821
- Vocabulary size: 435 114 (word frequency > 10)

The corpus could be useful in NLP projects, [word2vec](https://github.com/maxoodf/word2vec) models training and other ML algorithms developing.

#### HOWTO
The file is compressed by bzip2 utility and split to 49M parts.  
Execute the following commands to get the corpus in txt format:
```bash
git clone https://github.com/maxoodf/russian_news_corpus.git
cd ./russian_news_corpus
cat ./russian_news.txt.bz2_a* | bzip2 -d > ./russian_news.txt
```

## **Корпус лемматизированных текстов российских СМИ**
Коллекция лемматизированных (морфологически нормализованных) текстов российских СМИ (27 ведущих он-лайн порталов) за период 04.2016 - 03.2017. Статьи разделены символом '\n'.  
Коллекция тексов, так же, доступна [без лемматизации](https://drive.google.com/file/d/0B1shHLc2QTzzZGJFWTRQUUNrem8/view?usp=sharing).
- Размер корпуса:   ~ 4.5 GB
- Статей:           ~ 1 500 000
- Слов, всего:      ~ 360 000 000
- Слов, уникальных: ~ 5 178 821
- Размер словаря:   435 114 (частота слова > 10)

Назначение данного корпуса - исследования, связанные с машинной обработкой текстов, создание [word2vec](https://github.com/maxoodf/word2vec) моделей, алгоритмов машинного обучения и т.д.

#### Как загрузить корпус
Файл с содержимым корпуса сжат и разбит на части по 49М. Необходимо выполнить следующие команды для получения исходного файла в текстовом формате:
```bash
git clone https://github.com/maxoodf/russian_news_corpus.git
cd ./russian_news_corpus
cat ./russian_news.txt.bz2_a* | bzip2 -d > ./russian_news.txt
```
