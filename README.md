# MO_dvfu_2022

Здесь будут выкладываться материалы семинаров по курсу "Машинное обучение" в ДВФУ. 

- Полезные ссылки
  - [Anaconda](https://www.anaconda.com/products/individual)
  - [Stackoverflow](https://stackoverflow.com)
  - [Google Colab](https://colab.research.google.com/)

- Консультации
  - По Git и GitHub: [задание](https://github.com/V-Marco/hse_iad4_2022/blob/main/misc/git_cons.pdf), [видео](https://youtu.be/Cvd8tdK8CVo)

- Семинар 1: Немного про Jupyter notebook и numpy
  - [Кодспект](https://github.com/V-Marco/MO_dvfu_2022/blob/main/seminar_1/solved_sem01_numpy.ipynb)
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
  - [Видео]
  - [Классная статья по разным видам корреляций](https://medium.com/@outside2SDs/an-overview-of-correlation-measures-between-categorical-and-continuous-variables-4c7f85610365)
  - Некоторые коэффициенты, отражающие ассоциацию между категориальными переменными:
    - Две категориальные ранговые переменные: [корреляция Спирмена (можно использовать и для непрерывных переменных)](https://en.wikipedia.org/wiki/Spearman%27s_rank_correlation_coefficient), [тау Кендалла](https://en.wikipedia.org/wiki/Kendall_rank_correlation_coefficient)
    - Две категориальные номинальные переменные: [коэффициент Крамера (V или Phi, одно и то же)](http://mlwiki.org/index.php/Cramer%27s_Coefficient), основанный на [хи-квадрат критерии согласия (раздел Testing for statistical independence, показывает независимость)](https://en.wikipedia.org/wiki/Pearson%27s_chi-squared_test)
    - Категориальная и непрерывная: [p-value в F-тесте на сравнение средних](http://mlwiki.org/index.php/One-Way_ANOVA_F-Test)
