# 手作風鈴活動簡報｜網頁版部署

**對外網址：** https://molly0318.github.io/windchime-deck/

**GitHub Repo：** https://github.com/MOLLY0318/windchime-deck

---

## 說明

「森林的回聲：音符、節奏與果實」活動簡報的部署用副本。供 iPad（或任何裝置）連線開啟，透過 HDMI 投影到大螢幕使用，不需要帶筆電。

## 本機路徑

```
100_Todo/projects/windchime-deck/
```

> 資料夾英文名稱 `windchime-deck` 對應 GitHub Pages 網址，不可更改，否則網站連結會失效。

## 與原始專案的關係

- 原始工作檔（含腳本、流程、教學筆記）在 `100_Todo/projects/2026-06-music-therapy-windchime/`，是正式的內容來源。
- 這個資料夾只放部署用的 `index.html` + `images/` + `music/`，音樂為了符合 GitHub 100MB 單檔限制與現場網路載入速度，全部轉壓成 128kbps（原始高音質版本留在 `2026-06-music-therapy-windchime/music/`，本機播放用）。

## 更新流程

若原始簡報 `index.html` 有修改：

1. 複製最新版 `2026-06-music-therapy-windchime/index.html` 到這裡
2. 若音樂檔有更動，重新用 ffmpeg 轉壓 128kbps 放進 `music/`
3. `git add` → `git commit` → `git push origin main`

## 現場使用提醒

- 需要場館 WiFi 連線載入（建議到場後先用 iPad 開一次網址，確認能順利載入，尤其是音樂檔較大的段落）
- 遙控器／翻頁筆：多數透過模擬鍵盤方向鍵運作，iPad 需先用藍牙配對；務必活動前實際測試一次，確認遙控器能正常翻頁
- iPad 接 HDMI：用對應的轉接頭（Lightning/USB-C to HDMI），畫面會直接鏡像到投影幕，Safari 開啟網址即可
