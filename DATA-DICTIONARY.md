# 資料字典 / Data dictionary

book.json為固定文字主本。pages[]按25個官方影像幀排列，page_id為fNNN；unit ID前綴pNN是44個編號物理面。左右side是觀看全幅影像的左右，與紙面讀序分開。methods.physical_faces保存全部44面的原稿metadata、layer_states、gaps及notes，units之外的原稿欄位逐項不改；原稿unit order由所屬物理面的陣列順序表示。

units[].id保留原稿識別碼；layer由faithful映為original-print；role保留原稿role；text保留精確字串；side保留物理面所在側；bbox在core為null。原稿非null bbox移至source-regions.json的unit_source_regions，以unit_id對應，座標原值照存，不推定未宣告的座標制或逐字幾何。

本版role實際統計：{"body": 365, "byline": 2, "figure-label": 47, "heading": 1, "other-original-paratext": 4, "printed-page-number": 30, "running-title": 22, "title": 1}。

uncertainties.json為展平疑讀。page_id指fNNN，unit_id指pNN單位；start/end為Unicode碼點0起半開區間[start,end)，surface必須精確等於text[start:end]。extent=known只表示已知target位置，並非讀法確定。candidates與reason保留原稿；methods.uncertainty_declarations保留原始target及可選0起算occurrence_index。

source-regions.json的unresolved_source_regions保存已查看、文字或歸頁尚未確定的來源邊區，提供page_id、frame、side、原圖URL與hash、bbox、extent、reason及必要的unit_id，不含私人路徑或裁片。page_id保留來源記錄的定位錨點，不表示邊條文字已裁定屬於該頁；不能一概稱其文字不可辨。extent=unknown不宣稱字數或所有原字已收錄；bbox與碼點範圍不是同一種座標。unit_source_regions保留原稿非null unit bbox。未宣告座標制時不得自行解讀為xyxy或xywh。

source-pages.json與book.pages逐幀對應，提供URL、canvas、固定來源影像SHA-256、實際width/height及manifest_width/manifest_height；images_redistributed=false。實際像素尺寸不由manifest換算猜出。

metrics.codepoints是所有unit精確字串的Unicode碼點數，含空白與點號，不等於漢字數、排印字數或字形數。uncertainty_records是紀錄數，不等於疑字數或錯誤率。空白、未知、未量測與零分開。

TEI的ab與TXT的導航單位均為JSON單位的逐一投影；TEI xml:lang=lzh，英文說明語言為en／eng。TEI不是完整校勘app、逐字幾何或原書版面摹本。SCHEMA.json描述book.json；其他檔案的欄位語義由本字典補充。

