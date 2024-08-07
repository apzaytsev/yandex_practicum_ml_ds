# Разработка моделей машинного обучения для управления рисками и принятия решения о покупке

## Задача проекта:
Разработка моделей для прогнозирования удоя молока и его вкуса с целью отбора подходящих для покупки коров

## Использованы библиотеки и методы:

## Выводы по проекту:
- Были созданы 3 модели линейной регрессии, лучшая из них имеет следующие метрики:
  - R2 = 0.8247542745210406
  - MSE = 35673.88988618197
  - MAE = 146.16302445362325
  - RMSE = 188.87532895055926
- Была создана модель логистической регрессии для прогноза вкуса молока, применена к выборке предлагаемых к покупке коров.
- Был определен порог классификации 0.6 с учетом метрик accuracy, precision и recall.
- К покупке рекомендуются 4 коровы (0, 7, 11 и 13), как имеющие удой более 6000 и дающие вкусное молоко.
