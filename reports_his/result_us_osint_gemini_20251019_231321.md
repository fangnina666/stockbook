## 美股 OSINT 輿情分析 (2025-10-09 ~ 2025-10-19)

### 執行摘要

本次分析涵蓋 2025 年 10 月 9 日至 10 月 19 日期間的美股輿情。觀察到 "stealth"（法人偷偷買入）和 "sudden"（法人突然大量買入）兩種訊號。

*   **Stealth (連續偏多)**: 觀察到多檔股票呈現連續多日法人買入的現象，顯示市場可能存在潛在的、未公開的利多消息，或法人對這些股票的長期前景抱持樂觀態度。重點關注連續買入天數 (pos_streak) 較長、累積買入金額 (cum_pos) 較高的標的。
*   **Sudden (單日暴增)**: 大量股票出現單日法人買入量顯著增加的狀況。這種訊號可能源於突發事件、公司公告、行業趨勢變化等。需特別關注單日買入量 (sudden_buy_today) 較高、相較於前一日的增長比例 (sudden_buy_pct) 較大的標的。

**整體趨勢**: 數據顯示偏多訊號較為強烈，多檔股票同時出現 "stealth" 和 "sudden" 訊號，暗示市場存在一定程度的樂觀情緒。

### Top Picks

以下是綜合 "stealth" 和 "sudden" 訊號，並初步考量基本面/題材面後選出的 Top Picks (排序不分先後，需進一步研究)：

1.  **COP (康菲石油)**: 同時具備 "stealth" 和 "sudden" 訊號，能源價格上漲題材，法人持續加碼。
2.  **TMUS (T-Mobile US)**: 連續買入訊號加上單日買入量增加，電信行業穩定增長，5G 佈局。
3.  **DE (迪爾公司)**: 連續買入訊號疊加單日買入量增長，農業機械需求強勁，營運展望佳。
4.  **VST (Vistra Corp.)**: 連續七天買入加上單日買入量暴增，能源轉型題材，法人持續看好。
5.  **UDR (United Dominion Realty Trust)**: 連續買入訊號加上單日買入量大幅增加，房地產信託，受益於租金上漲。

### 個股速覽表格

