# Task Planner

A mobile-friendly, single-page team schedule with a live timeline, built-in breaks, task check-offs, and schedule editing.

## Live Demo

[Open Task Planner](https://calculator-gokul-2cc8.vercel.app)

## Features

- Daily timeline with automatically calculated start and end times
- Work and break blocks shown with distinct colors and icons
- Live current-block highlight and countdown
- Whole-day progress bar
- Task completion check-offs saved in browser storage
- Add, edit, delete, and reorder schedule blocks
- Shift the day with the start-time picker
- Optional gentle sound when a block changes
- Print-friendly layout
- Light/dark appearance follows the device setting
- Uses the Asia/Kolkata time zone

## Edit the Default Schedule

Open `index.html` and edit the `DEFAULT_SCHEDULE` array near the top of the JavaScript section. Each entry is:

```js
["Task name", 60] // duration in minutes
```

Use names containing `BREAK` (for example, `BREAK` or `LUNCH BREAK`) to mark rest blocks.

## Run Locally

1. Clone this repository:

   ```bash
   git clone https://github.com/Gokul-s-008/calculator.git
   ```

2. Open the project folder.
3. Open `index.html` in your browser.

No frameworks, packages, or build steps are needed. Schedule edits and check-offs are saved in that browser.

## Deployment

The site is deployed with [Vercel](https://vercel.com/). Pushes to the `main` branch are deployed automatically.

## Author

**Gokul S** · [GitHub](https://github.com/Gokul-s-008)
