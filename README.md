## 📥 下載與使用方式

### 下載
- 在本頁右方 **Releases** 區塊，下載 `twitch_watcher.exe`  
- 下載後即可直接執行，無需安裝 Python  

### 使用方式
1. **準備憑證**  
   - 到 [Twitch Developer Console](https://dev.twitch.tv/console/apps) 建立一個 Application  
   - 複製 **Client ID** 與 **Client Secret**  

2. **啟動程式**  
   - 打開 `twitch_watcher.exe`  
   - 在介面上輸入 **Client ID** 與 **Client Secret**  
   - 自動取得Token
   - 如有過期請點擊「重新取得 Token」  

4. **加入頻道**  
   - 在輸入框輸入要追蹤的頻道名稱（例如：kspksp）  
   - 按下「加入」 → 頻道會出現在清單中  
   - 右側的「✕」按鈕可快速刪除頻道  

5. **設定檢查間隔**  
   - 可輸入「分鐘」與「秒」作為檢查時間（例如 `0 分 30 秒`）  

6. **開始監控**  
   - 按下「開始執行」後，程式會自動檢查  
   - 發現開播會立即自動打開瀏覽器觀看  

---

## ⚠ 注意事項
- 首次使用時必須輸入 **Client ID** 與 **Client Secret** 才能運作  
- 預設不會保存 Client Secret，下次啟動需重新輸入  
- 請不要設定過短的檢查間隔，避免超過 Twitch API 限制  
- 部分防毒軟體可能會誤判，請將程式加入白名單  
