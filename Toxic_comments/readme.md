# Анализ текстов

[HTML](https://github.com/siniatkinfeliks/yandex-practicum-projects-data-science/blob/main/Toxic_comments/Siniatkin_Feliks_ML_for_texts_toxic_comments.html)     [ipynb](https://github.com/siniatkinfeliks/yandex-practicum-projects-data-science/blob/main/Toxic_comments/Siniatkin_Feliks_ML_for_texts_toxic_comments.ipynb)

## Описание проекта

Требуется анализировать комментарии пользователей на английском языке и выделять токсичные, чтобы отправить на модерацию.



## Навыки и инструменты

- **python**
- **pandas**
- **matplotlib**
- **numpy**
- nltk.stem.**WordNetLemmatizer**
- nltk.corpus.**stopwords**
- **re**
- sklearn.feature_extraction.text.**TfidfVectorizer**
- sklearn.model_selection.**train_test_split**
- sklearn.tree.**DecisionTreeClassifier**
- sklearn.ensemble.**RandomForestClassifier**
- sklearn.linear_model.**LogisticRegression**
- sklearn.experimental.**enable_halving_search_cv**
- sklearn.model_selection.**HalvingGridSearchCV**
- sklearn.metrics.**f1_score**, **roc_auc_score**

## Вывод

Была проведена исследовательская работа по обработке текстов и обучению и выбору модели для определения токсичных комментариев по методу TF-IDF. Выбрана модель логистической регрессии.
