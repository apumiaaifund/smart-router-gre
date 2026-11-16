<p align="center"><img src="assets/logo.svg" alt="logo" width="400"></p>

![PROVEN](https://img.shields.io/badge/PROVEN-145%20passed-brightgreen)

# Smart Router + GRE 2.0

**Air-gapped LLM router + PII shield. Маршрутизирует по типу данных, sensitive → локально.**

---

## За 30 секунд

**Что это:** Air-gapped LLM router + PII shield. Маршрутизирует запросы по типу данных: sensitive → локальная модель, публичное → GPU.

**Кому:** Обороны, госсектор, regulated industries — LLM без облака.

**Почему сейчас:** Нельзя отправить «СНИЛС + диагноз» в OpenAI. Smart Router держит sensitive-данные локально, публичные — в GPU.

**Что доказано:** 145 passed (49 gre + 96 router). apumia prove → PROVEN.

**Чего не доказано (честно):** Нет production-развёртывания. Integration-тесты требуют live gateway (router/test_suite.py — исключены из unit-прогона).

---

## Оффер

По запросу.

**Следующий шаг:** Покажу маршрутизацию на живом примере — 20 минут.

---

## GitHub

- **Private code:** apumiaaifund/smart-router-gre
- **Public demo:** apumiaaifund/smart-router-gre-demo

## License

MIT

---

### 🛡️ Верификация качества и безопасности (Apumia DevSecOps Gate)

> **Статус:** `VERIFIED & PROVEN` • **Дата аудита:** `16.11.2026`  
> **Контроль архитектуры (`Apumia Blueprint`):** `CLEAN` (`0` циклических зависимостей, контроль сложности McCabe)  
> **Анализ безопасности (`Bandit / Zero-Trust`):** `0` критических уязвимостей  
> **Протокол достоверности (`Apumia Hub`):** `_synthetic: false` | `preservation: 100.0%` | `verified: true`
