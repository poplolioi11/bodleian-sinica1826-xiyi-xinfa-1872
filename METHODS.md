# 方法與可重跑界線 / Methods and reproduction limits

本版在固定的Bodleian 3000px寬影像上進行AI初錄，按44編號物理面記錄原印文字、角色、來源側、疑讀、缺區與版面說明。封裝將同幀物理面合併為25個fNNN來源影像記錄，保留pNN單位識別碼與物理面順序。封裝不重新讀字、不正規化Unicode、不默補字、不改句讀，不採用他稿訂正。

The initial transcription was made with AI assistance. The exact executed model identity, effort setting and token figures cannot be verified from the available execution record and remain unknown; they are not reported as zero. Private agent/session identifiers are not model evidence. The initial version has no applied independent image reading, full human double collation, expert review, peer review or accuracy measurement.

疑讀target只有唯一出現時才自動定位；重複target必須由凍結稿明示0起算occurrence_index。候選與理由不替換正文。已查看、文字或歸頁尚未確定的來源邊區獨立保存extent=unknown及必要來源定位；部分邊條是否屬本頁或鄰頁尚未裁定，不能一概稱其文字不可辨。不捏造碼點區間或單字占位，也不因此宣稱所有原字已收錄。原稿非null bbox另存source-regions.json；core unit bbox仍為null。

原點號原刻／後加的性質尚未人工核定。現有字串中的點號、空白、罕字與異體原樣保存；字元編碼不是字形摹本，也不證明讀法正確。

工程封裝沿用既有固定schema、TEI與CFF驗證及匯出程序，並增加對實際44面凍結稿的全量字串、順序、角色、物理定位與bbox投影檢核。格式驗證、來源連結及checksum只證明資料一致與可核對性。

The package excludes source images, crops, private programs, prompts and complete private source-reading activity/provenance. It does not provide a full reproducible image-to-text production method. Public JSON/TXT/TEI and checksums permit inspection of the delivered fixed data and export equivalence, not reconstruction of every private production step.

本資源的用途限於歷史文獻、翻譯與印刷研究；沒有進行現代臨床驗證或生物研究。

