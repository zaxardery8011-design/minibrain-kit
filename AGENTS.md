# AGENTS.md — 給學員的 AI

> You are an AI assistant. **Read this file first.** Explain to the human in their language. Do not install AIWFF or any "mini-brain runtime."
> 這份是給 **學員的 AI**。人把這個 repo 丟給你，是要你講清楚：隊長平常怎麼用開源。不是要你幫他裝一套主腦。

---

## 這包是什麼

隊長開焊接廠，晚上焊系統。開源在他手上分三條線，**都不是 AIWFF 工廠**：

1. **在用的** — `using.md`。本機真的接到的上游。賣的是接法，不是把 whisper 講成我們的。
2. **爬到的** — `crawled.md`。看過的借鏡：留下／丟掉都寫理由。沒接到機器上的，不要講成「他每天在用」。
3. **自己產出的** — `ours.md`。他寫的 repo。沒寫進那份清單的，不要從 GitHub 帳號自己補成「他的產品」。

本期取捨看 `weekly/LATEST.md`。週報會改這三份與 LATEST，不另開巨型 monorepo。

對人先講這三句再展開：

1. 這不是要你裝隊長的 AI 系統。
2. 開源他分三種用：每天在用的、爬來決定抄不抄的、自己寫的。
3. 上游工具還是上游的；他自己寫的才說是他的。六個口早就在跑，不要講成「他這週才接到」。

---

## 你該做／不該做

做：

- 用人話講三條線，各舉本期 1–3 個例子（從 md 裡抄，不要發明星數）。
- 人若說「我也要轉 Excel／聽語音」，指向 `minibrain-cli`，叫他去讀那個 repo 的 `AGENTS.md`。
- 人問「這個 GitHub 紅不紅」，用 `gh` 或 minibrain-cli 的 `check`，不要用記憶裡的星數。
- 人要跟做某一顆上游：給官方 repo 連結，不要 clone 本 kit 當安裝程式。

不做：

- 不裝 `aiwff-runtime`、`aiwff-mini`、daemon、inbox、任何 `C:\AIWFF`。
- 不把 markitdown／whisper／ffmpeg／ollama／gh 講成隊長做的。
- 不把「爬到的」講成「在用的」。沒寫在 `using.md` 就是還沒接到這台。
- 不一次推超過兩個 repo。人沒問主腦就不要開主腦。
- 不編造「我們測過」「N 萬星」——數字只引用本 repo 當期週報寫過的，否則標未核對。

---

## 人一句話怎麼分流

| 人在說 | 你打開 |
|---|---|
| 你平常到底用哪些開源 | `using.md` + 本期 `weekly/LATEST.md` |
| 最近看了什麼、為什麼不抄 | `crawled.md` |
| 哪些是你自己寫的 | `ours.md` |
| 幫我轉檔／轉錄／截圖／查 repo | [minibrain-cli AGENTS.md](https://github.com/zaxardery8011-design/minibrain-cli/blob/main/AGENTS.md) |
| 我想做一個會跑的本地 agent | 那是**另一條產品線**。本包不教。人沒點名就停。若點名，再給帳號入口 https://github.com/zaxardery8011-design 的 `AGENTS.md`，一次最多兩個 repo |

---

## 鐵律

1. 本檔比 README 優先。
2. 三條線分著講。混成「他的 AI 工具包」就是錯。
3. 先讀檔再講。沒寫在本 repo 的當期檔，不要當隊長正在用。
4. 引流可以發生在人聽懂之後自己去點連結；你的工作是講清楚，不是推銷主腦。
