# Rofi Config

## 🔹 Features

- **Modes:** Only `drun` (application launcher)
- **Icons:** Enabled for graphical lists
- **Style:** Rounded corners, padding & spacing adjusted

<br>

## 🎨 Colors (color.rasi)

| Name           | Hex Color |
|----------------|-----------|
| Background     | `#111111` |
| Background-alt | `#222522` |
| Text           | `#cfdfd5` |
| Selected       | `#00552f` |
| Selected Text  | `#cfdfd5` |
| Active         | `#3fb83f` |
| Urgent         | `#ef6560` |

<br>

## 🖋 Fonts (dont.rasi)

- Font: `Monocraft 9.7`
- Icons: enabled

<br>

## 📦 Installation

1. Copy the config files to your Rofi directory, e.g.:

```bash
mkdir -p ~/.config/rofi
cp *.rasi ~/.config/rofi/
```

2. Launch Rofi with:

```bash
rofi -show drun
```

<br>

## 📂 Structure

```
.
├── config.rasi        # Main configuration
├── color.rasi         # Color definitions
└── font.rasi          # Fonts
```

---

## 🔗 Useful Links

- [Rofi GitHub](https://github.com/davatorium/rofi)
- [Rofi Wiki](https://github.com/davatorium/rofi/wiki)

