# Kate ♥ Nim

[Nim](http://nim-lang.org) language support and colors for [Kate](http://www.kde.org/applications/utilities/kate/).

# Screenshots

![NimKate](nimkate.png)

# Install

```bash
mkdir -p "~/.local/share/org.kde.syntax-highlighting/syntax/"
wget -o "~/.local/share/org.kde.syntax-highlighting/syntax/nim.xml" https://raw.githubusercontent.com/juancarlospaco/NimKate/master/nim.xml
mkdir -p "~/.local/share/org.kde.script/indentation/"
wget -o "~/.local/share/org.kde.script/indentation/nim.js" https://raw.githubusercontent.com/juancarlospaco/NimKate/master/nim.js
```

This does NOT require KatePart5 installed, works Ok with Kate only.

Source: https://docs.kde.org/trunk5/en/applications/katepart/highlight.html

<details>
    <summary>Manual Install</summary>

- **Syntax**: Save XML file to `"~/.local/share/org.kde.syntax-highlighting/syntax/nim.xml"`
- **Indent**: Save JS file to `"~/.local/share/org.kde.script/indentation/nim.js"`
- **Colors**: Kate > Settings > Configure Kate > Fonts & Colors > (Schema) Import...

</details>


# License

All code is released under [WTFPL](http://www.wtfpl.net/) unless explicitly stated otherwise.

[Original Repo (Dead)](https://github.com/PhilipWitte/NimKate#kate-s-nimrod "All Credit to the Original Author")
