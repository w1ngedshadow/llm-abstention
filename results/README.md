# Результаты

Baseline: Qwen2.5-3B-Instruct на VitaminC. Сравниваем ответы без отказа, отказ по исходной уверенности и после temperature scaling. Источники представлены текстом и таблицами.

- [Итоговая таблица](qwen3b_baseline/calibration_summary.csv) — риск, охват, ECE, пороги и 95% доверительные интервалы.
- [Начальный эксперимент без калибровки](qwen3b_baseline/summary.csv).
- [График риска и охвата без калибровки](qwen3b_baseline/risk_coverage.png).
- [Ноутбук](baseline_vitaminc.ipynb) — расчёты и графики.
- [Описание эксперимента](../report/baseline.md).

Предсказания модели сохранены в папке [`qwen3b_baseline/`](qwen3b_baseline/).
