## ML4ES, Лекция 7

#### Неопределенность в задачах машинного обучения. Оценка неопределенностей методом Bootstrap.



Лекция посвящена понятию неопределенностей, возникающих при решении задач машинного обучения. Рассматривается на примере задач класса "Обучение с учителем", на примере модели линейной регрессии.



Заметки к лекции доступны в [PDF](https://github.com/MKrinitskiy/ML4ES1-F2021-S2022/blob/main/Lect07/Lect07.pdf)

Рамочный ноутбук, в котором представлены технические детали применения Bootstrap для оценки неопределенности параметров, меры качества и оценок целевой переменной доступен по [ссылке](https://github.com/MKrinitskiy/ML4ES1-F2021-S2022/blob/main/Lect07/LR_problem-uncertainties-Bootstrap.ipynb).



В качестве материалов на дополнительное чтение можно обратить внимание на следующие источники:

Статья, считающаяся оригинальным описанием Bootstrap: [Efron, B. (1979). Bootstrap Methods: Another Look at the Jackknife. *The Annals of Statistics*, *7*(1), 1–26](https://www.jstor.org/stable/2958830)

Раздел 7.1 "Bootstrap methods" книги [Hastie T., Tibshirani R., Friedman J. The Elements of Statistical Learning: Data Mining, Inference, and Prediction, Second Edition / New York: Springer-Verlag, 2009.](https://web.stanford.edu/~hastie/ElemStatLearn/)

Статьи с описанием метода Bootstrap и исследованием его точности в оценке различных статистик:

[Efron B., Tibshirani R. The Bootstrap Method for Assessing Statistical Accuracy // Behaviormetrika. 1985. № 17 (12). C. 1–35.](https://link.springer.com/article/10.2333/bhmk.12.17_1) 

[Efron B., Tibshirani R. Bootstrap Methods for Standard Errors, Confidence Intervals, and Other Measures of Statistical Accuracy // Statistical Science. 1986. № 1 (1). C. 54–75.](https://projecteuclid.org/journals/statistical-science/volume-1/issue-1/Bootstrap-Methods-for-Standard-Errors-Confidence-Intervals-and-Other-Measures/10.1214/ss/1177013815.full)

[Singh K. On the Asymptotic Accuracy of Efron’s Bootstrap // The Annals of Statistics. 1981. № 6 (9). C. 1187–1195.](https://www.jstor.org/stable/2240409)



Книга с подробным описанием метода и его свойств [Tibshirani R. J., Efron B. An introduction to the bootstrap // Monographs on statistics and applied probability. 1993. (57). C. 1–436.](https://www.amazon.com/Introduction-Bootstrap-Monographs-Statistics-Probability/dp/0412042312); Часть книги в [PDF](http://cindy.informatik.uni-bremen.de/cosy/teaching/CM_2011/Eval3/pe_efron_93.pdf)



[Статья в Wikipedia о методе Bootstrap](https://en.wikipedia.org/wiki/Bootstrapping_(statistics))

[Заметки лекции #5 о методе Bootstrap Yen-Chi Chen](http://faculty.washington.edu/yenchic/17Sp_403/Lec5-bootstrap.pdf) курса [STAT/Q SCI 403](http://faculty.washington.edu/yenchic/17Sp_403/) Вашингтонского Университета (США)

[Заметки лекции #6 Yen-Chi Chen о применении метода Bootstrap в линейных моделях](http://faculty.washington.edu/yenchic/17Sp_403/Lec6-bootstrap_reg.pdf) курса [STAT/Q SCI 403](http://faculty.washington.edu/yenchic/17Sp_403/) Вашингтонского Университета (США)