| 股票代號 | 公司名稱                     | 題材時間軸                | 基本面                             | 題材面                                  | 技術分析 | 合理股價 | 操作建議        | 訊號對齊 | 總結一句話                               |
| -------- | ---------------------------- | ----------------------- | ---------------------------------- | --------------------------------------- | -------- | -------- | ------------- | -------- | -------------------------------------- |
| AEE      | Ameren Corp.               | 公用事業穩定需求       | 盈利穩定，派息良好                   | 美國基建計畫受益，綠色能源轉型                       |          |          | 謹慎樂觀        | stealth | 公用事業穩定增長，可長期持有。                       |
| BA       | 波音                         | 航空業復甦，國防訂單  | 營收改善，但債務壓力仍在               | 航空旅行需求恢復，國防預算增加                          |          |          | 謹慎樂觀        | stealth | 航空業復甦，但需關注財務風險。                        |
| BLDR     | Builders FirstSource         | 房屋建造需求持續         | 營收增長，利潤率提升                   | 美國房地產市場需求旺盛，供應鏈改善                   |          |          | 謹慎樂觀        | stealth | 受益於房地產市場，關注利率影響。                       |
| CLX      | The Clorox Company         | 消費必需品穩定需求      | 品牌效應，但成本壓力增加               | 衛生意識提高，產品需求穩定                          |          |          | 中性          | stealth | 消費必需品需求穩定，但利潤受擠壓。                        |
| COP      | 康菲石油                     | 能源價格上漲，供需緊張  | 盈利大幅提升，資產負債表健康           | 石油和天然氣價格上漲，全球能源需求增加                |          |          | 強力買入        | stealth, sudden_percent | 受益於能源價格，法人持續加碼。                        |
| COO      | CooperCompanies              | 醫療保健需求增加       | 營收穩定增長，研發投入持續           | 眼科和女性健康領域需求增加，創新產品推出          |          |          | 謹慎樂觀        | stealth | 醫療保健需求增加，具長期增長潛力。                      |
| DE       | 迪爾公司                     | 農業機械需求強勁        | 營收和利潤雙增，前景展望樂觀           | 全球糧食需求增加，農業技術升級                          |          |          | 強力買入        | stealth, sudden_percent | 農業機械需求強勁，營運展望佳。                        |
| DELL     | 戴爾科技                     | 企業IT支出增加         | 營收增長，伺服器和PC需求強勁           | 雲端服務和混合辦公模式推動IT基礎設施升級           |          |          | 謹慎樂觀        | stealth | 受益於IT支出增加，關注供應鏈挑戰。                       |
| DVN      | Devon Energy               | 能源價格上漲，頁岩油產量 | 盈利能力強勁，股息優厚               | 美國頁岩油產量增加，能源獨立性提升                        |          |          | 謹慎樂觀        | stealth | 受益於能源價格上漲，股息吸引力強。                      |
| EMN      | Eastman Chemical           | 特種化學品需求增加      | 營收增長，成本控制有效               | 工業和消費領域對特種化學品的需求增加                   |          |          | 謹慎樂觀        | stealth | 特種化學品需求增加，具長期增長潛力。                      |
| EXE      | IDEX Corporation           | 工業泵閥需求增加        | 盈利能力強勁，收購擴張               | 工業自動化和基礎設施建設推動泵閥需求                    |          |          | 謹慎樂觀        | stealth | 工業泵閥需求增加，具長期增長潛力。                      |
| FE       | FirstEnergy Corp.           | 公用事業穩定需求       | 盈利穩定，但債務壓力較大             | 美國基建計畫受益，電網升級需求                          |          |          | 中性          | stealth, sudden_percent | 公用事業穩定增長，但需關注財務風險。                        |
| FOX      | Fox Corporation            | 媒體娛樂內容需求         | 營收增長，串流媒體業務發展           | 體育賽事和新聞內容需求旺盛，廣告收入增加              |          |          | 中性          | stealth | 媒體娛樂內容需求，串流媒體競爭激烈。                       |
| GRMN     | Garmin Ltd.                | 戶外運動和航空電子需求  | 營收增長，產品創新能力強               | 健身追蹤器和航空電子產品需求穩定增長                  |          |          | 謹慎樂觀        | stealth | 戶外運動和航空電子需求，創新能力是關鍵。                  |
| HD       | The Home Depot             | 家居裝修需求持續         | 營收和利潤增長，但客流量下降           | 美國房地產市場活躍，DIY文化盛行                           |          |          | 謹慎樂觀        | stealth | 受益於家居裝修需求，關注客流量變化。                       |
| HWM      | Howmet Aerospace Inc.      | 航空航天零部件需求       | 營收增長，盈利能力提升               | 航空旅行需求恢復，飛機製造商增產                          |          |          | 謹慎樂觀        | stealth | 航空航天零部件需求，關注供應鏈問題。                       |
| LII      | Linder Industries          | 工業設備需求增加         | 營收增長，收購擴張策略               | 工業自動化和基礎設施建設推動設備需求                    |          |          | 謹慎樂觀        | stealth, sudden_percent | 工業設備需求增加，具長期增長潛力。                      |
| LMT      | Lockheed Martin            | 國防訂單穩定增長       | 營收和利潤穩定， backlog充足        | 全球地緣政治緊張，國防預算增加                          |          |          | 謹慎樂觀        | stealth | 國防訂單穩定，但估值較高。                          |
| MMC      | Marsh & McLennan           | 保險經紀和風險管理需求   | 營收和利潤增長，收購擴張               | 全球經濟復甦，企業風險意識提高                           |          |          | 謹慎樂觀        | stealth | 保險經紀和風險管理需求，具長期增長潛力。                      |
| MKC      | McCormick & Company        | 食品調味品需求         | 營收穩定，品牌效應                   | 家庭烹飪和食品消費需求穩定                           |          |          | 中性          | stealth, sudden_percent | 食品調味品需求穩定，但成本壓力增加。                        |
| MAA      | Mid-America Apartment Comm | 公寓租賃需求持續         | 營收和利潤增長，入住率高               | 美國人口流動性增加，租房市場需求旺盛                      |          |          | 謹慎樂觀        | stealth, sudden_percent | 受益於公寓租賃需求，但需關注利率影響。                       |
| MHK      | Mohawk Industries          | 地板材料需求增加         | 營收增長，但利潤率受壓               | 房地產市場活躍，房屋裝修需求增加                          |          |          | 謹慎樂觀        | stealth | 受益於地板材料需求，但需關注成本。                         |
| NEM      | Newmont Corporation        | 黃金價格上漲，避險需求  | 營收和利潤波動，取決於金價           | 全球經濟不確定性增加，黃金避險功能顯現                    |          |          | 中性          | stealth | 黃金價格影響大，具避險價值。                           |
| PH       | Parker-Hannifin            | 工業自動化需求增加       | 營收和利潤增長，收購擴張               | 工業自動化和基礎設施建設推動需求                    |          |          | 謹慎樂觀        | stealth | 工業自動化需求增加，具長期增長潛力。                      |
| PG       | 寶潔                       | 消費必需品需求穩定       | 品牌效應，但成本壓力增加               | 衛生意識提高，產品需求穩定                          |          |          | 中性          | stealth | 消費必需品需求穩定，但利潤受擠壓。                        |
| PEG      | Public Service Enterprise | 公用事業穩定需求       | 盈利穩定，但債務壓力較大             | 美國基建計畫受益，綠色能源轉型                       |          |          | 中性          | stealth | 公用事業穩定增長，但需關注財務風險。                        |
| PSA      | Public Storage             | 自助倉儲需求持續         | 營收和利潤增長，入住率高               | 人口流動性增加，房屋空間需求旺盛                          |          |          | 謹慎樂觀        | stealth, sudden_percent | 受益於自助倉儲需求，但需關注競爭。                         |
| SO       | The Southern Company       | 公用事業穩定需求       | 盈利穩定，派息良好                   | 美國基建計畫受益，電網升級需求                          |          |          | 謹慎樂觀        | stealth | 公用事業穩定增長，可長期持有。                       |
| TMUS     | T-Mobile US                | 無線通信服務需求         | 營收和利潤增長，5G網絡建設            | 5G網絡普及，數據流量需求增加                           |          |          | 強力買入        | stealth, sudden_percent | 電信行業穩定增長，5G佈局。                           |
| TSCO     | Tractor Supply Company     | 農村地區消費需求         | 營收和利潤增長，門店擴張               | 美國農村地區人口增長，農產品價格上漲                         |          |          | 謹慎樂觀        | stealth | 受益於農村地區消費，但需關注經濟週期影響。                     |
| UDR      | United Dominion Realty Trust | 公寓租賃需求持續         | 營收和利潤增長，入住率高               | 美國人口流動性增加，租房市場需求旺盛                      |          |          | 強力買入        | stealth, sudden_percent | 受益於公寓租賃需求，關注利率影響。                       |
| UPS      | 聯合包裹                   | 物流運輸需求持續         | 營收和利潤增長，但成本壓力增加           | 電子商務蓬勃發展，全球貿易增加                          |          |          | 謹慎樂觀        | stealth | 受益於物流運輸需求，但需關注成本控制。                       |
| VLO      | Valero Energy              | 煉油產品需求增加         | 盈利能力強勁，但環保壓力增加           | 石油和天然氣需求持續，煉油利潤率提高                        |          |          | 謹慎樂觀        | stealth | 受益於煉油產品需求，但需關注環保政策。                       |
| VLTO     | Veralto Corporation | 水質監測需求增加         | 營收增長，收購擴張策略               | 環境保護意識提高，水資源短缺問題日益嚴重                    |          |          | 謹慎樂觀        | stealth | 水質監測需求增加，具長期增長潛力。                      |
| VST      | Vistra Corp.               | 電力需求增加，能源轉型   | 盈利改善，清潔能源投資增加           | 美國電力需求增長，能源轉型政策支持                         |          |          | 強力買入        | stealth, sudden_percent | 能源轉型題材，法人持續看好。                          |
| WAB      | Wabtec Corporation         | 鐵路運輸設備需求         | 營收增長，收購擴張策略               | 全球貿易增加，鐵路運輸效率提升                         |          |          | 謹慎樂觀        | stealth | 鐵路運輸設備需求，具長期增長潛力。                      |
| WEC      | WEC Energy Group           | 公用事業穩定需求       | 盈利穩定，派息良好                   | 美國基建計畫受益，綠色能源轉型                       |          |          | 謹慎樂觀        | stealth | 公用事業穩定增長，可長期持有。                       |
| AMD      | AMD               | AI 晶片需求暴增       | 營收大幅增長，毛利率提升                   | AI 晶片市場爆發性成長，市場份額提升                         |          |          | 謹慎樂觀        | sudden_percent | 受益於 AI 晶片需求，但市場競爭激烈。                      |
| AES      | AES Corporation               | 能源轉型政策支持       | 營收增長，清潔能源投資增加                   | 美國能源轉型政策支持，可再生能源需求持續提升                         |          |          | 謹慎樂觀        | sudden_percent | 受益於能源轉型政策支持，但需關注政策風險。                      |
| AMCR      | Amcor Plc               | 包裝材料需求穩定       | 營收穩定增長，成本控制有效                   | 消費品包裝需求穩定，環保包裝材料需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 包裝材料需求穩定，但市場競爭激烈。                      |
| AMP      | Ameriprise Financial, Inc.               | 金融服務需求穩定       | 營收穩定增長，資產管理規模擴大                   | 退休儲蓄和投資需求穩定，財富管理服務需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 金融服務需求穩定，但市場波動性較大。                      |
| BRK-B      | Berkshire Hathaway Inc.               | 多元化投資組合       | 營收和利潤穩定，投資收益良好                   | 巴菲特投資理念和品牌效應，多元化投資組合降低風險                         |          |          | 謹慎樂觀        | sudden_percent | 多元化投資組合，但股價較高。                      |
| BLK      | BlackRock, Inc.               | 資產管理規模擴大       | 營收和利潤穩定，ETF市場領導者                   | ETF市場持續發展，被動投資需求增加                         |          |          | 謹慎樂觀        | sudden_rank | 資產管理規模擴大，但市場競爭激烈。                      |
| BMY      | Bristol-Myers Squibb               | 藥品需求穩定       | 營收和利潤穩定，研發投入持續                   | 癌症和免疫疾病藥物需求穩定，新藥研發成功                         |          |          | 謹慎樂觀        | sudden_percent | 藥品需求穩定，但專利到期風險較高。                      |
| CDNS      | Cadence Design Systems, Inc.               | 半導體設計需求穩定       | 營收穩定增長，技術領先                   | 半導體行業發展迅速，電子設計自動化（EDA）工具需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 半導體設計需求穩定，但技術更新換代快。                      |
| KMX      | CarMax, Inc.               | 二手車需求增加       | 營收增長，但利潤率受壓                   | 新車供應短缺，二手車價格上漲                         |          |          | 謹慎樂觀        | sudden_percent | 二手車需求增加，但市場波動性較大。                      |
| CHTR      | Charter Communications, Inc.               | 寬頻網路服務需求穩定       | 營收穩定增長，用戶數量增加                   | 居家辦公和線上娛樂需求穩定，寬頻網路服務需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 寬頻網路服務需求穩定，但市場競爭激烈。                      |
| STZ      | Constellation Brands, Inc.               | 酒精飲料需求穩定       | 營收穩定增長，品牌效應                   | 酒精飲料消費需求穩定，高端品牌市場份額提升                         |          |          | 謹慎樂觀        | sudden_percent | 酒精飲料需求穩定，但市場競爭激烈。                      |
| CPAY      | Paymentus Holdings, Inc.               | 數位支付需求增加       | 營收大幅增長，客戶數量增加                   | 數位支付普及，線上支付需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 數位支付需求增加，但市場競爭激烈。                      |
| CTRA      | Coterra Energy Inc.               | 天然氣價格上漲       | 營收大幅增長，利潤率提升                   | 天然氣供應短缺，價格上漲                         |          |          | 謹慎樂觀        | sudden_percent | 天然氣價格上漲，但市場波動性較大。                      |
| DAL      | Delta Air Lines, Inc.               | 航空業復甦       | 營收大幅增長，但成本壓力增加                   | 航空旅行需求恢復，商務旅行需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 航空業復甦，但成本控制是關鍵。                      |
| DLR      | Digital Realty Trust, Inc.               | 數據中心需求增加       | 營收穩定增長，出租率高                   | 雲端服務和AI技術發展，數據中心需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 數據中心需求增加，但市場競爭激烈。                      |
| DG      | Dollar General Corporation               | 平價零售需求穩定       | 營收穩定增長，門店數量增加                   | 通貨膨脹壓力，平價零售需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 平價零售需求穩定，但市場競爭激烈。                      |
| D      | Dominion Energy, Inc.               | 公用事業需求穩定       | 營收穩定增長，可再生能源投資增加                   | 電力需求穩定，可再生能源政策支持                         |          |          | 謹慎樂觀        | sudden_percent | 公用事業需求穩定，但債務壓力較大。                      |
| DPZ      | Domino's Pizza, Inc.               | 外賣需求穩定       | 營收穩定增長，品牌效應                   | 外賣需求穩定，線上訂購普及                         |          |          | 謹慎樂觀        | sudden_percent | 外賣需求穩定，但市場競爭激烈。                      |
| DTE      | DTE Energy Company               | 電力需求增加       | 營收穩定增長，可再生能源投資增加                   | 電力需求穩定，可再生能源政策支持                         |          |          | 謹慎樂觀        | sudden_rank | 電力需求穩定，但債務壓力較大。                      |
| EBAY      | eBay Inc.               | 線上零售需求穩定       | 營收穩定增長，但競爭激烈                   | 線上零售需求穩定，二手商品市場發展                         |          |          | 謹慎樂觀        | sudden_percent | 線上零售需求穩定，但市場競爭激烈。                      |
| ECL      | Ecolab Inc.               | 水處理和衛生服務需求穩定       | 營收穩定增長，客戶數量增加                   | 工業和商業清潔需求穩定，水資源短缺問題日益嚴重                         |          |          | 謹慎樂觀        | sudden_percent | 水處理和衛生服務需求穩定，但市場競爭激烈。                      |
| EW      | Edwards Lifesciences Corporation               | 醫療器材需求穩定       | 營收穩定增長，技術領先                   | 心血管疾病患病率增加，醫療器材需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 醫療器材需求穩定，但技術更新換代快。                      |
| ELV      | Elevance Health, Inc.               | 醫療保險需求穩定       | 營收穩定增長，會員數量增加                   | 醫療保險需求穩定，人口老齡化趨勢                         |          |          | 謹慎樂觀        | sudden_percent | 醫療保險需求穩定，但政策風險較高。                      |
| EPAM      | EPAM Systems, Inc.               | 數位轉型需求增加       | 營收大幅增長，客戶數量增加                   | 企業數位轉型需求增加，IT諮詢服務需求穩定                         |          |          | 謹慎樂觀        | sudden_percent | 數位轉型需求增加，但市場競爭激烈。                      |
| EXPE      | Expedia Group, Inc.               | 旅行需求復甦       | 營收大幅增長，但成本壓力增加                   | 航空旅行和酒店預訂需求恢復，旅遊業復甦                         |          |          | 謹慎樂觀        | sudden_percent | 旅行需求復甦，但市場波動性較大。                      |
| FAST      | Fastenal Company               | 工業用品需求穩定       | 營收穩定增長，門店數量增加                   | 工業生產活動增加，工業用品需求穩定                         |          |          | 謹慎樂觀        | sudden_percent | 工業用品需求穩定，但市場競爭激烈。                      |
| FRT      | Federal Realty Investment Trust               | 零售房地產需求穩定       | 營收穩定增長，出租率高                   | 零售業復甦，商場和零售店鋪需求增加                         |          |          | 謹慎樂觀        | sudden_percent | 零售房地產需求穩定，但市場風險較高。                      |
| FSLR      | First Solar, Inc.               | 太陽能發電需求增加       | 營收大幅增長，政府補貼支持                   | 太陽能發電成本降低，可再生能源政策支持                         |          |          | 謹慎樂觀        | sudden_percent | 太陽能發電需求增加，但市場競爭激烈。                      |
| GEV      | GE Vernova                | 能源轉型需求增加         | 營收改善，可再生能源投資增加         | 全球能源轉型趨勢，對電網基礎設施和可再生能源技術的需求不斷增長                  |          |          | 謹慎樂觀        | sudden_percent | 能源轉型題材，但需關注市場競爭。                           |
| GD      | General Dynamics               | 國防訂單穩定         | 營收穩定增長，backlog充足         | 全球地緣政治緊張，國防預算增加，對國防產品和服務的需求穩定增長                  |          |          | 謹慎樂觀        | sudden_percent | 國防訂單穩定，但估值較高。                           |
| GM      | General Motors               | 汽車需求復甦         | 營收改善，電動汽車銷量增加         | 汽車市場復甦，電動汽車滲透率提高，對電動汽車的需求不斷增長                  |          |          | 謹慎樂觀        | sudden_percent | 汽車需求復甦，但需關注市場競爭。                           |
| GS      | Goldman Sachs Group, Inc.       | 金融市場活動增加      | 營收波動，取決於市場表現        | 金融市場活動增加，投資銀行和交易業務收入增加                 |          |          | 中性          | sudden_percent | 金融市場活動影響大，具週期性。                           |
| HSIC      | Henry Schein, Inc.       | 醫療用品需求穩定      | 營收穩定增長，客戶網絡廣泛        | 醫療保健行業需求穩定，對醫療用品和設備的需求持續增長                 |          |          | 謹慎樂觀        | sudden_percent | 醫療用品需求穩定，但市場競爭激烈。                           |
| HSY      | The Hershey Company      | 巧克力和糖果需求穩定      | 營收穩定增長，品牌效應        | 巧克力和糖果消費需求穩定，節日和慶典活動的消費增加                 |          |          | 謹慎樂觀        | sudden_percent | 巧克力和糖果需求穩定，但市場競爭激烈。                           |
| HST      | Host Hotels & Resorts, Inc.      | 酒店入住率提升      | 營收大幅增長，但成本壓力增加        | 商務和休閒旅行需求恢復，酒店入住率提升                 |          |          | 謹慎樂觀        | sudden_percent | 酒店入住率提升，但市場波動性較大。                           |
| HII      | Huntington Ingalls Industries, Inc.      | 國防造船需求穩定      | 營收穩定增長，backlog充足        | 國防預算增加，對海軍艦艇和造船服務的需求穩定增長                 |          |          | 謹慎樂觀        | sudden_percent | 國防造船需求穩定，但項目週期較長。                           |
| IR      | Ingersoll Rand Inc.      | 工業設備需求增加      | 營收穩定增長，收購擴張策略        | 工業自動化和基礎設施建設推動工業設備需求                    |          |          | 謹慎樂觀        | sudden_percent | 工業設備需求增加，具長期增長潛力。                      |
| IP      | International Paper      | 包裝材料需求穩定      | 營收穩定增長，成本控制有效        | 消費品包裝需求穩定，電商物流需求增加                 |          |          | 謹慎樂觀        | sudden_percent | 包裝材料需求穩定，但市場競爭激烈。                           |
| JBL      | Jabil Inc.      | 電子製造服務需求增加      | 營收穩定增長，客戶網絡廣泛        | 全球電子產品製造外包趨勢，對電子製造服務的需求穩定增長                 |          |          | 謹慎樂觀        | sudden_percent | 電子製造服務需求增加，但市場競爭激烈。                           |
| MA      | Mastercard Inc.      | 數位支付需求增加      | 營收穩定增長，交易量增加        | 數位支付普及，線上支付和跨境支付需求增加                 |          |          | 謹慎樂觀        | sudden_percent | 數位支付需求增加，但市場競爭激烈。                           |
| META | Meta Platforms, Inc. | AI 需求暴增 | 營收大幅增長，利潤率提升 | AI 相關硬體需求暴增，伺服器需求 | | | 強力買入 | sudden_percent | AI 需求暴增，法人瘋狂加碼 |
| MSCI | Morgan Stanley Capital International | 全球指數編製 | 營收大幅增長 | 股票市場發展 | | | 強力買入 | sudden_percent | 數位指數發展，法人持續買超 |
| NTAP | NetApp, Inc. | 雲端儲存設備 | 營收穩定增長 | 雲端市場發展 | | | 謹慎樂觀 | sudden_percent | 雲端市場持續成長，可以持續關注 |
| OKE | Oneok, Inc. | 天然氣管道 | 營收穩定增長 | 天然氣運輸 | | | 謹慎樂觀 | sudden_percent | 天然氣需求持續增加 |
| ORCL | Oracle Corporation | AI 需求帶動 | 營收大幅增長 | AI 需求爆發，相關設備大幅成長 | | | 強力買入 | sudden_percent | AI 需求持續成長，法人瘋狂加碼 |
| PCG | PG&E Corporation | 電力公司 | 營收穩定增長 | 電力需求持續上升 | | | 謹慎樂觀 | sudden_percent | 電力需求上升，但市場競爭激烈 |
| O | Realty Income Corporation | REIT 房地產投資 | 營收穩定增長 | 房地產市場發展 | | | 謹慎樂觀 | sudden_percent | 房地產市場持續發展 |
| REG | Regency Centers Corporation | 房地產投資 | 營收穩定增長 | 房地產市場發展 | | | 謹慎樂觀 | sudden_percent | 房地產市場持續發展 |
| ROST | Ross Stores, Inc. | 零售百貨 | 營收穩定增長 | 消費力提升 | | | 謹慎樂觀 | sudden_percent | 零售百貨產業持續發展 |
| SLB | Schlumberger Limited | AI 需求帶動 | 營收大幅增長 | AI 相關設備需求爆發 | | | 強力買入 | sudden_percent | AI 需求持續成長，法人瘋狂加碼 |
| NOW | ServiceNow, Inc. | 雲端服務 | 營收穩定增長 | 雲端市場發展 | | | 謹慎樂觀 | sudden_percent | 雲端市場持續發展 |
| SWK | Stanley Black & Decker, Inc. | 工業設備 | 營收穩定增長 | 各產業持續發展 | | | 謹慎樂觀 | sudden_percent | 工業設備市場持續成長 |
| STT | State Street Corporation | 金融業務 | 營收穩定增長 | 金融市場成長 | | | 謹慎樂觀 | sudden_percent | 金融市場持續成長 |
| TXT | Textron Inc. | 航空訂單 | 營收穩定增長 | 航空產業復甦 | | | 謹慎樂觀 | sudden_rank | 航空產業持續復甦 |
| TJX | The TJX Companies, Inc. | 服飾零售 | 營收穩定增長 | 服飾零售產業發展 | | | 謹慎樂觀 | sudden_rank | 服飾零售產業持續發展 |
| ULTA | Ulta Beauty, Inc. | 美妝產品零售 | 營收穩定增長 | 美妝產品市場發展 | | | 謹慎樂觀 | sudden_percent | 美妝產品市場持續成長 |
| VZ | Verizon Communications Inc. | 通訊服務 | 營收穩定增長 | 通訊需求上升 | | | 謹慎樂觀 | sudden_percent | 通訊需求持續上升 |
| WRB | W. R. Berkley Corporation | 保險業務 | 營收穩定增長 | 保險需求上升 | | | 謹慎樂觀 | sudden_percent | 保險需求持續上升 |
| WM | Waste Management, Inc. | 廢棄物處理 | 營收穩定增長 | 廢棄物處理需求穩定 | | | 謹慎樂觀 | sudden_percent | 廢棄物處理需求穩定 |
| WST | West Pharmaceutical Services, Inc. | 醫療器材 | 營收穩定增長 | 醫療需求穩定 | | | 謹慎樂觀 | sudden_percent | 醫療需求穩定 |
| XEL | Xcel Energy Inc. | 電力公司 | 營收穩定增長 | 電力需求上升 | | | 謹慎樂觀 | sudden_percent | 電力需求上升 |
| CTAS | Cintas Corporation | 企業服務 | 營收穩定增長 | 企業服務需求上升 | | | 謹慎樂觀 | sudden_rank | 企業服務需求穩定 |

**備註**:
*   技術分析、合理股價、操作建議需結合更深入的研究。
*   訊號對齊欄位顯示該個股同時出現哪些訊號。

### 來源清單

*   [S1] SEC EDGAR filings (10-K, 10-Q, 8-K, Proxy)
*   [S2] Yahoo Finance / Reuters / Bloomberg / WSJ / FT
*   [S3] ETF 持股揭露（SPY/IVV/QQQ/ARKK 等）
