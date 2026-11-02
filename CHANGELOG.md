# RebelUI changelog (version stays 1.0.0)

## Latest
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
