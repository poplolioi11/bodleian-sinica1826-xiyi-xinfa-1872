# 西醫新法（[1872]；Bodleian Sinica 1826） / Xi yi xin fa [New methods of Western medicine]: Transcription dataset

**v0.1.0｜AI初錄，保留疑讀。**

《西醫新法》（Xi yi xin fa）是一部討論外科與包紮的晚清漢譯醫學文獻，署「美國嘉約翰口譯」「莆田林湘東筆述」；Bodleian Libraries館藏Sinica 1826的官方固定書目供定刊地[Canton]、年代[1872]。本資料集以該館數位影像為底本，提供六面圖版、三十七面正文及一面原框正文空白面的原印文字初錄，並以TXT、JSON及TEI XML保存文字、疑讀與物理面／影像幀對應，供晚清外科與包紮漢譯詞彙、圖文關係及印刷史研究。本版為保留疑讀的AI初錄，尚未經人類全文雙校或專家審定。

現代資料整理者：曲宸宇（Chu, Chen-Yu；GitHub帳號poplolioi11；[ORCID](https://orcid.org/0009-0003-9738-6914)）。歷史口譯、筆述責任與現代整理者分開。

## 範圍與內容

底本為25幅官方影像幀中的44個編號物理面p[1]–p[44]：p[1]–p[6]為六面圖版，p[7]–p[43]為三十七面正文，p[44]保留原框而正文空白。原框空白面仍在範圍內；四個封面內外面另層排除。圖版中的字、圖說、書名、署名、版心及其他原印副文本依固定稿保存；不由圖像猜補未讀文字，也不重建圖形幾何。此範圍不證明原書全本完整。

固定初稿實際計數：472個單位、9100個Unicode碼點、69筆疑讀、15個已查看、文字或歸頁尚未確定的來源邊區；碼點數不是漢字數，疑讀數不是錯誤率。

[TXT](book.txt)、[JSON](book.json)、[TEI XML](book.tei.xml)、[來源影像索引](source-pages.json)、[疑讀](uncertainties.json)、[來源區域](source-regions.json)、[資料字典](DATA-DICTIONARY.md)、[文字政策](TRANSCRIPTION-POLICY.md)、[品質](QUALITY.md)、[方法](METHODS.md)、[訂正](CORRECTIONS.md)、[工程驗證](VALIDATION.json)、[權利](RIGHTS.md)與[引用資料](CITATION.cff)。英文說明見[README.en.md](README.en.md)。

## 底本與年代

官方固定書目原題「西醫新法」，拼音「xi yi xin fa」，作者欄「Kerr, John Glasgow」，責任題署「美國嘉約翰口譯」「莆田林湘東筆述」，供定刊地[Canton]、年代[1872]。方括號保留館目推定性質；封面手寫年份是後加層，不作原刊紀年。未核定原印刊記或出版者。英文方括號題名[New methods of Western medicine]是編者意譯，不冒稱館方正式英題。

- [Bodleian原件物件](https://digital.bodleian.ox.ac.uk/objects/d07550d1-b969-4d5a-a5f3-5bd10634b21c/)
- [官方IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/d07550d1-b969-4d5a-a5f3-5bd10634b21c.json)
- [官方固定XML書目](https://github.com/bodleian/east-asian-mss/blob/c177d5a6db8585168b744d38a6bff02186d1968f/collections/chinese/Sinica%201826.xml)

## 使用與品質

本版為AI初錄；尚未套用獨立讀圖，未經人類全文雙校、專家審定或同儕審查，未量測準確率。原點號可能為原刻或後加，尚未人工核定。JSON／TXT／TEI字串一致、schema、hash及格式通過，只證明工程性質，不證明讀字正確。已查看、文字或歸頁尚未確定的來源邊區保留unknown extent；部分問題是邊條屬本頁或鄰頁尚未裁定，不能一概稱其文字不可辨。不視為未處理，也不任造一個「□」代表未知長度；本資料集不表示所有邊區已完成歸頁或所有原字均已收錄。

本資源供歷史文獻研究，不提供臨床驗證或現代醫療操作依據；沒有進行生物研究。引用文字請連同版本、unit ID、物理面與官方影像核對。

不公開來源影像、裁片、專用程式、提示或完整私人來源活動紀錄；未提供從影像完整重跑的方法。原文／忠實機械轉錄不新增排他限制，自有具著作權說明與原創編排採CC BY 4.0；未收入的館方影像另層適用CC BY-NC 4.0，詳[RIGHTS.md](RIGHTS.md)。

## 取得與引用

GitHub專案位置：https://github.com/poplolioi11/bodleian-sinica1826-xiyi-xinfa-1872 。Zenodo待封存；版本DOI與全版本DOI尚未取得。引用暫依CITATION.cff中的版本與GitHub專案連結。

關鍵字：西醫新法; Xi yi xin fa; 嘉約翰; John Glasgow Kerr; 林湘東; Lin Xiangdong; 晚清醫學翻譯; late-Qing medical translation; 包紮史; history of bandaging; 外科史; history of surgery; 圖文關係; image-text relationships; 印刷史; print history; Sinica 1826

