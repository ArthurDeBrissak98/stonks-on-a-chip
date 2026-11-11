# stonks-on-a-chip

> "I was the best, and I left a little surprise in the Net."
> — Rache Bartmoss

**v2: from UART/WebSocket to silicon limits.**

---

## Цель

Найти физические пределы STM32H7 для tick-to-trade: транспорт, CPU,
латентность, джиттер. Не «сделать торгового бота», а измерить, где
заканчивается кремний и начинается следующий уровень абстракции
(Ethernet, kernel bypass, FPGA).

## Документы

- [ADR-001 — выбор MCU](docs/ADR-001-mcu-selection.md)
- [ADR-002 — стратегия транспорта](docs/ADR-002-transport-strategy.md)
- [LIMITS-EXPERIMENT-PLAN — план измерения пределов](docs/LIMITS-EXPERIMENT-PLAN.md)

## Статус

**Planning phase. Hardware: Nucleo-H723ZG (pending purchase).**

## История

- **v1 (archived):** educational sandbox with UART/WebSocket.
- **v2 (this repo):** production-grade exploration of physical limits.
