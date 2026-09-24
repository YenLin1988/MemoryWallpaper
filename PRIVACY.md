# 隱私說明

適用於 MemoryWallpaper v0.7.0 Beta，更新日期：2026-09-24。

照片與影片匯入副本、手動人物標記、收藏和播放設定保存在本機 `~/Library/Application Support/MemoryWallpaper/`。本版本不提供開發者伺服器分析或自動上傳素材功能。

使用 Google 匯入時，App 會與 Google OAuth、Photos Picker 及媒體下載服務通訊，只下載使用者選取的素材。OAuth 用戶端設定保存在本機；存取權杖僅保留於記憶體，不保存 refresh token。Google 服務適用其自身隱私政策。

本機素材不供廣告、出售或模型訓練。Google API 資料使用遵守 Google API Services User Data Policy，包括 Limited Use 要求。

退出 App 後刪除上述資料夾，可清除本機匯入副本與設定；此操作不可復原，請先備份需要保留的檔案。原始來源照片不會因此刪除。Google 授權可在 Google 帳戶的第三方連結管理頁撤銷。

GitHub Issues 是公開的，請勿提交私人照片、OAuth JSON、帳號憑證或未遮蔽的個人資訊。隱私相關一般問題可在本專案 Issues 提出，勿附敏感資料。

## Windows 預覽版

Windows 0.1 預覽版的本機資料位於 `%LOCALAPPDATA%\MemoryWallpaper`，尚無 Google 匯入。卸載不移除個人素材與設定。詳見 [Windows 說明](WINDOWS.md)。
