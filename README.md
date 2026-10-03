# GuideOS PDF/A Konverter

**Klartext** ist eine moderne, schlanke GTK4/Libadwaita-Anwendung für Linux, die gescannte PDF-Dateien mittels **OCRmyPDF** durchsuchbar macht und in das langzeitsichere **PDF/A-Format** umwandelt.

![GTK4](https://img.shields.io/badge/GUI-GTK4%20%2F%20Libadwaita-blue)
![Python](https://img.shields.io/badge/Language-Python%203-green)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

---

## ✨ Features

- **Moderne GNOME-Optik:** Fügt sich nahtlos in aktuelle Linux-Desktops (GTK4 & Libadwaita) ein.
- **Durchsuchbare PDFs (OCR):** Nutzt Tesseract OCR und OCRmyPDF zur Erkennung von Texten in gescannten Dokumenten.
- **Mehrfachauswahl:** Mehrere PDFs gleichzeitig auswählen und im Hintergrund verarbeiten lassen.
- **Freeze-freie UI:** Dank Multithreading bleibt die Benutzeroberfläche auch bei großen Dokumenten jederzeit bedienbar.
- **Direkter Ordnerzugriff:** Zieldateien werden strukturiert in einem Unterordner (`pdfa_output`) abgelegt und können direkt aus der App heraus geöffnet werden.

---

## 🛠 Voraussetzungen

Für den Betrieb werden Python 3, PyGObject sowie OCRmyPDF inklusive deutscher Sprachpakete benötigt.

### Debian / Ubuntu / Linux Mint
```bash
sudo apt update
sudo apt install python3 python3-gi python3-gi-cairo gir1.2-gtk-4.0 gir1.2-adw-1 ocrmypdf tesseract-ocr tesseract-ocr-deu
