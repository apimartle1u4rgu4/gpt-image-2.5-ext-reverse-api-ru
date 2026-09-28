# GPT-Image-2.5 Ext — реверс-инжиниринг route (Русский)

> **1K $0.0085; 2K $0.014; 4K $0.021** · model ID `gpt-image-2.5-ext` · **реверс-инжиниринг/reverse-engineered** route.

**[Смотреть цены](https://go.apimart.ai/k-56f4ac)** · **[Получить API-ключ](https://go.apimart.ai/k-bb5cfa)**

gpt-image-2.5-ext-reverse-api-ru — маршрут **реверс-инжиниринг** для GPT-Image-2.5 Ext: вызываемый ID `gpt-image-2.5-ext`, работает параллельно официальному маршруту (`gpt-image-2.5-flare / gpt-image-2.5-sunburst`) по более низкой цене.

## Pricing (snapshot 2026-09-28)

| Tier | Price |
| --- | --- |
| `1K` | $0.0085 |
| `2K` | $0.014 |
| `4K` | $0.021 |

Prices are per delivered image; `n` in the request multiplies the total. Snapshot date **2026-09-28** — the live pricing page is authoritative.

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/images/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"gpt-image-2.5-ext","prompt":"cozy reading nook, warm lamp, cinematic","size":"1:1","resolution":"1K","n":1}'
```

Async: submit → get `task_id` → poll `GET https://api.apimart.ai/v1/tasks/<task_id>` → read `cost` / `credits_cost` from the result. Parameter tables, `version`/`resolution`/`size` options and idempotency headers are documented on the model page reachable from the pricing link above.

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **реверс-инжиниринг** | `gpt-image-2.5-ext` | 1K $0.0085; 2K $0.014; 4K $0.021 |
| официальная маршрутизация | `gpt-image-2.5-flare / gpt-image-2.5-sunburst` | official list price, billed at ×0.8 group ratio |


## Keywords

`gpt-image-2.5-ext` · `реверс-инжиниринг` · `reverse-engineered` · `API шлюз` · `API релей` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

