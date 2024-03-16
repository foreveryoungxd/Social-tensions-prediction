# Social-tensions-prediction
В данном ноутбуке представлены подходы прогнозирования социальной напряженности в отдельных странах
на основе методов машинного обучения. Цель исследования заключалась в том, чтобы повысить результативность прогнозирования за счет анализа военно-политических, экономических, демографических факторов, а также предобработки выбранных предикторов. Результатом стала модель машинного
обучения, позволяющая с точностью рассчитанных метрик спрогнозировать внутренний вооруженный
конфликт как высшую форму социальной напряженности.

Результатом исследования стало то, что в предсказании вероятности возникновения внутреннего вооруженного конфликта играют следующие факторы:
1) Демократичность правящей власти (democracy_index) - военно-политический фактор
2) Государственный контроль над территорией страны (state_control_over_territory) - военно-политический фактор
3) Природная рента (resources_rent_procent_of_GDP) - экономический фактор
4) Инфляция (inflation_rate) - экономический фактор

В статье - https://izv.etu.ru/assets/files/izvestiya-9-2023-49-59.pdf описан полных ход исследования, приведены ссылки на источники данных для анализа, а также применение более простых подходов к прогнозированию вероятности возникновения внутреннего вооруженного конфликта на основе случайных деревьев решений и случайного леса деревьев решений.
