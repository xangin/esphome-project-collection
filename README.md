# 🛠️ Xangin's ESPHome & IoT Project Collection

歡迎來到我的 IoT 專案集散地！👋

這裡彙整了我開發與維護的開源硬體專案，主要專注於 **ESPHome** 框架的應用、電子紙顯示器（E-Paper）驅動以及各品牌冷氣（HVAC）的智慧控制模組。所有的專案皆旨在讓智慧家庭（Home Assistant）整合變得更簡單、穩定。

如果你覺得這些專案對你有幫助，歡迎在個別專案頁面幫我按一顆星星 (⭐ Star)！

---

## 📂 專案目錄 (Project Categories)

### 📺 E-Paper 電子紙顯示系列
專注於低功耗資訊看板、氣象站與各式尺寸電子紙的 ESPHome 驅動整合。

| 專案名稱 | 說明 |
| :--- | :--- |
| **[eink-4c-dashboard](https://github.com/xangin/eink-4c-dashboard)** | 4色電子紙資訊儀表板設計，支援豐富色彩顯示。 |
| **[eink-weather-board](https://github.com/xangin/eink-weather-board)** | 專用氣象資訊顯示板，整合即時天氣資訊。 |
| **[esphome-eink-dashboard](https://github.com/xangin/esphome-eink-dashboard)** | 基於 ESPHome 的通用型電子紙儀表板配置。 |
| **[esphome_eink2.9_series](https://github.com/xangin/esphome_eink2.9_series)** | 針對 2.9 吋電子紙系列的驅動與應用範例。 |

### ❄️ 智慧冷氣控制系列 (Smart AC Control)
針對不同品牌冷氣通訊協定的 ESPHome 實作，讓傳統冷氣輕鬆接入 Home Assistant。

* **TaiSEIA 協定支援 (國際、日立)**
    * [TaiSEIA_ESPhome_samples](https://github.com/xangin/TaiSEIA_ESPhome_samples) - 支援台灣智慧能源產業協會 (TaiSEIA) 標準通訊協定的範例，目前適用台灣販售的國際與日立冷氣。

* **日本品牌支援**
    * [Daikin-ESPhome](https://github.com/xangin/Daikin-ESPhome) - 大金 (Daikin) 冷氣專用控制模組，基於 ESP32-C3 晶片設計。
    * [mhi-ac-ctrl-esp32-c3](https://github.com/xangin/mhi-ac-ctrl-esp32-c3) - 三菱重工 (Mitsubishi Heavy Industries) 冷氣控制，基於 ESP32-C3 晶片設計。
    * [MitsubishiCN105ESPHome](https://github.com/xangin/MitsubishiCN105ESPHome) - 三菱電機 (Mitsubishi Electric) CN105 介面專用控制，基於 ESP32-C3 晶片設計。

### 🔌 其他硬體應用 (Misc & Tools)
* [WT32-ETH01-esphome-pwm-fan-control](https://github.com/xangin/WT32-ETH01-esphome-pwm-fan-control) - 使用 WT32-ETH01 (乙太網路模組) 實現 PWM 風扇控制，適合需要有線網路穩定性的場景，如機櫃散熱。

---

## 🚀 如何使用 (How to use)

1. 點擊上方連結進入個別專案。
2. 參考各專案的 `README.md` 進行硬體接線與 YAML 設定。
3. 將配置刷入您的 ESP32 裝置。
4. 在 Home Assistant 中透過 ESPHome integration 新增裝置。

## 🤝 參與貢獻 (Contribution)

歡迎提交 Issue 回報問題，或發送 Pull Request 改進程式碼。如果您有特定型號的冷氣測試回饋，也非常歡迎分享！

## 📝 License

各專案授權條款請參閱個別儲存庫說明。

---
*Created by [xangin](https://github.com/xangin)*
