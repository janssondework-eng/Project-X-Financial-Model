# Project X Financial Model

[English version](README.md)

Финансовая модель для портфолио по early-stage digital platform, сфокусированной на студенческом жилье и подборе соседей.

Модель оценивает стратегию монетизации, рост пользователей, unit economics, операционные расходы, cash flow, valuation и sensitivity в разных бизнес-сценариях.

## Краткое резюме

- Тип модели: startup operating and valuation model
- Горизонт прогноза: 36 месяцев
- Бизнес-концепция: платформа для студенческого жилья и roommate matching
- Сценарии: Conservative, Base, Optimistic
- Начальные активные пользователи в Base-сценарии: 2 500
- Месячный рост пользователей в Base-сценарии: 5.5%
- Месячный churn в Base-сценарии: 3.5%
- Конверсия в успешную сделку в Base-сценарии: 15.0%
- Средняя комиссия в Base-сценарии: 4.0%
- Ставка дисконтирования в Base-сценарии: 18.0%

Выбранные base-case outputs, видимые на скриншотах workbook:

| Метрика | Результат |
|---|---:|
| 2026 Revenue | 6.90M RUB |
| 2027 Revenue | 8.75M RUB |
| 2028 Revenue | 11.62M RUB |
| NPV | 7.14M RUB |
| IRR | 254.1% |
| Implied valuation | 34.86M RUB |
| Total 3-year EBITDA | 11.93M RUB |

Все допущения синтетические и используются только для портфолио, обучения и практики финансового планирования.

## Бизнес-концепция

Project X - цифровая платформа, которая помогает студентам и молодым специалистам находить совместимых соседей и варианты жилья через более структурированный процесс.

Модель оценивает, может ли платформа стать финансово привлекательной через несколько потоков монетизации:

- комиссия с успешных арендных сделок
- premium subscription
- partnership revenue
- advertising revenue
- promoted listings
- paid listings после достижения более сильной marketplace traction

## Структура модели

Workbook включает:

| Лист | Назначение |
|---|---|
| `Cover` | обзор модели и навигация |
| `Assumptions` | scenario selector и ключевые бизнес-допущения |
| `Monthly Model` | 36-месячный operating forecast |
| `Annual Summary` | годовая сводка revenue, EBITDA и active users |
| `Unit Economics` | ARPU, CAC, LTV, LTV/CAC и payback logic |
| `P&L` | profit and loss statement |
| `Cash Flow` | free cash flow и discounted cash flow |
| `Valuation` | NPV, IRR и revenue multiple valuation |
| `Sensitivity` | чувствительность revenue к deal conversion и commission |
| `Dashboard` | визуальная сводка ключевых outputs |
| `README Notes` | заметки workbook для GitHub documentation |

## Дополнительная документация

- [docs/model_overview.md](docs/model_overview.md)
- [docs/assumptions_and_scenarios.md](docs/assumptions_and_scenarios.md)
- [docs/valuation_methodology.md](docs/valuation_methodology.md)
- [docs/model_audit_notes.md](docs/model_audit_notes.md)
- [docs/improvement_backlog.md](docs/improvement_backlog.md)

## Скриншоты

### Dashboard Preview

![Dashboard Preview](screenshots/dashboard_preview.png)

### Assumptions

![Assumptions](screenshots/assumptions.png)

### Unit Economics

![Unit Economics](screenshots/unit_economics.png)

### Cash Flow

![Cash Flow](screenshots/cash_flow.png)

### Valuation

![Valuation](screenshots/valuation.png)

### Sensitivity Analysis

![Sensitivity Analysis](screenshots/sensitivity_analysis.png)

## Ключевые аналитические функции

- 36-месячный прогноз
- scenario selector
- логика месячного роста пользователей и churn
- выручка по потокам монетизации
- фиксированные и переменные cost assumptions
- P&L forecast
- free cash flow forecast
- NPV and IRR framework
- revenue multiple valuation
- unit economics
- sensitivity analysis
- dashboard summary

## Навыки, показанные в проекте

- financial modeling
- startup finance
- revenue modeling
- unit economics
- scenario analysis
- sensitivity analysis
- P&L forecasting
- cash flow forecasting
- valuation logic
- структура Excel-модели
- investment case preparation
- business analysis

## Структура репозитория

```text
Project-X-Financial-Model/
|-- README.md
|-- README_RUS.md
|-- LICENSE
|-- financial_model/
|   `-- Project_X_Financial_Model.xlsx
|-- docs/
|   |-- assumptions_and_scenarios.md
|   |-- improvement_backlog.md
|   |-- model_audit_notes.md
|   |-- model_overview.md
|   `-- valuation_methodology.md
`-- screenshots/
    |-- annual_summary.png
    |-- assumptions.png
    |-- cash_flow.png
    |-- cover.png
    |-- dashboard_preview.png
    |-- monthly_model.png
    |-- pnl_statement.png
    |-- sensitivity_analysis.png
    |-- unit_economics.png
    `-- valuation.png
```

## Как ревьюить

1. Начать с `README.md` для понимания бизнес-кейса и outputs.
2. Открыть `docs/assumptions_and_scenarios.md`, чтобы понять ключевые драйверы.
3. Открыть workbook и просмотреть `Assumptions`, `Monthly Model`, `Unit Economics`, `Cash Flow`, `Valuation` и `Dashboard`.
4. Использовать `docs/model_audit_notes.md` и `docs/improvement_backlog.md`, чтобы понять текущие ограничения и будущие улучшения.

## Дисклеймер

Это синтетическая модель для портфолио. Она не является инвестиционной рекомендацией и не должна использоваться для реального инвестиционного решения без валидированных рыночных данных, source-backed assumptions, полноценного model audit и sensitivity review.
