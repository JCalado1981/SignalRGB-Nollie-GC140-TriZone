# SignalRGB-Nollie-GC140-TriZone
SignalRGB TriZone component for the Nollie GC140 RGB fan.
# SignalRGB Nollie GC140 TriZone

![Nollie GC140 TriZone](Images/preview.png)

Bring independent RGB lighting zones to your **Nollie GC140** fans with full SignalRGB compatibility.

This project divides the original **34 LED Nollie GC140** into **three independent lighting zones**, allowing advanced RGB effects similar to premium modular RGB fans while preserving full compatibility with the original hardware.

---

## ✨ Features

- Independent **Center RGB Zone** (10 LEDs)
- Independent **Left RGB Zone** (12 LEDs)
- Independent **Right RGB Zone** (12 LEDs)
- Full compatibility with SignalRGB
- Compatible with the Nollie8 Controller
- Supports single fans and daisy-chained fan groups
- Designed specifically for the original Nollie GC140

---

## 📦 Components

| Component | LEDs |
|-----------|-----:|
| GC140 Center | 10 |
| GC140 Left | 12 |
| GC140 Right | 12 |

Total LEDs: **34**

---

## 📁 Repository Structure

```
Components/
    GC140 Center.json
    GC140 Left.json
    GC140 Right.json

Images/
    gc140_center.png
    gc140_left.png
    gc140_right.png

Screenshots/

README.md
CHANGELOG.md
LICENSE
```

---

## 📥 Installation

1. Download the latest release.
2. Copy the JSON component files into your SignalRGB Components folder.
3. Restart SignalRGB.
4. Open your Nollie Controller.
5. Add the following components:

- GC140 Center
- GC140 Left
- GC140 Right

Arrange the three components to match the physical fan layout.

---

## ✔ Compatibility

| Hardware | Status |
|----------|--------|
| Nollie GC140 | ✅ Supported |
| Nollie8 Controller | ✅ Supported |
| SignalRGB | ✅ Supported |
| Daisy Chain Fans | ✅ Supported |

---

## 🖼 Screenshots

### Components

| Left | Center | Right |
|------|--------|-------|
| ![](Images/gc140_left.png) | ![](Images/gc140_center.png) | ![](Images/gc140_right.png) |

Additional screenshots can be found in the **Screenshots** folder.

---

## 💡 Why this project?

The original Nollie GC140 is treated as a single 34 LED device.

This project separates the fan into three independent RGB zones, making advanced SignalRGB effects possible while maintaining the original LED order and full hardware compatibility.

---

## 🙏 Acknowledgements

Special thanks to:

- **SignalRGB** for the original GC140 component.
- **Rockslay**, whose GC120 TriZone project inspired the concept behind this implementation.
- Everyone in the SignalRGB and Nollie communities who shares knowledge and ideas.

---

## 👨‍💻 Author

**Jorge Miguel Calado**

Community project developed for SignalRGB users.

Technical collaboration during development:
**OpenAI ChatGPT**

---

## 📄 License

This project is released under the **MIT License**.

Feel free to use, modify and improve it while keeping proper attribution.

---

# ⭐ If this project helped you

Please consider giving the repository a ⭐ on GitHub.

It helps other SignalRGB users discover the project.
