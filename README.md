# 回憶桌布 · MemoryWallpaper

將照片與影片化為 Mac 桌面上的回憶。**v0.7.0 Beta｜macOS 13+｜Apple Silicon（M1 或更新晶片）**

[下載測試版](https://github.com/YenLin1988/MemoryWallpaper/releases/tag/v0.7.0-beta.1) · [回報問題與建議](https://github.com/YenLin1988/MemoryWallpaper/issues)

**Windows 使用者：** [Windows 11 x64 預覽版下載與限制](WINDOWS.md)。此版尚未 Windows 實機驗證，功能與 Mac 版不同。

本專案僅提供安裝檔、使用說明與回饋管道，**不公開原始碼**。Release 的「Source code」壓縮檔僅包含本專案的說明文件，請下載 `.dmg` 安裝檔。

## 安裝

1. 下載 `MemoryWallpaper-0.7.0-beta.1-macOS-arm64.dmg`。
2. 開啟映像檔，將「MemoryWallpaper」拖到 Applications。
3. 從「應用程式」開啟回憶桌布，匯入自己的照片或影片。

**此測試版使用臨時簽章，尚未 Apple Developer ID 簽章與公證。** macOS 可能阻擋開啟。確認下載來源後，可依系統提示在「系統設定 → 隱私權與安全性」選擇「仍要打開」（若系統提供）。若仍無法開啟，請回報錯誤訊息；不需要關閉系統安全防護。Intel Mac 不支援本次安裝包。

## 功能

- 原生照片牆、人物標記、收藏、播放清單、搜尋與照片資訊。
- 照片依序／隨機播放，最短 15 秒；影片可播完整支再切換。
- 直式照片使用同張照片放大與柔化作為背景。
- 十種轉場與隨機模式，多螢幕播放。
- 拍攝日期排序、年份月份篩選、往年今日、方向與尺寸篩選。
- 繁體中文、简体中文、日本語、English、한국어。
- 資料夾匯入、重複素材辨識、節能與登入啟動選項。

## Google 相簿：進階測試功能

本機匯入不需要 Google 帳號。Google Picker 匯入目前需要使用者自行建立 Google Cloud 專案、啟用 Photos Picker API、建立桌面 OAuth 用戶端並配置測試帳號，再於 App 中選取 OAuth JSON。此版本未提供所有人可直接使用的共用正式 Google 登入。

只匯入使用者主動選取的照片及已儲存影片，不會自動同步完整相簿、Google 人物名稱或 Google 回憶推薦。請勿在 Issues 上傳 OAuth JSON、權杖或私人照片。

## 已知限制

- Beta 尚未完成不同 Mac 機型與長時間使用的全面驗證。
- 暫停後恢復影片會從該影片開頭播放。
- 影片的柔化背景使用靜態影格。
- 全螢幕暫停以視窗大小判斷，最大化視窗也可能觸發。
- 匯入會保存本機副本，請預留磁碟空間；移出清單不會刪除原始照片。

## 回饋

請透過 Issues 選擇「錯誤回報」或「功能建議」。回報時提供 App 版本、macOS 版本、Mac 晶片及重現步驟；截圖請先遮蔽個人資訊。

[隱私說明](PRIVACY.md) · [使用條款](TERMS.md)
