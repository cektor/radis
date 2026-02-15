# 📻 Radio Amateur Digital ID Query
### R.A.D.I.S.

**[English](#english) | [Türkçe](README-tr.md)**

<div align="center">

<img src="radioid.png" alt="App Logo" width="150"/>

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-Android-green.svg)
![License](https://img.shields.io/badge/license-MIT-orange.svg)
![API](https://img.shields.io/badge/API-24%2B-brightgreen.svg)

**The Ultimate Tool for Radio Amateurs to Query DMR, NXDN, Repeater IDs, and APRS Data**

**🆓 100% Free & Ad-Free Forever**

[Download](#download) • [Features](#features) • [Screenshots](#screenshots) • [Privacy](#privacy) • [Support](#support)

</div>

---

## 🌟 Why Choose This App?

Are you a radio amateur looking for a **fast, reliable, and privacy-focused** way to query digital IDs and APRS data? Look no further! Our application is specifically designed for the ham radio community with features that matter most to you.

### ✨ Key Highlights

- 🚀 **Lightning Fast** - Query DMR, NXDN, and Repeater IDs in seconds
- 📡 **APRS Integration** - Real-time APRS station tracking with QTH Locator calculation
- 🔒 **Privacy First** - No data collection, no tracking, no ads
- 📴 **Offline Mode** - Access your recent searches without internet
- 🌙 **Dark Theme** - Beautiful dark-first design for night operations
- 🆓 **100% Free** - No subscriptions, no in-app purchases

---

## 🎯 Features

### 📊 Digital ID Search

Query radio amateur information across multiple networks:

#### DMR ID Search
- Search by callsign or DMR ID
- View operator name, city, country
- Display last talk group activity
- Copy ID to clipboard with one tap

#### NXDN ID Search
- Complete NXDN database access
- Instant callsign lookup
- Detailed operator information

#### Repeater Database
- Search repeaters by ID or callsign
- View frequency, offset, and tones
- Find responsible operators
- Location information (city, country)

### 🗺️ APRS Features

Advanced APRS station tracking:

- **Real-time Position** - Latest station coordinates
- **QTH Locator** - Automatic Maidenhead grid calculation
- **APRS PassCode** - Generate passcode for any callsign
- **Map Integration** - Open station location in APRS.fi
- **SSID Support** - Automatic detection of -N, -1, -2, etc.
- **Station Info** - Comment, symbol, and last seen data

### 🔄 Smart Features

#### Offline Mode
- **24-hour cache** for DMR/NXDN/Repeater queries
- **1-hour cache** for APRS data (more dynamic)
- Automatic synchronization when online
- Visual offline indicator

#### Share & Export
- **Share Results** - Send via WhatsApp, Telegram, SMS, Email
- **QR Code Generation** - Create QR codes for any result
- **UTF-8 Support** - Perfect Turkish character handling
- **Copy to Clipboard** - Quick copy for IDs and passcodes

#### User Experience
- **Uppercase Input** - Automatic callsign formatting
- **Empty Field Validation** - Helpful error messages
- **Fast Navigation** - Bottom tab navigation
- **Clean Interface** - Minimal, distraction-free design

---

## 📱 Screenshots

### Main Screens

| ID Search | APRS Query | Results |
|-----------|------------|---------|
| ![ID Search](screenshots/id_search.png) | ![APRS](screenshots/aprs.png) | ![Results](screenshots/results.png) |

### Features in Action

| Offline Mode | QR Code | Share |
|--------------|---------|-------|
| ![Offline](screenshots/offline.png) | ![QR](screenshots/qr.png) | ![Share](screenshots/share.png) |

---

## 🚀 Getting Started

### Requirements

- Android 7.0 (API 24) or higher
- Internet connection (for queries)
- ~10 MB storage space

### Installation

#### Option 1: Google Play Store (Recommended)
```
Coming Soon!
```

#### Option 2: Direct APK Download
1. Download the latest APK from [Releases](https://github.com/yourusername/radio-amateur-id-query/releases)
2. Enable "Install from Unknown Sources" in Android settings
3. Install the APK
4. Open and start querying!

#### Option 3: Build from Source
```bash
# Clone the repository
git clone https://github.com/yourusername/radio-amateur-id-query.git

# Open in Android Studio
cd radio-amateur-id-query

# Build and run
./gradlew assembleDebug
```

---

## 🔧 Technical Details

### Built With

- **Kotlin** - Modern Android development
- **Jetpack Compose** - Declarative UI framework
- **Retrofit** - Type-safe HTTP client
- **Coroutines** - Asynchronous programming
- **ViewModel** - Lifecycle-aware data management
- **SharedPreferences** - Local data caching
- **ZXing** - QR code generation

### Architecture

- **MVVM Pattern** - Clean separation of concerns
- **Repository Pattern** - Data abstraction layer
- **Offline-First** - Cache-first strategy
- **Material Design** - Modern UI/UX principles

### Data Sources

#### RadioID.net API
- **Purpose:** DMR, NXDN, and Repeater database
- **Coverage:** Worldwide radio amateur database
- **Update Frequency:** Real-time
- **Data Type:** Public information

#### APRS.fi API
- **Purpose:** APRS station tracking
- **Coverage:** Global APRS-IS network
- **Update Frequency:** Real-time
- **API Key:** Read-only public access

---

## 🔒 Privacy & Security

### Our Commitment

- ✅ **No Data Collection** - We don't collect any user data
- ✅ **No Tracking** - No analytics or tracking services
- ✅ **No Ads** - Completely ad-free experience, forever
- ✅ **No Accounts** - No registration required
- ✅ **100% Free** - No subscriptions, no in-app purchases, no hidden costs
- ✅ **Local Storage Only** - Data cached on your device
- ✅ **HTTPS Only** - Secure API communications
- ✅ **Open Source** - Transparent codebase

### Permissions

The app requires only **TWO** permissions:

- **INTERNET** - To query RadioID.net and APRS.fi APIs
- **ACCESS_NETWORK_STATE** - To detect network connectivity and show online/offline status

**No other permissions needed!** No location, camera, contacts, or storage access.

### Data Handling

- **Search Queries:** Sent directly to third-party APIs (RadioID.net, APRS.fi)
- **Cache Storage:** Stored locally on your device (encrypted by Android OS)
- **Cache Duration:** 24 hours (IDs) / 1 hour (APRS)
- **User Control:** Clear cache by uninstalling the app

Read our full [Privacy Policy](privacy_policy.md)

### Legal Notice & Data Sources

**Important Information:**

All user and radio amateur information displayed in this application is legally retrieved from public databases:

- **RadioID.net** - Public DMR, NXDN, and Repeater database
- **APRS.fi** - Public APRS network data

This application acts solely as a query interface and does NOT store, collect, or maintain any user data on our servers. All information is:

- ✅ Publicly available through official radio amateur databases
- ✅ Retrieved in real-time from third-party APIs
- ✅ Temporarily cached locally on your device only
- ✅ Legally accessible under amateur radio regulations

**Data Removal Requests:**

If you wish to remove or modify your information:
- Contact **RadioID.net** directly for DMR/NXDN/Repeater data
- Contact **APRS.fi** directly for APRS data
- We cannot process removal requests as we do not store any data

**Terms of Use:**

By using this application, you acknowledge and agree that:
1. All data is sourced from public radio amateur databases
2. The application does not store personal data on external servers
3. Data removal requests must be directed to the original data sources
4. The application complies with amateur radio regulations and data protection laws

---

## 🌍 Supported Languages

- 🇬🇧 English
- 🇹🇷 Turkish (Türkçe)

---

## 📖 How to Use

### Searching Digital IDs

1. Open the app (starts on ID Search screen)
2. Enter a callsign (e.g., `TB1TFO`) or ID number (e.g., `2861059`)
3. Tap "Sorgula" (Query)
4. View results for DMR, NXDN, and Repeater databases
5. Tap the copy icon next to any ID to copy it

### Querying APRS Data

1. Navigate to "APRS Sorgula" tab
2. Enter a callsign (e.g., `TB1TFO`)
3. Tap "APRS Sorgula"
4. View station position, QTH Locator, and APRS PassCode
5. Tap "Haritada Görüntüle" to open in APRS.fi

### Sharing Results

1. After getting results, scroll to the bottom of the card
2. Tap "Paylaş" to share via any app
3. Or tap "QR Kod" to generate a QR code
4. Share with fellow radio amateurs!

### Offline Access

1. Query any callsign or ID while online
2. Results are automatically cached
3. When offline, search the same callsign
4. See cached results with offline indicator
5. Data refreshes automatically when back online

---

## 🤝 Contributing

We welcome contributions from the radio amateur community!

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Setup

```bash
# Prerequisites
- Android Studio Arctic Fox or later
- JDK 11 or higher
- Android SDK 35

# Clone and setup
git clone https://github.com/yourusername/radio-amateur-id-query.git
cd radio-amateur-id-query

# Open in Android Studio and sync Gradle
```

### Coding Guidelines

- Follow Kotlin coding conventions
- Use Jetpack Compose for UI
- Write meaningful commit messages
- Add comments for complex logic
- Test on multiple Android versions

---

## 🐛 Bug Reports & Feature Requests

Found a bug or have a feature idea? We'd love to hear from you!

### Reporting Bugs

Please include:
- Android version
- Device model
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

### Feature Requests

Tell us:
- What feature you'd like
- Why it would be useful
- How it should work

[Open an Issue](https://github.com/yourusername/radio-amateur-id-query/issues)

---

## 📞 Support

### Get Help

- 📧 **Email:** info@algyazilim.com
- 🌐 **Website:** https://algyazilim.com
- 💬 **Issues:** [GitHub Issues](https://github.com/yourusername/radio-amateur-id-query/issues)

### FAQ

**Q: Is this app free?**  
A: Yes! 100% free with no ads or in-app purchases.

**Q: Do I need to create an account?**  
A: No! The app works without any registration.

**Q: Does it work offline?**  
A: Yes! Recent searches are cached for offline access.

**Q: Which databases does it search?**  
A: RadioID.net (DMR, NXDN, Repeaters) and APRS.fi (APRS stations).

**Q: Is my data safe?**  
A: Absolutely! We don't collect any user data. Everything is stored locally on your device.

**Q: Can I use it outside Turkey?**  
A: Yes! It works worldwide for all radio amateurs.

---

## 👨‍💻 Developer

**ALG Yazılım & Elektronik Inc.**

- **Developer:** Fatih ÖNDER (TB1TFO - CekToR)
- **Email:** info@algyazilim.com
- **Website:** https://algyazilim.com

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

- **RadioID.net** - For providing the DMR/NXDN/Repeater database API
- **APRS.fi** - For the excellent APRS tracking service
- **Radio Amateur Community** - For feedback and support
- **Open Source Contributors** - For making this project better

---

## 🌟 Star History

If you find this app useful, please consider giving it a star! ⭐

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/radio-amateur-id-query&type=Date)](https://star-history.com/#yourusername/radio-amateur-id-query&Date)

---

## 📊 Stats

![GitHub stars](https://img.shields.io/github/stars/yourusername/radio-amateur-id-query?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/radio-amateur-id-query?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/yourusername/radio-amateur-id-query?style=social)

---

<div align="center">

**Made with ❤️ for the Radio Amateur Community**

**73!** 📻

[⬆ Back to Top](#-radio-amateur-digital-id-query)

</div>
