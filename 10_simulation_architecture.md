# Simulation Architecture

## Phase 1 — Excel engine

Перша версія симулятора має будуватись в Excel, бо це найшвидший спосіб перевірити логіку.

### Принцип
- кожен бізнес = окремий набір листів;
- спільні ресурси = окремий блок;
- сезонність = окремий блок;
- зведення = окремий блок.

### Орієнтовна структура
Для кожного бізнесу:
- inputs;
- operations;
- unit economics;
- seasonality;
- monthly cash flow;
- risks / scenarios.

Для системи:
- shared resources;
- capex plan;
- working capital model;
- group cash flow;
- dashboard;
- scenario manager.

## Phase 2 — Excel with rules

На другому етапі додаються:

- правила конфлікту за техніку;
- правила пріоритетів;
- автоматичні прапори ризику;
- пороги зупинки / масштабування.

## Phase 3 — Python simulator

Python потрібен тоді, коли з'явиться потреба у:

- подієвій симуляції;
- складній диспетчеризації;
- оптимізації маршрутів;
- десятках взаємозалежних правил;
- швидкому прогоні багатьох сценаріїв;
- окремому UI.

## Архітектурний принцип

Дані мають бути однаковими в обох світах:

- Excel як перша керована модель;
- Python як наступний рівень обчислення.

## Ключові модулі майбутньої моделі

- master data;
- pricing;
- routes;
- assets;
- storage;
- working capital;
- taxes;
- scenario engine;
- decision rules;
- KPI engine.

## Обов'язкові outputs

- net profit by direction;
- cash flow by month;
- working capital need;
- asset utilization;
- bottlenecks;
- weakest link;
- best scaling candidate;
- stress scenario result.
