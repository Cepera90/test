test_1_2_ipynb".ipynb - decision:
1) Некоторые параметры набора точек для трека имеют различную размерность в зависимости от платформы (iOS или Android) - какие это параметры?
2) Переведите все параметры в одинаковую размерность

test_3.ipynb - decision:

3) В richtracks для каждого трека есть поле TrackOrigin, которое описывает кем была произведена поездка: владельцем смартфона или нет. 
Задание: постройте модель, предсказывающую на основании данных из входящих точек, была ли поездка пассажирской или нет.

Try to add features MidOverSpeed and HiOverSpeed.
Add feature duration of track.

Use DecisionTreeClassifier model (Execution time 11s, score 0.839),
BaggingClassifier (Execution time 6m (n_estimators=56), score 0.905),
RandomForestClassifier (n_estimators=37, score 0.899),
ExtraTreesClassifier (Execution time 3m, score 0.9045),
AdaBoostClassifier (Execution time 4m(n_estimators=56), score 0.774).
