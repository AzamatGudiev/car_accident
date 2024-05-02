# car_accident
analysis of a car accident reports in Ingushetia

Что сделано:

В этом исследовании я использовал методы обработки естественного языка и API ChatGPT для категоризации ключевых аспектов данных о дорожном движении, в частности, таких колонок как `status_violations`, `nearby`, `nearby_road_conditions` и `participant_violations`. С помощью методов инженерии признаков я улучшил датасет, сделав его характеристики более понятными и релевантными для анализа, что позволило получить более глубокие выводы из данных. (смотреть clustering_and_feat_engineering.ipynb)

Затем я использовал различные инструменты визуализации для создания графиков и таблиц, которые ясно и эффективно показывают тенденции и закономерности в данных. (смотреть accident_analysis.ipynb)

Кроме того, я применил Google API  для определения общественных мест поблизости от мест аварий. Эту информацию я интегрировал в анализ и нарисовал на карте как аварии, так и близлежащие общественные места, что позволило получить комплексное представление о факторах, влияющих на безопасность дорожного движения. (смотреть Google_API.ipynb)

