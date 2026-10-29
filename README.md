# Sri Lanka public holidays and Poya days, 2026-2027

Every public, bank and mercantile holiday in Sri Lanka for 2026 and 2027, with the full moon Poya days marked, as JSON, CSV and iCalendar files.

**Browse it, check the next holiday and get a calendar feed: [hirantha.me/tools/sri-lanka-holidays](https://hirantha.me/tools/sri-lanka-holidays)**

## Files

| File | What it is |
| --- | --- |
| `data/holidays-2026.json` | The 2026 holidays |
| `data/holidays-2027.json` | The 2027 holidays |
| `data/holidays.json` | All years in one file |
| `data/holidays.csv` | All years, as CSV |
| `calendars/sri-lanka-holidays.ics` | Every holiday, for a calendar app |
| `calendars/sri-lanka-poya-days.ics` | Poya days only |
| `calendars/sri-lanka-mercantile-holidays.ics` | Mercantile holidays only |

Each holiday has: `date` (YYYY-MM-DD), `weekday`, `name` (as gazetted), `poya` (a full moon Poya day itself, not "the day following"), `mercantile` (also a mercantile holiday, which applies to private-sector employees), and `bank` and `public` (true for every row). Saturdays and Sundays are bank holidays too; a plain weekend is not listed, but a holiday that falls on one is.

Want calendar feeds that update themselves, or a widget for your website? See [hirantha.me/widgets](https://hirantha.me/widgets). A JSON API with a free key is at [hirantha.me/developers](https://hirantha.me/developers).

## Source

Transcribed from the Central Bank of Sri Lanka's published bank-holiday lists (https://www.cbsl.gov.lk/en/about/about-the-bank/bank-holidays-2026 and -2027), which follow the holidays gazetted under the Holidays Act, No. 29 of 1971. The 2027 list is Extraordinary Gazette No. 2493/05. Every row is checked against the Central Bank's table, including the weekday it prints. The government can amend the list by notification; a date here is the gazetted one.

## Licence and credit

[CC BY 4.0](LICENSE). Use it for anything, including commercial work. Please credit it with a link:

```html
Sri Lanka holidays from <a href="https://hirantha.me/tools/sri-lanka-holidays">hirantha.me</a>
```

Found a mistake? Open an issue or write via [hirantha.me/contact](https://hirantha.me/contact).

_Generated 2026-10-27 from the data behind [hirantha.me](https://hirantha.me)._
