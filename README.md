# AIJ 2020: Digital Peter

1 Выполнялось обучение модели для преобразования сканов в тест Петра I
<br>https://github.com/GladyshevVitaly/AIJ-2020/blob/main/aij-pg-img-to-peter-text.ipynb

2 Код для исполнени модели в контейнере
<br>https://github.com/GladyshevVitaly/AIJ-2020/blob/main/run_eval.py

3 Формирую датасет на основе корпуса текстов XVII века для обучения seq2seq фильтра-корректора
<br>https://github.com/GladyshevVitaly/AIJ-2020/blob/main/dt_17th_prep.ipynb

4 Обучение модели seq2seq фильтра-корректора
<br>https://github.com/GladyshevVitaly/AIJ-2020/blob/main/seq2seq_post.ipynb

5 Код для исполнения в контейнере преобразования скана в текст с последующей seq2seq коррекцией
<br>https://github.com/GladyshevVitaly/AIJ-2020/blob/main/run_eval_sts_attn.py

Код отправлялся в Docker на ODS.AI

Самой большой проблемой данного соревнования была острая нехватка вычислительных мощностей и особенно объёма памяти ускорителя

Использовал ускорители на платформах:
- Colaboratory
- Kaggle
- Яндекс DataSphere

Место занял не самое высокое. Но опыта приобрёл массу :)

Таблица результатов: https://ods.ai/competitions/aij-petr/leaderboard
