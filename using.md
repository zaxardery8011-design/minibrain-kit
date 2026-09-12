# 在用的

這台機器上有接到、還在跑的上游。官方 repo 是別人的。接法見 [minibrain-cli](https://github.com/zaxardery8011-design/minibrain-cli)。

| 上游 | 接到哪個口 | 在這台做什麼 | 取捨 |
|---|---|---|---|
| [microsoft/markitdown](https://github.com/microsoft/markitdown) | `md` | Excel 報價、ERP PDF、pptx 講義先變 Markdown 再讀 | xlsx 合併儲存格會變 Unnamed |
| [ggml-org/whisper.cpp](https://github.com/ggml-org/whisper.cpp) | `hear` / `digest` | TG 語音、自拍片、YouTube 音軌轉逐字稿，走本機 CUDA | 專有名詞會聽錯；簡體可能混進中文稿 |
| [FFmpeg](https://ffmpeg.org) | `hear`（影片）、`digest` | 抽音、轉 16k wav | 只當管子，不當產品 |
| [yt-dlp/yt-dlp](https://github.com/yt-dlp/yt-dlp) | `digest` | 拉 YouTube 音軌 | 下載規則常變 |
| [cli/cli](https://github.com/cli/cli)（gh） | `check` | 外部說「這個很紅」時驗 repo 存在和星數 | 只驗量級，不驗內容 |
| poppler（pdftoppm） | `md` 轉 PDF | PDF 進 markitdown 時要它在 PATH | 沒裝就轉失敗 |
| Microsoft Edge | `shot` | 改完頁面截一張靜態圖自己看 | 只有一幀；非 Windows 沒接 |
| [ollama](https://ollama.com) | `digest` 摘要（可選） | 有在聽 `127.0.0.1:11434` 才蒸餾；沒有就逐字稿 | 事實對比與最終決策不給它 |

沒寫在這張表＝這台沒把它當日常口。那是「爬到的」或還沒接。
