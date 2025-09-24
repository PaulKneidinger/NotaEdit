# NotaEdit - Moderner Notar-Editor

NotaEdit ist eine moderne WPF-Anwendung für Notare zur Verwaltung und Erstellung von Verträgen und Vorlagen.

## 🎯 Features

### ✅ Implementiert
- **Hierarchische Ordnerstruktur** - Unbegrenzte Ordnertiefe
- **Navigation** - Intuitive Ordner-Navigation mit Zurück-Funktion
- **Dark-Mode Support** - Vollständiges Theme-System
- **Einstellungen** - Konfigurierbare App-Einstellungen
- **Ordnerverwaltung** - Erstellen, Umbenennen, Löschen von Ordnern
- **Dateiverwaltung** - Verwalten von Verträgen und Vorlagen

### 🚧 In Entwicklung
- Vertrags-Editor
- Vorlagen-Editor
- Variable-System für Platzhalter
- Word-Integration
- PDF-Export

## 🛠️ Technologie

- **.NET 8** - Moderne .NET-Plattform
- **WPF** - Windows Presentation Foundation
- **C# 12** - Neueste C#-Features
- **JSON** - Für Datenspeicherung
- **Theme-System** - Light/Dark-Mode

## 📋 Systemanforderungen

- Windows 10/11
- .NET 8 Runtime
- 100MB freier Speicherplatz

## 🚀 Installation

1. Repository klonen:
```bash
git clone https://github.com/[USERNAME]/NotaEdit.git
cd NotaEdit
```

2. Projekt bauen:
```bash
dotnet restore
dotnet build
```

3. Anwendung starten:
```bash
dotnet run --project NotarEditor
```

## 📖 Verwendung

### Ordnerverwaltung
1. **Hauptansicht** zeigt alle Hauptordner als Karten
2. **Ordner erstellen** über Plus-Button (➕)
3. **Ordner öffnen** durch Klick auf Ordner-Karte
4. **Zurück-Navigation** über Zurück-Button (←)

### Navigation
- **Ordner-Karten-Ansicht**: Hauptordner als visuelle Karten
- **Listen-Ansicht**: Ordnerinhalt als strukturierte Liste
- **Doppelklick auf Unterordner**: Navigation in tiefere Ebenen
- **Rechtsklick**: Kontextmenü für Umbenennen/Löschen

### Einstellungen
- **Design-Modus**: Hell, Dunkel, System-Standard
- **Sprache**: Deutsch, English
- **Schriftart**: Konfigurierbare Standard-Schriftart
- **Word-Integration**: Ein/Ausschaltbar

## 🗂️ Projektstruktur

```
NotaEdit/
├── NotarEditor/
│   ├── MainWindow.xaml/.cs    # Hauptfenster
│   ├── SettingsWindow.xaml/.cs # Einstellungen
│   ├── ThemeManager.cs        # Theme-System
│   ├── AppSettings.cs         # Einstellungsverwaltung
│   ├── FolderItem.cs          # Ordner-Datenmodell
│   └── App.xaml/.cs           # App-Konfiguration
├── README.md
└── LICENSE
```

## 🤝 Beitragen

1. Fork das Projekt
2. Feature-Branch erstellen (`git checkout -b feature/AmazingFeature`)
3. Änderungen commiten (`git commit -m 'Add some AmazingFeature'`)
4. Branch pushen (`git push origin feature/AmazingFeature`)
5. Pull Request öffnen

## 📝 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe LICENSE für Details.

## 👤 Autor

**Entwickelt mit GitHub Copilot**

## 🛣️ Roadmap

### Version 2.0
- [ ] Rich-Text-Editor für Verträge
- [ ] Template-System mit Variablen
- [ ] Baustein-Verwaltung
- [ ] Drag & Drop-Funktionalität

### Version 2.1
- [ ] PDF-Export
- [ ] Word-Integration
- [ ] Vorschau-System
- [ ] Automatische Backups

### Version 2.2
- [ ] Multi-User-Support
- [ ] Versionsverwaltung
- [ ] Plugin-System
- [ ] Cloud-Synchronisation

## 🐛 Issues & Support

Bei Problemen oder Feature-Requests, bitte ein Issue erstellen.

## 🙏 Danksagungen

- Microsoft für .NET und WPF
- Community für Feedback und Beiträge
