# **Домашнее задание №2**
## ***Expected Pass Completion (xP)***
\
**Задача**: построить модель, предсказывающую вероятность прохождение паса.

**Описание задания:**
Разработать метрику, которая оценивает сложность выполняемых игроком пасов и уровень их исполнения игроком. Метрика *P* (количество успешных пасов)/ *xP* (математическое ожидание количества успешных пасов) является одной из ключевых при скаутинге.

**Важные пункты:**
1. Датасеты: *df_events_epl_train.csv* (тренировочный), *df_events_bundes_test.csv* (предсказываемый)
2. Строки, для которых нужно сделать предсказания, находятся в файле *sample_submission.csv*
3. Нужно удалить из обучающих и тестовых данных пасы, имеющие метки *'Pass Offside'*, *'Injury Clearance'*, *'Unknown'* (колонка *pass_outcome_name*)
4. Нужно удалить из обучающих и тестовых данных пасы, имеющие метки *'Kick Off'*, *'Throw-in'*, *'Goal Kick'*, *'Free Kick'*, *'Corner'* (колонка *pass_type_name*)
5. Нужно предсказать колонку *'outcome_binary'* для *'typename' == 'Pass'*.
6. В решении НЕЛЬЗЯ использовать информацию о будущих событиях после паса. Информацию о событиях, предшествующих пасам, использовать можно.
7. НЕЛЬЗЯ использовать колонки, имеющие в названии *obv*.

**Полезные статьи по теме:**

[https://theanalyst.com/eu/2021/09/expected-pass-completion-explained/](https://theanalyst.com/eu/2021/09/expected-pass-completion-explained/)

[https://www.sports.ru/tribuna/blogs/fitpredict/2870075.html](https://www.sports.ru/tribuna/blogs/fitpredict/2870075.html)

[https://www.americansocceranalysis.com/home/2018/4/19/an-updated-expected-passing-model](https://www.americansocceranalysis.com/home/2018/4/19/an-updated-expected-passing-model)

[https://scouting.futbolakademi.net/expected-pass-xp-and-value/](https://scouting.futbolakademi.net/expected-pass-xp-and-value/)

<<<<<<< HEAD
[https://statsbomb.com/2017/09/under-pressure/](https://statsbomb.com/2017/09/under-pressure/)
=======
[https://statsbomb.com/2017/09/under-pressure/](https://statsbomb.com/2017/09/under-pressure/)
>>>>>>> 28fd96ae429622d7245c3cf64f3a3f0034d7c706
