# Changelog

## 0.0.2 — 2026-04-22

- Fix selection contrast — selection background was the same as the foreground, which made selected text invisible. Replaced with a dark desaturated teal (`#2a3f3f`) that preserves syntax color underneath.
- Replace translucent word highlight (`#40404060`) with a solid subtle fill (`#2a2a2a`) — no more ghosting over code.
- Add `findMatchBorder` so search matches pop without drowning the text.
- Remove `editor.selectionForeground` override; VS Code's default preservation of syntax colors looks better.
- Apply the same fixes to terminal selection.

## 0.0.1 — 2026-04-14

- Initial release.
- Full editor + workbench + terminal palette.
- Syntax token mapping for strings, keywords, functions, types, comments, numbers, regex, decorators, markdown, diff, JSON, CSS.
