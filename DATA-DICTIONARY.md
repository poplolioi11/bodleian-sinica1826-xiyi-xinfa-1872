# Data dictionary / 欄位說明

`book.json` is the fixed text master for this release. `pages[]` follows the 25 official image captures (`fNNN`); unit IDs beginning `pNN` refer to the 44 physical faces. Units retain ID, text, role, side and order. Core unit bounding boxes are null; the one previously observed unit region and unresolved edge regions are in `source-regions.json`. Region boxes do not imply glyph boundaries.

`uncertainties.json` records 71 provisional ranges with unit ID, exact surface, candidates and reason. Start is inclusive and end exclusive in Unicode code points. Original 69 uncertainty declarations and full before/after history remain privately fixed; current uncertainty positions derive from the operations. `source-pages.json` supplies original capture URLs, SHA-256 and dimensions.

`book.txt` serializes the same unit strings with explicit unit labels. `book.tei.xml` preserves the same strings, unit IDs and source links in TEI; no complete critical apparatus or complete private annotation history is claimed. `REVISION-CHANGES.json` gives public scope and representative corrections, not the complete private difference worklog. `VALIDATION.json` and `SHA256SUMS` document engineering checks only.

`methods.physical_faces[]` separates immutable `historical_initial_observation` from `revision_status`. Source locator fields are unchanged; historical notes are not current coverage or current glyph assertions.
