# JavaScript DOM Practical Assignment — Bus Ticket Booking

## Ujeeddo
Waxaad xalay barateen DOM iyo Stock Counter. Hadda sameeya mashruuc cusub oo **Bus Ticket Booking** ah adigoo isticmaalaya JavaScript DOM. Ha koobiyeeynin project-kii hore; faham logic-ga oo adigu hirgeli.

## Files
- `index.html` — Design-ka waa diyaar (HTML + Tailwind CSS).
- `script.js` — Halkaan ayaad ku qoraysaan JavaScript; waxaa ku jira TODO instructions.

## Requirements
1. Qiimaha **hal ticket = $5**.
2. Tirada kuraasta baska oo dhan = **8**.
3. Bilowga: `Tickets selected = 0`, `Available seats = 8`, `Total = $0`.
4. `+ Add` wuxuu kordhiyaa tickets-ka hal mar, balse **ma dhaafi karo 8**.
5. `− Remove` wuxuu dhimaa tickets-ka hal mar, balse **kama hoos mari karo 0**.
6. `Reset` wuxuu ku celiyaa tirada tickets-ka `0`.
7. Markasta oo tiradu is beddesho: update-garee ticket count, seats available, total price, iyo status.
8. Isticmaal `document.querySelector()`, `addEventListener()`, `textContent`, variables, conditions iyo function.

## Tijaabooyinka laga rabo
| Action | Tickets | Available | Total |
|---|---:|---:|---:|
| Initial | 0 | 8 | $0 |
| Add once | 1 | 7 | $5 |
| Add 3 more | 4 | 4 | $20 |
| Remove once | 3 | 5 | $15 |
| Reset | 0 | 8 | $0 |
| Click Remove at 0 | 0 | 8 | $0 |
| Click Add at 8 | 8 | 0 | $40 |

## Bonus (optional)
- Disable `Add` when all 8 seats are selected.
- Disable `Remove` when 0 tickets are selected.
- Show `Bus is full` when seats run out.

## How to run
Open `index.html` in a browser (or use VS Code Live Server). An internet connection may be needed for Tailwind's CDN styles; the DOM logic itself runs locally.

## Submission
Send your GitHub repository link and a screenshot (or short screen recording) showing the project working.
