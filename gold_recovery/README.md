Улучшение процесса обогащения золота

Описание проекта
Требуется подготовить прототип модели машинного обучения, которая должна предсказать коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

Навыки и инструменты
python
pandas
numpy
scipy
sklearn.model_selection.cross_val_score
sklearn.metrics.mean_squared_error
sklearn.metrics.mean_absolute_error
sklearn.preprocessing.StandardScaler
sklearn.linear_model.LinearRegression
sklearn.tree.DecisionTreeRegressor
sklearn.ensemble.RandomForestRegressor
matplotlib

Общий вывод
изучены и обработаны данные 2. проведен анализ концентрации, размера гранул, исследована суммарная концентрация 3. построены и обучены 3 модели, с выбором лучших гиперпараметров через автоматическое подбирания параметров GridSearchCV 4. выбрана лучшая модель Случайный лес с симметричной средней абсолютной процентной ошибкой sMAPE = 6.6 5. проверил Случайный лес на тестовых данныхс sMAPE = 8.7 6. подтвердил оценку через константную модель с sMAPE = 8.9
