# Архитектура — «Медикаменте» (учебный проект)

---
Анализ текущего ИТ‑ландшафта клиники, проектированию целевого решения с Privacy by Design, стратегии защиты данных и оценке рисков миграции.

- Диаграммы: `.drawio` в `Task1/dfd`, `Task2`, `Task4`
- Документация: `.md` в `Task1`, `Task2`, `Task3`, `Task4`



## 🧭 Артефакты по заданиям

- Task1. Анализ As Is. потоки данных. аудит безопасности. список проблем
- Task2. Диаграмма контекста C4 целевого состояния с блоками Privacy by Design
- Task3. Классификация данных и таблица мер защиты плюс автоматизация контроля
- Task4. Диаграмма Исикавы по рискам миграции и рекомендации

## 🧭 Как открыть и просматривать

- Откройте `.drawio` в приложении draw.io Desktop или в браузере `app.diagrams.net`
- Целевая C4. `Task2/project10-landscape.drawio.xml`
- DFD. `Task1/dfd/1-appointment.drawio` `2-payment.drawio` `3-medical-records.drawio` `4-inventory.drawio`
- Исикава. `Task4/ishikawa.drawio`

## 🧭 Структура проекта

```
.
├─ Task1/                 # анализ As Is и DFD
│  ├─ dfd/
│  │  ├─ 1-appointment.drawio
│  │  ├─ 2-payment.drawio
│  │  ├─ 3-medical-records.drawio
│  │  └─ 4-inventory.drawio
│  └─ docs/
│     ├─ confidential_inventory.md
│     ├─ security_audit.md
│     ├─ problems.md
│     ├─ data_protection_catalog.md
│     └─ tagging_mechanism.md
├─ Task2/                 # целевое состояние C4
│  ├─ project10-landscape.drawio.xml
│  └─ README.md
├─ Task3/                 # стратегия защиты данных
│  └─ docs/
│     ├─ classification.md
│     ├─ protection_table.md
│     ├─ tools_registry.md
│     └─ controls_automation.md
├─ Task4/                 # риски миграции
│  ├─ ishikawa.drawio
│  └─ report.md
└─ README.md
```
## 🧭 Нефункциональные требования

- Безопасность. конфиденциальность данных шифрование RBAC ABAC тегирование аудит мониторинг удаление данных по запросу субъекта
- Масштабируемость. рост клиентов филиалов и сотрудников
- Сопровождаемость и конфигурируемость. понятные артефакты и возможность менять конфигурации без доработок


