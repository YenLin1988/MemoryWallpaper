# 回憶桌布 Windows 0.1.0 Preview

[下載 Windows 安裝程式](https://github.com/YenLin1988/MemoryWallpaper/releases/tag/windows-v0.1.0-preview.1)

**Windows 11 · Intel／AMD x64 · 實驗性預覽版，尚未完成 Windows 實機驗證。**

## 安裝與使用

1. 下載 `MemoryWallpaper-0.1.0-preview.1-Windows-x64-Setup.exe`。
2. 執行安裝程式，完成後從開始功能表開啟 MemoryWallpaper。不需要管理員權限，不需要另裝 .NET。
3. 按「匯入照片／影片」，先選少量測試素材，再按「播放桌布」。
4. 按「停止桌布」或關閉主視窗會停止播放。睡眠時也會停止，喚醒後需手動播放。

安裝程式與 App 尚未數位簽章，Windows SmartScreen 可能阻擋。請確認來源與校驗碼，不需要關閉 Windows Defender。公司政策若禁止未簽章程式，請勿繞過限制。

## 已移植

- 本機照片／影片匯入、SHA-256 重複辨識、匯入副本保存。
- 照片牆、搜尋檔名及人物、手動人物標記、收藏。
- 照片拍攝日期排序、往年今日、橫式／直式篩選（依可讀取的照片 metadata）。
- 依序／隨機、上一張／下一張、照片最短 15 秒、影片播完再切換。
- 同張照片放大模糊背景，十種進場特效／隨機。
- 繁中、簡中、日文、英文、韓文介面。

## 與 Mac 版的差異

本版不是 Mac 0.7 的完整功能移植。尚無 Google 登入／Picker、播放清單、資料夾監看、系統匣、完整節能規則、多螢幕獨立播放、年月篩選及桌面日期顯示。

照片支援 JPG、PNG、BMP；尚不支援 HEIC。影片支援情況依 Windows 解碼器而定，MP4／MOV 並非所有編碼都可播放；影片不產生縮圖，邊緣為黑色，拍攝日期及尺寸尚未擷取。照片 EXIF 旋轉方向尚需實機確認。

桌面播放使用 Explorer 的非公開 WorkerW 機制，可能受 Windows 更新或其他桌布程式影響。找不到可用宿主時會報錯並停止。多螢幕目前共用桌面範圍，未提供獨立配置。

## 驗證狀態

已完成跨平台 Release 建置、自帶 .NET 執行環境的 x64 封裝、NSIS 安裝程式編譯、核心資料與隨機播放測試，以及原始碼／PDB 排除檢查。

**尚未在 Windows 電腦執行安裝程式或 App。** 首次啟動、桌面圖示層級、影片解碼、混合 DPI、休眠及 Explorer 重啟仍需實機測試；本版供願意協助測試的使用者下載。

## 資料與解除安裝

資料保存於 `%LOCALAPPDATA%\MemoryWallpaper`，本版沒有 Google 網路匯入。照片、標記及設定只存在本機；不提供開發者分析上傳。匯入會複製素材並佔用磁碟空間。

Windows「設定 → 應用程式」可移除程式；請先結束 App。解除安裝保留資料夾及素材。若要清除資料，備份後手動移除上述資料夾。原始來源檔不會被移除。

[回報錯誤](https://github.com/YenLin1988/MemoryWallpaper/issues) 時請提供 Windows 版本、CPU、螢幕配置與錯誤文字，並遮蔽私人內容。原始碼不公開；內含 .NET/WPF 的授權與第三方聲明隨程式提供。
