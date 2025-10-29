# Image quality evaluation metric for generative models

Refer to the paper *./AMICON_paper.pdf* for details about this work, including setup, models, datasets and image quality evaluation metrics used, as well as proposed metric and results.

---

Ревера Ярослав ПМІ-45, бакалаврська робота 2025. 

ДОСЛІДЖЕННЯ ТА АДАПТАЦІЯ МЕТРИК ОЦІНКИ ЯКОСТІ ЗОБРАЖЕНЬ ДЛЯ ГЕНЕРАТИВНИХ НЕЙРОННИХ МЕРЕЖ

Керівник: Пелюшкевич О.В.

For implementation of CycleGAN and pix2pix, source code of original authors was used.

В даному репозиторії підготовано Jupyther ноутбуки для проведення порівняння та аналізу оцінки метрик. Зокрема, у файлі `eval_evffd.ipynb` знаходиться код для обчислення значення запропонованої метрики як для всього набору даних, так і для окремих зображень. 

Для успішного проведення оцінки та результатів необхідно задати шлях до справжніх та згенерованих зображень.

Для оцінки використовуючи існуючі метрики FID та SSIM можна використати запропоновані скрипти, які знаходяться в корені репозиторію і названі відповідно. Використання таке ж як і для запропонованої метрики. 
