# Лабораторна робота № 10: Трансферне навчання у TensorFlow та Keras 3

* **Студентка:** Чернега Катерина, група МІТ-31
* **Модель:** `EfficientNetB0` (`weights="imagenet"`, вхід `224×224×3`, шкала `[0, 255]`)
* **Дані:** Підмножина Food-101 із ЛР №9 (`chocolate_cake`, `hamburger`, `ravioli`), очищена від SHA-256 дублікатів.

## Порядок запуску
1. Переконайтеся, що підготовлена вибірка з ЛР №9 знаходиться за шляхом `../Lab9/data/food101_lab9` (або в `Lab10/data`).
2. Запустіть ноутбук `lab10_transfer_learning.ipynb` зверху вниз у середовищі Python із TensorFlow 2.16+ (Keras 3), NumPy, Pandas, Matplotlib та Scikit-learn.
3. Усі таблиці, графіки та `metadata.json` зберігаються у папку `lab10_results/`.

## Вміст папки `Lab10`
* `lab10_transfer_learning.ipynb` — повний код, криві навчання, матриця помилок, аналіз помилок та висновки.
* `lab10_results/` — порівняльна таблиця валідації (`validation_comparison.csv`), `metadata.json`, `split_manifest.json` та графіки.
* `README.md` та `.gitignore`.