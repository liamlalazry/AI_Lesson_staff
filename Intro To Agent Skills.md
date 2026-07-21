Claude Skills 


הרעיון ב SKILLS
הוא לחסוך טעינה וחזרתיות בזמן שמבצעים פעולות שחוזרות על עצמן כל פעם שאתה מסביר את הסטנדרט שבו אתה כותב קוד את הפורמט של מה שאתה רוצה להוציא אתה חוזר על עצמך והרעיון מאחורי skills זה לחסוך את זה 
תיקייה שבה יש מקורות מידע הגדרות או סקריפטים לפעולה שנועדו לגרום לקלוד לעבוד בצורה מדוייקת יותר ויעילה 
skill.md 
קובץ הגדרות בסיסי שיכול לכוון על סקילים אחרים ומקורות בתוך תיקיית ה skills
סקילים צריך להבין שהוא נטען ברגע שנטען סקיל ואם הוא גדול מידיי זה בזבוז של עיבוד ופחות כיף לתחזק ולשנות  לכן שם נשמור רק דברים חיוניים ונשמור חומרים אחרים בקבצים נפרדים שקלוד יקרא כשיצטרך למשל כשיופיע קישור בסקיל אחר,
בקובץ הזה יש תיאור של הסקיל שאותו רוצים להפעיל כשההוראות יגיעו למטה הרעיון הוא שקלוד בודק את הסקילים השונים לפי התיאור ובוחר את אלו שמתאימים לו הכי הרבה 

personal skills - /home/skills 
.claude/skills inside a repository - team preference skills 

claude.md - general skill that loaded in every conversatition - if u want something to always happend this is the place - for example
Threat me as a Tier 2 soc analysit that is working in AD environment when answering questions or suggesting solutions.

good description is answering what and when 
Skills load on demand


Enterprise -> Personal -> Project -> Plugins

example: 
---
name: pr-description
description: Writes pull request descriptions. Use when creating a PR, writing a PR, or when the user asks to summarize changes for a pull request.
---

When writing a PR description:

1. Run `git diff main...HEAD` to see all changes on this branch
2. Write a description following this format:

## What
One sentence explaining what this PR does.

## Why
Brief context on why this change is needed

## Changes
- Bullet points of specific changes made
- Group related changes together
- Mention any files deleted or renamed

agentskill.io - many available field s like allowed-tools which can restrict tools or action like just "Read" or model which restrict to specific models

