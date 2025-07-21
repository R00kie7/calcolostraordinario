# 📊 Calcolo Straordinario

> **App Flutter gratuita per la gestione professionale degli orari di lavoro e il calcolo automatico degli straordinari**

[![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)](https://firebase.google.com)
[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](#)

## 🌟 Caratteristiche Principali

### ⏰ **Gestione Orari Avanzata**
- 📅 **Registrazione precisa** di entrate, uscite e pause
- 🌙 **Supporto turni notturni** con calcolo automatico
- ⚙️ **Orari flessibili** completamente personalizzabili
- 📊 **Dashboard intuitiva** con overview giornaliera

### 💼 **Calcolo Straordinari Intelligente**
- 🔢 **Algoritmi automatici** per straordinari feriali e festivi
- 💰 **Maggiorazioni personalizzabili** secondo contratto
- 📈 **Soglie configurabili** per attivazione straordinari
- ⚖️ **Conformità normative** del lavoro italiane

### 📊 **Reportistica Professionale**
- 📄 **Esportazione Excel/PDF** con template professionali
- 📈 **Grafici statistiche** mensili e annuali
- 📋 **Riepiloghi dettagliati** per periodo personalizzato
- 💾 **Storico completo** di tutti i dati inseriti

### ☁️ **Backup e Sincronizzazione**
- 🔐 **Google Drive integrato** con crittografia end-to-end
- 🔄 **Sincronizzazione automatica** multi-dispositivo
- 🛡️ **Privacy by design** - dati locali per default
- 🗑️ **Controllo completo** sui tuoi dati

### 🎨 **Esperienza Utente**
- 🌙 **Modalità scura/chiara** con cambio automatico
- 📱 **Design responsive** ottimizzato per tutti i dispositivi
- ⚡ **Performance elevate** con Flutter
- 🌍 **Completamente in italiano**

## 🚀 Installazione e Setup

### 📱 **Download da Google Play Store**
```
🔗 Scarica l'app UFFICIALE dal Google Play Store
💰 Completamente GRATUITO
🚫 Nessuna pubblicità invasiva
⚠️ ATTENZIONE: Scarica solo dalla fonte ufficiale per garantire sicurezza e aggiornamenti
```

### ⚠️ **Importante - Solo Uso Personale**
```
🛡️ Questa app è protetta da copyright
📱 Utilizzare SOLO la versione ufficiale dal Google Play Store  
🚫 È VIETATO modificare, redistribuire o creare versioni alternative
⚖️ Tutti i diritti riservati allo sviluppatore
```

## 📋 Funzionalità Dettagliate

### 🕐 **Tracciamento Orari**
| Funzione | Descrizione | Automazione |
|----------|-------------|-------------|
| **Entrata/Uscita** | Registrazione orari con timestamp preciso | ⚡ One-tap |
| **Pause** | Gestione pause pranzo e coffee break | 🔄 Automatiche |
| **Turni Notturni** | Calcolo corretto per turni oltre mezzanotte | ✅ Smart Logic |
| **Correzioni** | Modifica retroattiva orari errati | ✏️ Editing facile |

### 💰 **Calcoli Straordinari**
```dart
// Esempio algoritmo straordinario
if (oreLavorate > sogliaNormale) {
  straordinario = oreLavorate - sogliaNormale;
  if (isFestivo) {
    maggiorazione = straordinario * moltiplicatoreFestivo;
  } else {
    maggiorazione = straordinario * moltiplicatoreFeriale;
  }
}
```

### 📊 **Esportazione Dati**
- **📄 Formato Excel (.xlsx)** - Compatibile con tutte le versioni
- **📋 Formato PDF** - Report formattati professionalmente
- **📨 Invio diretto** via email o condivisione
- **🗓️ Filtri periodo** - Giornaliero, settimanale, mensile, personalizzato

## 🔧 Configurazione Avanzata

### ⚙️ **Impostazioni Orari di Lavoro**
```yaml
# Configurazione esempio
orario_standard:
  ore_giornaliere: 8
  giorni_settimanali: 5
  pausa_pranzo: 60  # minuti
  
straordinari:
  soglia_attivazione: 8  # ore
  maggiorazione_feriale: 1.25  # +25%
  maggiorazione_festiva: 1.50  # +50%
  maggiorazione_notturna: 1.30  # +30%

festivi:
  - "2024-01-01"  # Capodanno
  - "2024-04-25"  # Festa della Liberazione
  - "2024-05-01"  # Festa del Lavoro
  # ... altri festivi
```

### 🎨 **Personalizzazione Interfaccia**
- **🌈 Temi colore** - Predefiniti e personalizzabili
- **📱 Layout adattivo** - Ottimizzato per tablet e smartphone
- **⚡ Animazioni** - Fluide e responsive
- **🔤 Tipografia** - Leggibile e professionale

## 🛡️ Privacy e Sicurezza

### 🔒 **Principi di Privacy**
- **📱 Dati locali first** - Tutto funziona offline
- **🔐 Crittografia** - Protezione avanzata dei dati sensibili
- **✅ Consenso esplicito** - Per ogni condivisione dati
- **🗑️ Controllo totale** - Elimina i tuoi dati quando vuoi

### 🛠️ **Misure di Sicurezza**
```dart
// Esempio crittografia locale
final encryptedData = await CryptoUtils.encrypt(
  data: workTimeData,
  key: userDeviceKey,
  algorithm: AES256
);
```

### 📋 **Conformità Normative**
- **🇪🇺 GDPR** - Regolamento Generale Protezione Dati
- **🇮🇹 Privacy Code** - Decreto legislativo 196/2003
- **⚖️ Codice del Consumo** - Tutela consumatori
- **🏢 Normative lavoro** - CCNL e contrattazione

## 🧪 Testing e Qualità

### 🔬 **Test Suite Completa**
```bash
# Esecuzione test completi
flutter test

# Test con coverage
flutter test --coverage
genhtml coverage/lcov.info -o coverage/html

# Test integrazione
flutter drive --target=test_driver/app.dart
```

### 📊 **Metriche di Qualità**
- **✅ Test Coverage** > 90%
- **⚡ Performance Score** > 95/100
- **🔒 Security Audit** - Nessuna vulnerabilità critica
- **♿ Accessibility** - WCAG 2.1 AA compliant

## 🚀 Roadmap e Sviluppi Futuri

### 📅 **Versione 2.0 (Q2 2024)**
- [ ] 🤖 **Intelligenza Artificiale** - Predizione straordinari
- [ ] 📊 **Analytics avanzati** - Dashboard business intelligence
- [ ] 🔗 **API esterne** - Integrazione sistemi HR
- [ ] 📱 **App iOS** - Versione nativa per iPhone/iPad

### 🎯 **Versione 2.5 (Q4 2024)**
- [ ] ⌚ **Smartwatch support** - WearOS e Apple Watch
- [ ] 🌐 **Web dashboard** - Gestione da browser
- [ ] 👥 **Multi-user** - Gestione team e gruppi
- [ ] 🔄 **Auto-sync** - Sincronizzazione real-time

### 🚀 **Versione 3.0 (2025)**
- [ ] 🏢 **Enterprise features** - Soluzioni aziendali
- [ ] 🌍 **Localizzazione** - Supporto multi-lingua
- [ ] 🔧 **Plugin system** - Estensibilità modulare
- [ ] 📈 **Machine Learning** - Ottimizzazioni predittive

## 🤝 Supporto e Segnalazioni

###   **Supporto Tecnico**
- **Email principale:** [appdevmond@gmail.com](mailto:appdevmond@gmail.com)
- **Tempo risposta:** Entro 48h lavorative
- **Lingue:** Italiano, Inglese

### 🐛 **Segnalazione Bug e Suggerimenti**
Se riscontri problemi o hai suggerimenti per migliorare l'app:

```markdown
**Bug Report Template:**
- 📱 Dispositivo e versione Android
- 🔢 Versione app
- 📝 Passi per riprodurre
- 🎯 Comportamento atteso vs effettivo
- 📷 Screenshot (se applicabile)
```

**Invia a:** [appdevmond@gmail.com](mailto:appdevmond@gmail.com)

### 💡 **Richiesta Funzionalità**
```markdown
**Feature Request Template:**
- 🎯 Descrizione funzionalità
- 💪 Casi d'uso specifici
- 📊 Priorità e impatto stimato
```

## 🛠️ Stack Tecnologico

### 📱 **Frontend & Mobile**
- **Flutter** 3.16+ - Framework UI cross-platform
- **Dart** 3.0+ - Linguaggio di programmazione
- **Material Design 3** - Design system Google

### ☁️ **Backend & Cloud**
- **Firebase** - Backend as a Service
  - 📊 Analytics - Statistiche utilizzo
  - 🔐 Authentication - Login sicuro Google
  - ☁️ Cloud Storage - Backup file
- **Google Drive API** - Sincronizzazione dati

### 📦 **Dipendenze Principali**
```yaml
dependencies:
  flutter: sdk: flutter
  
  # State Management
  provider: ^6.1.1
  
  # Storage locale
  shared_preferences: ^2.2.2
  sqflite: ^2.3.0
  
  # Google Services
  google_sign_in: ^6.1.6
  google_mobile_ads: ^5.1.0
  firebase_core: ^2.24.2
  firebase_analytics: ^10.7.4
  
  # File Handling
  file_picker: ^6.1.1
  excel: ^2.1.0
  pdf: ^3.10.7
  
  # UI/UX
  fl_chart: ^0.66.0
  intl: ^0.19.0
```

### 🔧 **Tools e Development**
- **Android Studio** - IDE principale
- **VS Code** - Editor alternativo
- **Git** - Version control
- **GitHub Actions** - CI/CD pipeline
- **Firebase Console** - Gestione backend

## 📈 Statistiche e Metriche

### 📊 **Performance App**
```
⚡ Avvio app: < 2 secondi
💾 Dimensione APK: ~29.6 MB
🔋 Consumo batteria: Ottimizzato
📱 Memoria RAM: < 150 MB
```

### 📱 **Compatibilità**
- **Android** 5.0+ (API level 21+)
- **Architetture** ARM64, ARMv7, x86_64
- **Risoluzione** Adaptive (phone/tablet)
- **Orientamento** Portrait/Landscape

### 👥 **Community**
- **⭐ Utenti attivi** dell'app
- **📧 Feedback** e suggerimenti ricevuti
- **🐛 Bug report** risolti
- **  Download** dal Google Play Store

## 📞 Supporto e Contatti

### 📧 **Supporto Tecnico**
- **Email principale:** [appdevmond@gmail.com](mailto:appdevmond@gmail.com)
- **Lingue:** Italiano

### 🌐 **Risorse Online**
- **🏠 Sito Web:** [https://r00kie7.github.io/calcolo-straordinario-website/](https://fellowino.github.io/calcolo-straordinario-website/)
- **  Google Play Store:** [Scarica l'app ufficiale](#)
- **  Supporto:** [appdevmond@gmail.com](mailto:appdevmond@gmail.com)
- **  Feedback:** Invia suggerimenti via email

###
- **🛡️ Privacy Policy:** [privacy-policy.html](https://r00kie7.github.io/calcolo-straordinario-website/privacy-policy.html)
- **⚖️ Terms of Service:** [terms-of-service.html](https://r00kie7.github.io/calcolo-straordinario-website/terms-of-service.html)
- **🗑️ Account Deletion:** [account_deletion.html](https://r00kie.github.io/calcolo-straordinario-website/account_deletion.html)

## 📜 Licenza e Copyright

```
© 2024 App Dev Mond - Tutti i diritti riservati

LICENZA D'USO PER UTENTI FINALI:
- ✅ Permesso di utilizzo personale dell'app originale
- ✅ Download solo dal Google Play Store ufficiale
- ❌ VIETATA la modifica del codice sorgente
- ❌ VIETATA la redistribuzione in qualsiasi forma
- ❌ VIETATA la creazione di versioni derivate
- ❌ VIETATO il reverse engineering

L'app è fornita "così com'è" senza garanzie di alcun tipo.
Lo sviluppatore si riserva il diritto di modificare questi termini.

Per richieste commerciali o di licenza speciale:
📧 Contatta: appdevmond@gmail.com
```

## 🙏 Ringraziamenti

### 🛠️ **Tecnologie Open Source**
Questo progetto è possibile grazie a:
- **Flutter Team** - Framework incredibile
- **Google** - Servizi cloud e tools
- **Community Dart/Flutter** - Packages e supporto
- **GitHub** - Hosting e collaboration

---

<div align="center">

**📱 Scarica ora Calcolo Straordinario e trasforma la gestione dei tuoi orari di lavoro!**

[![Google Play](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white)](#)


</div>
