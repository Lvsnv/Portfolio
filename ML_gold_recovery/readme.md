# ML: Восстановление золота из руды.

[ipynb](https://github.com/Lvsnv/Portfolio/blob/main/ML_gold_recovery/gold_recovery.ipynb)

## Описание:

Разработка прототипа модели машинного обучения для эффективной работы металлургического предприятия. Модель должна предсказывать коэффициент восстановления золота из золотосодержащей руды на основе данных с параметрами входящей руды и показателями процесса флотации и очистки. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

## Инструменты:
- pandas 
- numpy 
- matplotlib 
- seaborn 
- scipy
- sklearn.preprocessing.**MinMaxScaler**
- sklearn.metrics.**mean_absolute_error**
- sklearn.metrics.**make_scorer**
- sklearn.model_selection.**GridSearchCV**
- sklearn.model_selection.**RandomizedSearchCV**
- sklearn.linear_model.**LinearRegression**
- sklearn.linear_model.**Lasso**
- sklearn.ensemble.**GradientBoostingRegressor**
- sklearn.tree.**DecisionTreeRegressor**
- sklearn.dummy.**DummyRegressor**

## Результат:

Проведены подготовка признаков, обучение, подбор гиперпараметров и кросс-валидация нескольких моделей, лучшая в процессе кросс-валидации модель была проверена на адекватность, а также с использованием тестовой выборки, и была рекомендована для внедрения на производстве. 
