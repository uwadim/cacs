---
title: Сервис-репозиторий программного обеспечения
date: "2022-11-20T00:00:00Z"

reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: false  # Show author profile?
comments: false  # Show comments?

header:
  caption: ""
  image: ""
---
В рамках программы «Академическое лидерство «Приоритет 2030», предложенной Федеральным государственным автономным образовательным учреждением высшего образования «Первый Московский государственный медицинский университет имени И.М. Сеченова» Минздрава России (Сеченовский университет), ЦАССом было разработано или адаптировано следующее программное обеспечение:
1. Программное обеспечение для серийного анализа [синолитических графов](https://www.frontiersin.org/articles/10.3389/fgene.2021.733783/full) с помощью GNN[^1].
    - [Код для построения паренклитических / синолитических графов](https://github.com/solomennik/parenclitic_synolytic)
    - [Код для применения графовых нейронных сетей к задаче классификации паренклитических / синолитических графов](https://github.com/uwadim/parenclitic_gcn)
    - [Походы к классификации с использованием графов в связке со сверточной нейронной сетью (на примере масс-спектрометрии выдыхаемого воздуха)](https://github.com/solomennik/convo-network-with-graphs)
2. Сравнительный анализ различных сетей, паренклитических и корреляционных графов.
    - [Оценка дизадаптации динамических систем с использованием паренклитических и корреляционных графов для временных рядов](https://github.com/solomennik/ts-graph-methods)
3. Программное обеспечение для анализа протеомных данных - серийных онкомаркеров[^2].
    - [Однопеременная полностью Байесовская иерархичная модель для поиска точки поворота и классификации для ранней детекции рака](https://github.com/solomennik/proteomic-data/blob/main/uEB_code.R)
    - [Многопеременная полностью Байесовская иерархичная модель для поиска точки поворота и классификации для ранней детекции рака](https://github.com/solomennik/proteomic-data/blob/main/mFB_code.R)
    - [Однопеременная параметрическая эмпирическая Байесовкая модель](https://github.com/solomennik/proteomic-data/blob/main/uFB_code.R)
4. [Программное обеспечение для моделирования обработки информации в нейрон-астроцитарных сетях](https://github.com/altergot/neuro-astro-network)
5. Поограммы для цифровой модели печени.
    - [Программы для математической модель метаболизма гепатоцеллюлярного холестерина и липопротеинов in vitro для терапии гиперлипидемии](https://github.com/solomennik/liver-modeling)

[^1]: Графовые нейронные сети ([Graph neural network](https://en.wikipedia.org/wiki/Graph_neural_network))
[^2]: [A Bayesian Screening Approach for Hepatocellular Carcinoma Using Multiple Longitudinal Biomarkers](https://github.com/solomennik/proteomic-data/blob/main/Tayob_et_al-2018-Biometrics.pdf)
