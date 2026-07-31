# MeteoL – weather symbols, now in font form.

## Most commonly used meteorological symbols packed into an easy-to-use TrueType font

I have no idea how others insert symbols into their documents, but this seems to be the easiest method. I couldn't find any weather font with official WMO symbols, so I created this one.
Most of the commonly used meteorological symbols – rain, wind, thunderstorms, the usual suspects – all packed into one handy TrueType font.  
Originally built for my own notes, but hey, maybe you'll find a use for it too.

## So, what's inside?

- **MeteoL.ttf** – The font. Download - double-click - install - done.
- **MeteoL-character_map** – A handy cheat sheet showing character assignments, what each symbol looks like, and how to combine them. 
- **MeteoL.svg** – The raw Inkscape source. Edit this if you want to add or change symbols.  
- **MeteoL.sfd** & **MeteoL.g2n** – FontForge stuff.

⚠️ - The character mapping is adapted to the Slovak keyboard and language. Characters such as č,ť,ž,ý are used. You need to install the Slovak (QWERTY) layout.

## How to install

1. Double-click `MeteoL.ttf`.
2. Click the **Install** button.
3. Done. That's it.

## How to edit or add symbols
<ins> **First of all:**
Please **do not change the character assignment** under any circumstances. This would make a real mess for users in their documents. If you need to, create a completely different, independent version, like "MeteoL-EN" or something.</ins>
1. **Fork** this repository on GitHub (so you don't accidentally break my stuff).
2. Download everything from the `/src` directory.
3. Open `MeteoL.svg` in Inkscape.
4. Use the **SVG Font Editor** tool to tweak or add symbols.
5. Save as `.svg` (Inkscape format, please).
6. Open `MeteoL.sfd` in Font Forge and import the updated `.svg`.
7. In `Element` → `Font Info` → `PS Names`, bump the version number:
   - Adding new symbols? → 1.1 → 2.0
   - Just fixing a bug? → 1.1 → 1.2
8. Go to `File` → `Generate Fonts` and regenerate `.ttf` (and whatever else).  
   ⚠️ **Warning:** Font Forge will complain about "a few" errors. I didn't even read it. Ignore them – it works fine on Linux Mint and LibreOffice. Your mileage may vary.
9. Save your `.sfd` project.
10. Upload **everything** (yes, all files) to your fork.
11. Submit a **Pull Request** – I'll take a look and hopefully merge it.

---

## Tested on:

- Linux Mint (works great)
- LibreOffice (works great)
- Other systems? Probably. Let me know if something breaks.

---

## Known issues:
- **Small and inconsistent character size** – Symbols are small, and some of them are not perfectly aligned in size.  Not a big deal, but it may affect visual consistency. The solution is to tweak the size for each character individually.

- **All characters are placed too high** – The baseline is currently set above the standard typographic baseline. So, it's actually useless in Writer, but usable in Calc by aligning the characters to the bottom of the cell.

I'll fix it by the end of the first week of August if the stars are aligned.

---

## License & credits

Created by Ľuboš Černák.  
Licensed under **CC0** – do whatever you want with it. No strings attached.  
https://creativecommons.org/publicdomain/zero/1.0/deed.en

---

*If you find a bug, need a new symbol, or just want to say hi – open an issue, create a fork, or send a pigeon. I'll do my best to help.* 🕊️
