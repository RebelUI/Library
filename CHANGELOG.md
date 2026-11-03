# RebelUI changelog (version stays 1.0.0)

## Latest
- Round 4: 11 elements (Vector, Level, BarChart, Stack, ButtonRow, Tiles, Status, KeyValue, Callout, Tasks, ColorInput), 17 window tools (GoTo, ListTabs, OnOpen, OnClose, Every, CycleTheme, RandomTheme, Fireworks, Sparkle, RippleAt, Achievement, ShowShortcuts, CopyReport, SetFont, SetTextScale, Konami, IdleDim) and helpers `UI:SelfTest()`, `UI:Info()`, `UI.Debounce`, `UI.Throttle`, `UI.FormatNumber`, `UI.Short`.
- Round 3: 12 tab elements (TriState, ToggleGrid, Socials, Until, Poll, Leaderboard, TextArea, Heading, Gallery, FAQ, Changelog, Avatars), 11 screen looks (Snow, Matrix, Aurora, Vignette, Scanlines, Flash, Pulse, Shine, Wiggle, Welcome, CountDown) and 7 tools (Prompt, Choose, Confirm, Loading, Hotkey, Once, PlaySound).
- Round 2: 20 new tab elements (Radio, CheckList, Swatches, Badge, Profile, Spacer, Quote, Counter, Meter, Compare, Banner, Marquee, Stopwatch, Clock, Spoiler, TagInput, Pagination, Copy, Kbd, Tip) and 10 window tools (Announce, ShowChangelog, Tour, AskRating, Lock, SetAutoHide, GetFlag, SetFlag, Highlight, Rain). The Example has a new "More" tab.
- New cards: `Tab:Groupbox`, `Tab:Tabbox`, `Tab:Accordion` (like Linoria / Obsidian groupboxes and tabboxes).
- Repo moved to RebelUI/Library. Removed the Discord embed file and the black icons folder.
- Close animations: Normal, BlackHole (rebuilt), Shatter, TVOff, Spin, Implode, Custom (full-screen picture or video), None. `Win:SetCloseAnimation`, `Tab:ClosePicker`, `UI.PreviewClose`, `UI.PlayCover`.
- Explosion styles: Classic, Confetti, Shockwave, Sparks, Diamonds, Custom (your picture), None. `Win:SetBoomStyle`, `Tab:BoomPicker`. No "LET'S GO" / "BOOM" text by default.
- Links are blue with an underline, a dark scan and a blue link icon (`Tab:Link`, link labels, rich-text links).
- Summary tab: Print removed; added Files, Session, Important and Discord buttons.
- Black hole close animation on the X of the main window (on by default; `Win.CloseAnimation = "None"` turns it off). The key panel only uses it with `CloseAnimation = "BlackHole"`. Also `Win:Close()` and `UI.BlackHole`.
- New default key panel ("Card"): compact like a classic key system, with a Get Key drawer, Discord button, Check Key, status line, Paste button, Cooldown and many animations. `Layout = "Wide"` / `"Tall"` keep the older panels.
- Developer tools: `UI.Debug`, `UI.OnError`, `UI.Errors`, `UI.Log`.
- Live translations: `UI:AddLanguage`, `UI:SetLanguage`, `UI.T`.
- Move elements: `obj:MoveUp()`, `obj:MoveDown()`, `obj:MoveTo(n)`.
- Key lifetime: `RememberFor`, a lifetime from `Check` (second value), `UI.KeyTimeLeft`, `UI.WatchKey`, `UI.FormatTime`.
- Device-bound key: `HwidBind`, `UI.GetHWID`, `Check(key, hwid)`.
- New elements: `Tab:Stepper`, `Tab:Rating`, `Tab:Countdown`.
- Key panel: dark provider cards, "Link copied" pill, light key box, moving border, pulsing Verify button.
- Icons: `UI.IconMode` ("Black" default, "White", "Glow"); async icon buttons with a spinning loading icon.
- Summary tab: Info, Search, Refresh, Copy, Print, Save, Share, Export.
- Expand/minimize button wired to `Win:Maximize()`. Locked toggles show a padlock.
- Fixes: spinner icon invisible, spinner leak on close, search box overlapping the top-bar buttons, Verify text overlapping the padlock, paused countdown still counting.
