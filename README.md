# MO_dvfu_2022

Здесь будут выкладываться материалы семинаров по курсу "Машинное обучение" в ДВФУ. 

- Полезные ссылки
  - [Anaconda](https://www.anaconda.com/products/individual)
  - [Stackoverflow](https://stackoverflow.com)
  - [Google Colab](https://colab.research.google.com/)

- Консультации
  - По Git и GitHub: [задание](https://github.com/V-Marco/hse_iad4_2022/blob/main/misc/git_cons.pdf), [видео](https://youtu.be/Cvd8tdK8CVo)

- Семинар 1: Немного про Jupyter notebook и numpy
  - [Кодспект **(UPD: решения)**](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_1/solved_sem01_numpy.ipynb)
  - [Видео](https://youtu.be/DHYaR0OXLzk)
  - [Хороший пост про np.random.seed()](https://stackoverflow.com/questions/21494489/what-does-numpy-random-seed0-do)
  - [Классный текст про генераторы случайных чисел](https://onlinelibrary.wiley.com/doi/pdf/10.1002/9783527683147.app1)
  - [Markdown Cheatsheet](https://www.markdownguide.org/basic-syntax#overview)
  - [Про LaTex из Википедии](https://en.wikipedia.org/wiki/LaTeX), есть хорошие курсы на Курсере

- Семинар 2: Pandas & Matplotlib
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_2/solved_sem01_pandas.ipynb)
  - [Видео](https://youtu.be/kLRmQjrzd7A)
  - [Разница между функциями `map`, `apply`, `applymap`](https://stackoverflow.com/questions/19798153/difference-between-map-applymap-and-apply-methods-in-pandas)
  - [Примеры индексации в Pandas](https://github.com/V-Marco/hse_iad5_2021/blob/main/misc/pandas_indexing_examples.ipynb)
  - [Здоровское пояснение про bitwise operators в Pandas](https://towardsdatascience.com/bitwise-operators-and-chaining-comparisons-in-pandas-d3a559487525)

- Семинар 3: EDA & sklearn
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_3/solved_sem03_eda_sklearn.ipynb)
  - [Видео](https://youtu.be/8A3MeZzkBmE)
  - [Классная статья по разным видам корреляций](https://medium.com/@outside2SDs/an-overview-of-correlation-measures-between-categorical-and-continuous-variables-4c7f85610365)
  - Некоторые коэффициенты, отражающие ассоциацию между категориальными переменными:
    - Две категориальные ранговые переменные: [корреляция Спирмена (можно использовать и для непрерывных переменных)](https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient), [тау Кендалла](https://en.wikipedia.org/wiki/Kendall_rank_correlation_coefficient)
    - Две категориальные номинальные переменные: [коэффициент Крамера (V или Phi, одно и то же)](http://mlwiki.org/index.php/Cramer%27s_Coefficient), основанный на [хи-квадрат критерии согласия (раздел Testing for statistical independence, показывает независимость)](https://en.wikipedia.org/wiki/Pearson%27s_chi-squared_test)
    - Категориальная и непрерывная: [p-value в F-тесте на сравнение средних](http://mlwiki.org/index.php/One-Way_ANOVA_F-Test)

- Семинар 4: Градиентный спуск
  - [Конспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_4/sem04_grad.pdf)
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_4/solved_sem04_grad.ipynb)
  - [Видео](https://youtu.be/gy1LE8n6m_c)
  - [О сходимости градиентного спуска на практике](https://datascience.stackexchange.com/questions/24534/does-gradient-descent-always-converge-to-an-optimum)

- Семинар 5: Логистическая регрессия и SVM
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_5/solved_sem05_logit_svm.ipynb)
  - [Видео](https://youtu.be/Df-maYyFe9A)
  - [Про AUC ROC](https://dyakonov.org/2017/07/28/auc-roc-площадь-под-кривой-ошибок/)

- Семинар 6: Обработка текстов
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_6/solved_sem06_texts.ipynb)
  - [Видео](https://youtu.be/Df-maYyFe9A)

- Семинар 7: Решающие деревья
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_7/solved_sem07_trees.ipynb)
  - [Конспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_7/sem07_notes.pdf)
  - [Решение бонуса](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_7/bonus_sem07_trees.ipynb)
  - [Видео](https://youtu.be/gBFXVjp1u54)

- Семинар 8: Случайный лес
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_8/solved_sem08_rf.ipynb)
  - [Конспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_7/sem07_notes.pdf)
  - [Видео](https://youtu.be/gBFXVjp1u54)

- Семинар 9: Градиентный бустинг
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_9/solved_sem09_boostings_part1.ipynb)
  - [Имплементации бустинга](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_9/sem09_boostings_part2.ipynb)
  - [Видео](https://youtu.be/e41RW-FXITc)

- Семинар 10: Кластеризация
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_10/solved_sem10_clustering.ipynb)
  - [Видео](https://youtu.be/e41RW-FXITc)
