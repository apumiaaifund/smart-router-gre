# Smart Router + GRE 2.0 — Public Demo

<p align="center"><img src="assets/logo.svg" alt="logo" width="400"></p>


## За 30 секунд

**Что это:** Smart Router + GRE 2.0: air-gapped LLM router + PII shield. Маршрутизирует запросы по типу данных, sensitive → локально.

**Кому:** Обороны, госсектор, regulated industries — LLM без облака.

**Что доказано:** 145 тестов (49 gre + 96 router).

**Чего не доказано (честно):** Нет production-развёртывания.

---



On-Premise, Air-Gapped шлюз для оптимизации LLM-инфраструктуры.
**Demo materials only.** Full source code — available on purchase.

## What is this

1. **Smart Router Gateway 1.0.0** — semantic cache + Scoring Layer.
   Bank secrecy (20-digit accounts) → CPU node qwen2.5-7b-cpu.
2. **Green Router Enterprise (GRE 2.0)** — noise filtering, normalization
   (NEVER_STRIP), masking 5 PII + 3 secrets.

## Verification (internal)

| Layer | Result |
|---|---|
| Static + deps | OK |
| GRE pytest | 19 passed |
| GRE evals | 14/14 passed |
| Router HTTP | 16/16 passed |
| **Total** | **145 tests** |

## Demo files

### Pitch & slides
- `OnePager.html` — product one-pager
- `Демо_слайды.html` — demo slides
- `Демо_v2.html` — interactive demo
- `Слайд_Делаем_Не_делаем.html` — scope: what we do / don't
- `Границы_v2.html` — project boundaries

### Commission & analysis
- `Q&A_КОМИССИЯ.md` — commission Q&A
- `Письмо_Конкуренты.html` — competitor analysis

### Demo requests (examples)
- `Демо_запрос2_sensitive.json` — sensitive request example
- `Демо_запрос5_PII.json` — PII request example
- `ПОКАЗ/` — demonstration artifacts (PII masking, sensitive routing, CPU/ACCOUNT)

## Full source

Available on purchase. Private repository + ZIP.
Contact: apumiaaifund@gmail.com

## Data integrity

**No synthetic data in production.** All external sources documented in `sources.yaml` (Private repo) with official URLs, real dates, status. Demo marked `_synthetic: true`.

**Никакой синтетики в продакшене.** Все источники — в `sources.yaml` с официальными URL и реальными датами.
