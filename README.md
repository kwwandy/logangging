# 羅庚勁

九宮飛星、八宅八遊星、家人命卦，配合手機指南針使用。

## 放上 GitHub Pages

1. 喺 GitHub 開一個新 repository（例如 `luogeng`），設做 Public
2. 撳 **Add file → Upload files**，將呢個資料夾入面**所有檔案同 `icons` 資料夾**一齊拖入去，再撳 **Commit changes**
3. 去 **Settings → Pages**，Source 揀 **Deploy from a branch**，Branch 揀 `main`、資料夾揀 `/ (root)`，撳 **Save**
4. 等一兩分鐘，網址會係 `https://你的帳戶名.github.io/luogeng/`

## 加到手機主畫面

- **iPhone（Safari）**：撳分享 → 加入主畫面。第一次撳「用指南針」會問你批准動作感應器，要撳允許
- **Android（Chrome）**：撳右上角 ⋮ → 安裝應用程式／加到主畫面

## 檔案

| 檔案 | 用途 |
|---|---|
| `index.html` | 整個 app |
| `manifest.json` | App 名稱、圖示、主題色 |
| `sw.js` | 離線使用（開過一次之後冇網都用得） |
| `icons/` | Logo 同各尺寸圖示 |

## 更新

改完 `index.html` 再上載覆蓋就得。如果手機仍然見到舊版，將 `sw.js` 第二行 `luogeng-v1` 改做 `luogeng-v2`（之後每次加一）再上載。
