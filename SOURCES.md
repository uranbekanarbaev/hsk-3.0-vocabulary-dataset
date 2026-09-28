# Source and edition

The dataset is a transcription of **《HSK 考试大纲》 / Syllabus for the Chinese Proficiency Test**, published **2025-11** by the Center for Language Education and Cooperation. The supplied PDF cover prints **2026-07** as its implementation date. That printed date is not a statement that every test centre had changed its exam on that date; consult current official registration information.

- [Official HSK page](https://www.chinesetest.cn/HSK) → HSK 3.0 → Examination Syllabus.
- [Source syllabus PDF](https://hsk.cn-bj.ufileos.com/3.0/%E6%96%B0%E7%89%88HSK%E8%80%83%E8%AF%95%E5%A4%A7%E7%BA%B21219.pdf).
- Edition checked: 28 September 2026.
- Supplied source filename: `新版HSK考试大纲1219.pdf`.
- Source SHA-256: `ec74ce0439e837bbb15154be13e747ae798903b2fd3a331629df6c3b45504941`.

## Scope

All **11,000 numbered vocabulary entries**, IDs 1–11,000, are represented exactly once. First-level totals are 300, 200, 500, 1,000, 1,600, 1,800 and 5,600. Cumulative totals are 300, 500, 1,000, 2,000, 3,600, 5,400 and 11,000.

Chinese entries, pinyin, parts of speech and full level labels are retained from the source. Blank parts of speech remain blank. Homograph suffix digits are preserved in `entry` and also separated into `hanzi` / `homograph`. `level` records the first introduced level; `level_label` retains the full parenthetical source label. The advanced band is `7-9`, never three invented sublists.

No automatic English dictionary glosses were included. This is a Chinese/pinyin syllabus reference. The CSV and JSON share the same records. `source_pdf_page` identifies the physical page in the source PDF, counting the cover as page 1.

This is the **November 2025 examination syllabus**, not the earlier 2021 proficiency standard and not the old six-level HSK 2.0 vocabulary list. The printable layout and offline browser are independent additions by hsk-tutor.com. Source rights are not replaced; see [LICENSE.md](LICENSE.md).
