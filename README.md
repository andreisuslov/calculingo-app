# <img src='Workflow/icon.png' width='64' alt='icon'> calculingo Alfred Workflow

A calculator you type at in plain words, in an Alfred window

[⤓ Download the workflow](https://github.com/andreisuslov/calculingo-app/releases/latest)

## Usage

`calc` opens the window, and `calc from 1 jan to christmas` opens it already answering. Dates and the gap between them, the time in another city, money at today's rate, units, the sun and the moon, and maths from a sum to a percentile: it is the calculator from [calculingo.app](https://calculingo.app), and the answer updates on every keystroke.

Below the answer, the window lists what would finish the line (a city, a unit, a currency). Otherwise it lists your recent questions, or examples if you haven't asked anything yet. Nothing in the list is chosen until you press <kbd>↓</kbd>, so <kbd>↩</kbd> is about the line you typed.

* <kbd>↩</kbd>: Copy the answer and close the window. If the last word is half-typed, or the line doesn't answer yet, it finishes the line instead. With a row chosen, it fills the line with that row.
* <kbd>⌘</kbd><kbd>↩</kbd>: The same, but pastes the answer into the app you were in.
* <kbd>⌘</kbd><kbd>⇧</kbd><kbd>C</kbd>: Copy the answer and keep the window open.
* <kbd>⇥</kbd>: Fill the line with whatever is on offer: the chosen row, the example an empty box shows, or the rest of a half-typed word. <kbd>→</kbd> does the same while a row is chosen.
* <kbd>↓</kbd><kbd>↑</kbd> (or <kbd>⌃</kbd><kbd>N</kbd> <kbd>⌃</kbd><kbd>P</kbd>): Move through the list. <kbd>↑</kbd> from the first row goes back to the line.
* <kbd>⌘</kbd><kbd>1</kbd>–<kbd>⌘</kbd><kbd>9</kbd>: Fill the line with the row with that number.
* <kbd>⌘</kbd><kbd>O</kbd>: Ask the question on calculingo.app.
* <kbd>⌘</kbd><kbd>⇧</kbd><kbd>⌫</kbd>: Forget the chosen recent question. <kbd>⌘</kbd><kbd>⌫</kbd> forgets them all, with Undo.
* <kbd>esc</kbd>: Step back: the list, then the line, then the window.

A name is given its value with `:=`, as on the site: `price := $8 * 3`, then `price in eur`, and `ans` is the last answer.

## Free and Pro

Eight answers a day are free: each one you copy or paste counts, and the footer says how many are left. After the eighth, the window shows the way to [buy a license](https://store.calculingo.app/) until the next day.

A license makes them unlimited. It's the same calculingo Pro license that unlocks [calculingo for Mac](https://calculingo.app/features), and the workflow uses it from there: nothing to paste in.

## Requirements

Alfred 6 with the Powerpack, and [calculingo for Mac](https://calculingo.app/features), which is free to download. The workflow asks the app for each answer. If the app isn't running, the workflow starts it in the background, out of sight and out of the Dock.

## License

Copyright (c) 2026 Andrei Suslov. All rights reserved. See [LICENSE](LICENSE).
