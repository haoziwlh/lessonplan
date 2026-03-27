# Proposal: RSD 2025-2026 Lesson Plan Generation

## Overview

为 Reading School District 2025-2026 学年的每一个正常上课日，自动生成标准化 lesson plan 文件，格式符合学区要求（`docs/rules.md`）。

## Source

- 日历来源: [RSD 2025-2026 Calendar (English FINAL)](https://files-backend.assets.thrillshare.com/documents/asset/uploaded_file/5197/Rsd/149d6917-8b67-4d55-9018-e9c614750a01/RSD_2025-2026_CALENDAR_-_English_FINAL.pdf?disposition=inline)
- 学区: Reading School District (RSD), Pennsylvania

## Scope

- **日期范围**: 2025年8月25日（First Student Day）至 2026年6月5日（Last Student Day）
- **包含**: 所有正常上课日（含 Early Dismissal 日）
- **排除**: 所有有颜色标注的日期（见下方详细列表）

## 排除日期（有颜色 / 不上课）

### School Closed: Offices Closed（法定假日）
| 日期 | 说明 |
|------|------|
| Sep 1, 2025 | Labor Day Holiday |
| Nov 27–28, 2025 | Thanksgiving Holiday |
| Dec 24–25, 2025 | Christmas Holiday |
| Dec 31, 2025 | New Year's Holiday |
| Jan 1, 2026 | New Year's Holiday |
| Jan 19, 2026 | Martin Luther King Day |
| Apr 2–3, 2026 | Easter Holiday |
| May 25, 2026 | Memorial Day |
| Jun 19, 2026 | Juneteenth |

### School Closed: Offices Open
| 日期 | 说明 |
|------|------|
| Aug 22, 2025 | Summer Recess |
| Aug 29, 2025 | Labor Day Recess |
| Dec 1, 2025 | Thanksgiving Recess |
| Dec 26, 29, 30, 2025 | Winter Break |
| Jan 2, 2026 | Winter Break |
| Feb 16, 2026 | Presidents' Day |
| Mar 30–31, 2026 | Spring Break |
| Apr 1, 6, 2026 | Spring Break |

### School Closed: Teachers on Duty（无学生）
| 日期 | 说明 |
|------|------|
| Aug 4–8, 2025 | Induction Week |
| Aug 18, 2025 | Clerical Day |
| Aug 19–21, 2025 | In-service Day #1–#3 |
| Sep 29, 2025 | In-service Day #4 |
| Oct 13, 2025 | In-service Day #5 |
| Nov 4, 2025 | Election Day / In-service Day #6 |
| Nov 24–26, 2025 | Act 80 Day / Parent Conferences |
| Feb 12–13, 2026 | Act 80 Day / Parent Conferences |
| Mar 23, 2026 | Act 80 Day |
| Jun 8, 2026 | Clerical Day |

## 特殊上课日（Early Dismissal，仍需创建 lesson plan）

| 日期 | 说明 |
|------|------|
| Oct 31, 2025 | Early Dismissal |
| Dec 23, 2025 | Early Dismissal |
| Jan 16, 2026 | Early Dismissal |
| May 22, 2026 | Early Dismissal |
| Jun 5, 2026 | Early Dismissal（Last Student Day）|

## 学期划分（Marking Periods）

| 学期 | 日期范围 |
|------|----------|
| First Quarter | Aug 25 – Oct 30, 2025 |
| Second Quarter | Oct 31, 2025 – Jan 20, 2026 |
| Third Quarter | Jan 21 – Mar 25, 2026 |
| Fourth Quarter | Mar 26 – Jun 5, 2026 |

## 考试窗口期（供 lesson plan 备注）

| 考试 | 日期 |
|------|------|
| Keystone Exam | Dec 3–17, 2025; May 11–22, 2026 |
| WIDA Exam | Jan 5 – Feb 28, 2026 |
| PSSA (ELA) | Apr 21–23, 2026 (Grades 3–8) |
| PSSA (Math) | Apr 27–28, 2026 (Grades 3–8) |
| PSSA (Science) | Apr 29–30, 2026 (Grades 5 & 8) |

> 注：州考期间不批准学生教育出行

## Lesson Plan 格式要求（来自 docs/rules.md）

每个 lesson plan 必须包含以下字段：

1. **Date / Time Frame / Subject / Grade**（日期、时间段、科目、年级）
2. **Goal / Objective**（目标，须对齐 RSD 标准课程）
3. **Skills / Knowledge**（基于数据的学生需求技能）
4. **Activities / Procedures**（教学活动流程），包含：
   - 针对 ELs、IEP 学生、高风险学习者的 Scaffolds / Accommodations / Modifications / SDI
   - Paraprofessional 计划（如已分配）
5. **Resources**（教学资源）
6. **Assessment**（正式或非正式，衡量课程目标）

## 输出方案（待确认）

- **文件格式**: Markdown (`.md`)，每天一个文件
- **命名规则**: `YYYY-MM-DD.md`（如 `2025-09-02.md`）
- **目录结构**: 按月分文件夹（如 `lessons/2025-09/`）
- **预估文件数**: 约 175–185 个上课日

## 待确认事项

- [ ] 科目和年级是否固定？（还是每个 lesson plan 都是同一模板供手填？）
- [ ] 文件命名和目录结构是否符合预期？
- [ ] 是否需要从 8月25日（第一学生日）开始，还是其他日期？
