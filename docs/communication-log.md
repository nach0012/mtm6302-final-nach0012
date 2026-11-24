# Communication Log – MyStyle

Developer: Saida Nachit · Client: assigned classmate (MyStyle brief)

Summaries only; private messages and contact details are not published.

| Date and time | Outreach / question | Response | Decision and reason |
|---|---|---|---|
| Nov 23, 2026, ~5:15 PM | Introduced myself to the client, summarized my understanding of the brief, and asked 5 clarification questions (Q1–Q5 below). | Nov 23, ~5:18 PM: client acknowledged and said she would answer after work. | Continued planning with working assumptions while waiting. |
| Nov 24, 2026, ~12:20 AM | — | Client confirmed my understanding and answered Q1–Q5. Her main priority: keep the app simple, organized and easy to use. | Answers adopted (see below). |
| Nov 24, 2026 | Instructor asked me to reduce the scope: remove the optional picture, F3 Create an outfit and F4 Surprise Me; keep F1 and F2; apply favorites to clothing items. | Nov 24, 2026: client agreed to the reduced scope. | Instructor-approved scope change. Required features are now F1 Add clothes, F2 Manage wardrobe, F5 Favorite items, plus Clear Everything. Plan, wireframes and tests updated; original brief kept in docs. |

## Clarification questions

| # | Question | Client answer (Nov 24) | Effect on the plan |
|---|---|---|---|
| Q1 | Should the delete confirmation warn how many saved outfits will also be deleted? | Yes. | No longer applies – outfits were removed in the scope change. Delete still asks for confirmation. |
| Q2 | In the "All" view, should clothes be grouped by category or shown as one list? | Group under Tops, Bottoms and Shoes. | Grouped headings in the All view (`renderWardrobe`). |
| Q3 | How should items with the same name be told apart in the outfit dropdowns? | Add a number; a picture can also help. | No longer applies – no outfit dropdowns or pictures. Duplicate names stay separate items with their own id. |
| Q4 | Is a name length limit acceptable? | Yes, 40 characters maximum. | 40-character limit for clothing names (`cleanName`, test T4). |
| Q5 | Should the wardrobe filter and Favorites Only be remembered after a refresh? | No – start on "All" with Favorites Only off; saved data stays available. | Filters are not saved; clothes and favorites are restored. |
