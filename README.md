# RSD 2025-2026 Lesson Plan

Reading School District 2025-2026 学年标准化 Lesson Plan 生成项目。

## 项目目标

为 RSD 每一个正常上课日自动生成符合学区要求的 lesson plan 文件，覆盖 2025年8月25日至 2026年6月5日。

## Lesson Plan 格式要求

每个 lesson plan 须包含（来自 `docs/rules.md`）：

- **Date / Time Frame / Subject / Grade**
- **Goal / Objective**（对齐 RSD 标准课程）
- **Skills / Knowledge**（基于学生数据）
- **Activities / Procedures**（含 ELs、IEP、高风险学习者的 Scaffolds / Accommodations / Modifications / SDI，以及 Paraprofessional 计划）
- **Resources**
- **Assessment**（正式或非正式）

## 学年日历

- 来源：[RSD 2025-2026 Calendar (English FINAL)](https://files-backend.assets.thrillshare.com/documents/asset/uploaded_file/5197/Rsd/149d6917-8b67-4d55-9018-e9c614750a01/RSD_2025-2026_CALENDAR_-_English_FINAL.pdf?disposition=inline)
- 第一学生日：2025年8月25日
- 最后学生日：2026年6月5日

| 学期 | 日期范围 |
|------|----------|
| First Quarter | Aug 25 – Oct 30, 2025 |
| Second Quarter | Oct 31, 2025 – Jan 20, 2026 |
| Third Quarter | Jan 21 – Mar 25, 2026 |
| Fourth Quarter | Mar 26 – Jun 5, 2026 |

## 目录结构

```
lessons/
  2025-08/
  2025-09/
  ...
  2026-06/
docs/
  rules.md          # 学区 lesson plan 格式要求
openspec/
  changes/
    rsd-2025-2026-lessonplan/
      proposal.md   # 项目提案（含完整日历分析）
```
