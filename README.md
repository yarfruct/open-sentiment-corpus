# OpenSentimentCorpus

This repository contains OpenSentimentCorpus, a sentence-level sentiment dataset for Russian.

OpenSentimentCorpus is a derivative of [OpenCorpora](http://opencorpora.org/), an open corpus of Russian texts.

## Markup

1. All the sentences shorter than 7 words were exlcuded.
2. Each sentence was marked as _positive_, _negative_, _neutral_, _mixed_, or _doubtful_ by at least three evaluators according to the sentence author's attitude to the topic of the sentence. The  _mixed_ mark indicates that the author expresses both positive and negative attitude in the sentence, and the _doubtful_ mark indicates that the sentence has questionable sentiment, unclear author's position, or any other reason of the evaluator's uncertainty.
3. All the sentences that had at least one _doubtful_, or both _positive_ and _negative_ marks were excluded.
4. Two approaches to the calculation of the final sentiments were utilized.
	* According to the first approach, the final sentiment of each sentence was calculated according to the majority of marks. If there was no such a majority, the sentence was excluded.
	* According to the second approach, the final sentiment was assigned according to the result of agreement between all the evaluators. If there was no such an agreement, the sentence was excluded.


## Content
There are three files in the repository:

* `opensentimentcorpus-final-by-majority.csv` contains only final sentiments calculated according to the majorities of the marks;
* `opensentimentcorpus-final-by-total-agreement.csv`;
* `opensentimentcorpus-all-marks.csv` contains all the evaluators' marks.

## Evaluators

* Alexander Skvortsov (Скворцов Александр Константинович)
* Alla Manakhova (Манахова Алла Михайловна)
* Anastasia Baskakova (Баскакова Анастасия Сергеевна)
* Anastasia Chernyshova (Чернышова Анастасия Александровна)
* Anna Moscwina (Москвина Анна Владимировна)
* Anton Kurbatov (Курбатов Антон Игоревич)
* Daniil Vereschagin (Верещагин Даниил Дмитриевич)
* Dmitry Chernyshov (Чернышов Дмитрий Васильевич)
* Dmitry Kononets (Кононец Дмитрий Анатольевич)
* Evgenya Shikova (Шикова Евгения Борисовна)
* Igor Krasavin (Красавин Игорь Сергеевич)
* Ilona Arefyeva (Арефьева Илона Юрьевна)
* Ivan Beliyakov (Беляков Иван Николаевич)
* Maria Leonova (Леонова Мария Алексеевна)
* Sergey Yazynin (Язынин Сергей Германович)
* Veronika Sliskova (Слискова Вероника Валерьевна)
* Vladislav Nepryahin (Непряхин Владислав Вадимович)
* Vladislav Petryakov (Петряков Владислав Леонидович)


## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/3.0/88x31.png" /></a><br/>
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>

