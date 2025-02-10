# ai-course-project

## Ціль проекту

прототип RAG системи для генерації sustainability чеклистів для бізнесу на основі сформованої бази знань

## Інструкції з запуску

Оточення:

Використовуємо Google Colab або локальне середовище з підтримкою Python 3.
Потрібно встановити необхідні пакети:

!pip install openai==0.27.0 transformers sentence-transformers faiss-cpu gradio python-docx scikit-learn

Репозиторій та код:

Завантажити/скопіювати файл сourse-project.ipynb із GitHub-репозиторію.
Відкрити Notebook у Google Colab або запускати локально.

Або відкрити напряму: https://colab.research.google.com/drive/1wwFZL319l10YKDknaHayYlMkwlJdu1yn?authuser=1

Запустити клітинки:
По черзі виконати всі комірки, встановити бібліотеки, оголосити змінні.

Gradio Blocks інтерфейс:
Запуск: коли ви виконаєте demo.launch(), з’явиться посилання.

Перейдіть за посиланням:
Company Information (англійською) — введіть опис бізнесу (шведською чи англійською, за бажанням). Наприклад, Home cleaning service company in Stockholm.
Upload a file — опційно завантажте ваш DOCX/TXT з sustainability-текстами. (тут можна скачати docx) з підготовленими релевентнами текстами з реальними даним.)
Натисніть “Generate Checklist” — отримаєте Generated Checklist шведською та автоматичну релевантність (Automatic Relevance).
За потреби виставте Your Rating (1–5) та натисніть “Submit Rating”, щоб отримати JSON із підсумком.

