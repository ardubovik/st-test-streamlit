# Программная инженерия. Модуль 4

### Дубовик А.А. 

#### Генерация описания по изображению (image to text model)
- [Приложение](/PW2/image_to_text_app/image_to_text_app.py)

# Генерация описания по изображению (image to text model)

## Постановка задачи:

Развернуть ранее созданное Web приложение, используя фреймворк `Streamlit` и предварительно обученную модель из `HuggingFace` в облаке для доступа пользователей через интернет.

## Решение:

Решение реализовано в облаке `Streamlit Cloud`.

Применена готовая модель: https://huggingface.co/Salesforce/blip-image-captioning-base

Модель предварительно обученная на наборе данных COCO — базовая архитектура (с базовой магистралью ViT) и применима для условных и безусловных подписей к изображениям. 

### Работа с приложением:
1) Открыть в браузере URl: https://st-test-app-ln9askzyjcjudqc245kw5i.streamlit.app/
2) Загрузить изображение, нажав кнопку `Browse files`
3) Нажать кнопку "Сгенерировать описание"

### Пример ответа:

```
Результат (eng): A man in a hard hat looking at something
```

### Необходимые зависимости:
```
    transformers
    sentencepiece
    streamlit 
    torch
```
### Установка зависимостей:
```
    pip install -r requirements.txt
```
