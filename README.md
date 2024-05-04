# Key'n'Stroke

Displays keystrokes and visualizes mouse clicks in an overlay window. Extremely useful for demonstractive screen recording where you need your audience to easily understand _what_ keys or mouse buttons you pressed and _when_ you pressed them!

## Features

- Displays special keys (e.g., volume up: 🔊) and shortcuts
- Displays mouse cursor position
- Visually indicates pressed buttons
- Click-through
- Opacity configuration
- Customizable!
  - Choose icons
  - Select colors
  - Font choice
  - Overlay size and position
  - Text position and orientation
- Displays history of keys pressed
- Icon in notification area
- One small executable &mdash; no installation required
- Works on high-dpi screens
- Compatible with varied-dpi on multiple screens

Requirements: Windows 10

## Download

[Download Key-n-Stroke.exe 1.1.0](https://github.com/Phaiax/Key-n-Stroke/raw/master/Releases/`v1.1.0`/Key-n-Stroke.exe) (most recent, 2022-02-08)

There is no installation step. Just keep that `exe` file to start the application.

You will be greeted once with a [smart screen warning](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/Smartscreen1.png). Click "More Info" and "Execute Anyway". It's fine if the issuer name is 'Open Source Developer, Daniel Seemer'.

## Screenshots

[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/mouse.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/mouse.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/ctrl_scroll.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/ctrl_scroll.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/example1.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/example1.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/comic_sans_ms.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/comic_sans_ms.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/resizemode.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/resizemode.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/bottom_right.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/bottom_right.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/bottom_center.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/bottom_center.png)
[![Screenshot](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/settings.png)](https://raw.githubusercontent.com/Phaiax/Key-n-Stroke/master/Screenshots/settings.png)

## Releases

You can find all the exe files in the `Releases` folder

- `v0.0.1` (Text positioning not implemented yet)
- `v0.1.1` (Looks fine)
- `v0.1.2` (More Whitespace between special chars)
- `v0.1.3` (fix bug with Win+? shortcuts)
- `v0.2.0` (indicator for cursor position, history timeout, bugfixes, documentation)
- `v0.3.0` (indicator for pressed buttons, deadkey fixes, backspace functionality)
- `v0.3.1` (new icons, little fixes and internal improvements)
- `v1.0.0`
  - Rebrand as _Key'n'Stroke_ for better discoverability, previously _PxKeystrokesForScreencasts_
  - Switch to .NET 4.8 and WPF
  - Nicer icon rendering
  - High-Dpi compatibility
  - Custom Icons
- `v1.0.1`
  - No changes, just testing the update mechanism
- `v1.1.0`
  - _New_: Draw lines on the screen
  - _New_: Shortcut mode for keystroke window
  - _New_: Standby mode
  - _New_: Hide cursor indicator if cursor is hidden
  - _New_: Draw edge of cursor indicator
  - _New_: Indicate clicks via color change in cursor indicator
  - _New_: Setting to hide welcome window on startup
  - _Fix_: Capture shortcuts
  - _Fix_: Keystroke window startup position overlaps taskbar
  - _Fix_: Crash on modifier+click with button indicators enabled
  - _Fix_: Show shortcut shift+backspace

## Feature Requests

This app is Open Source. If you would like to see a feature, submit an issue or go ahead and start a pull request afterwards!

## Donations and Financial

You can donate via [paypal.me/phaiax](https://www.paypal.me/phaiax), send Bitcoins (`1JWER55pheUeJzaUcqaYwP8ZaGe5C16Rp9`) or Stellar Lumens (`phaiax*keybase.io`).  You can verify the wallet addresses cryptographically on [keybase.io/phaiax](https://keybase.io/phaiax). Add the message "pkfs" or "keynstroke" to the payment so I can associate it with this project. After funds are raised for the six-years worth of developer certificates (which I assume will never happen), I will use any additional funds to buy 🍦 for myself and anyone I like.

This app shows a smart screen warning. To remove this, I bought a validated security certificate from [Certum](http://www.certum.eu/certum/cert,offer_en_open_source_cs.xml). Unfortunately, even this step did not remove the warning. (As reported by people on the internet). However, at least it now shows my name as the author.

I said that if someone funds at least three years of certification (€ 75.00), I will use that money to buy a new certificate each year and implement a secure autoupdater. It's not that much, but I started anyway :smile: Here is the list of donations for full transparency: (three as of Feb 2022)

| Date       | Amount | From             |
|------------|--------|------------------|
| 2023-11-20 | € 20   | S. M.            |
| 2023-06-11 | € 9.10 | R. G. R.         |
| 2023-12-02 | € 22.22| A. V. N.         |
| 2023-07-25 | € 5    | D. N.            |
| 2023-05-30 | € 10.26| I. J.            |
| 2023-03-14 | € 5    | J. L.            |
| 2022-02-02 | € 50   | Mario Pastoor    |
| 2021-11-28 | € 16.95| Joshua Taylor    |
| 2021-03-05 | € 11.14| Heitor K. M. M.  |
| 2020-05-17 | € 5    | Marek S.         |
| 2020-08-06 | € 10   | AGlass0fMilk     |

Expenses: Certum Open Source Certificate and cryptographic card reader + Shipping: €119.87

Total: €164.67 - €119.87 = €44.8

Thx a lot, its time for a new certificate since the first one is expired :D

## License

Apache Version 2, refer to the file LICENSE for details

## Developed and signed by

- Daniel Seemer (<mail-oscert@invisibletower.de>)
