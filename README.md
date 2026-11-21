# أطلس الجماعات الإسلامية · Atlas of Islamic Movements

An interactive map and timeline of every figure, group and book mentioned by Sheikh Ahmad bin Khalid al-Hajri in his 10-part YouTube series on Islamic groups (Keyan al-Ma'rifa channel). Arabic and English.

خريطة تفاعلية وخط زمني لكل شخصية وجماعة وكتاب ذكره الشيخ أحمد بن خالد الهاجري في «سلسلة الجماعات الإسلامية».

## Links to a specific view

Add a hash to the address to open a figure, group, book, tab or year directly:

| Link | Opens |
|---|---|
| `#p=qutb&y=1960` | Sayyid Qutb's card in 1960 |
| `#g=mb` | The Muslim Brotherhood |
| `#b=qutb.1` | The card for *Milestones* |
| `#tab=books` | The Books tab |

The address updates as you browse, so you can copy it at any point to share what you're looking at.

## Sources and notes

- Opinions, judgments and classifications are the sheikh's, as stated in the series. Dates, places, countries and geographic spread come from general historical knowledge and may be approximate.
- Portraits and group logos are freely licensed files from Wikipedia and Wikimedia Commons. Each file's author and licence are listed on its card and under "Image credits" in the About tab.
- Flags are from [flag-icons](https://github.com/lipis/flag-icons) (MIT licence).
- Map data: Natural Earth, via world-atlas.

## Running it locally

It's a static site. Serve the folder with any web server, for example `python -m http.server`, and open `http://localhost:8000`. Opening `index.html` straight from disk won't work, because the page loads its data with `fetch`.
