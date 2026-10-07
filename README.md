# Gujarati Speech Emotion Recognition (SER) - Audio Recorder

A web-based audio recording application for collecting speech samples for Gujarati emotion recognition research.

---

## 🎯 Live Application

**📱 Access the app here:**
- **https://anjum-mansuri.github.io/gujarati-ser-recorder/**

---

## 📥 Direct Download

**Download HTML file:**
- **https://claude.ai/artifact/A6va4Q31LWXLLsyffmTixc**

---

## 📧 Submit Recordings

**Email collected audio files to:**
- **aymljku@gmail.com**

---

## ✨ Features

### Audio Recording
- ✅ Browser-based microphone recording
- ✅ Real-time audio level monitoring
- ✅ Support for all participant types (child 5-17, adult 18+)

### Audio Processing (48kHz WAV)
- ✅ Automatic resampling to 48kHz mono
- ✅ Audio normalization to optimal levels
- ✅ Quality checking (peak level analysis)
- ✅ WAV format output

### Data Collection
- ✅ Participant name (optional)
- ✅ Age validation
- ✅ Gender selection
- ✅ Gujarati dialect selection
- ✅ Emotion selection (7 emotions: Angry, Calm, Fearful, Happy, Neutral, Sad, Surprised)

### File Management
- ✅ Unique filenames: `{name}-{age}-{uniqueID}-48kHz.wav`
- ✅ Timestamp-based ID for traceability
- ✅ One-click download
- ✅ Audio playback preview

---

## 📝 Filename Format

```
{participant-name}-{age}-{uniqueID}-48kHz.wav
```

**Examples:**
- `Rajesh-28-1728315542123-a7f3-48kHz.wav`
- `Priya-32-1728315545890-k2x1-48kHz.wav`
- `child-12-1728315548234-m5n9-48kHz.wav`

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Audio Processing:** Web Audio API
- **Format:** WAV (48kHz, mono, 16-bit)
- **Hosting:** GitHub Pages
- **Browser Support:** Chrome, Firefox, Edge, Safari

---

## 📱 Supported Devices

- ✅ Desktop (Windows, Mac, Linux)
- ✅ Tablets (iPad, Android)
- ✅ Mobile phones (iPhone, Android)

---

## 🚀 How to Use

### For Participants

1. **Open the app:** https://anjum-mansuri.github.io/gujarati-ser-recorder/
2. **Enter your details:**
   - Name (optional)
   - Age
   - Gender
   - Gujarati dialect
3. **Select emotion** to express
4. **Record speech** (3-5 seconds recommended)
5. **Download WAV file**
6. **Email to researcher:** aymljku@gmail.com

### For Researchers

1. **Clone repository:**
   ```bash
   git clone https://github.com/anjum-mansuri/gujarati-ser-recorder.git
   ```

2. **Customize as needed:**
   - Edit `index.html` for modifications
   - Change participant instructions
   - Adjust emotion list or dialects

3. **Deploy:**
   - GitHub Pages automatically serves `index.html`
   - Or use any static hosting (Netlify, Vercel, etc.)

---

## 📊 Audio Quality Report

After recording, participants see:
- **Peak Level:** Audio loudness percentage (0-100%)
- **Duration:** Recording length in seconds
- **Format:** 48kHz Mono WAV
- **Warning:** Alert if audio is too quiet

---

## 🔐 Privacy & Data

- ✅ **No cloud upload** - All processing happens locally
- ✅ **No server storage** - Files stored only on participant's device
- ✅ **Participant control** - They decide when to download and share
- ✅ **Anonymous options** - Name is optional for adults

---

## 📚 Research Details

**Project:** Gujarati Speech Emotion Recognition (SER)  
**Institution:** LJ University  
**Researcher:** Dr. Anjum Mansuri  
**Contact:** aymljku@gmail.com  

---

## 🔗 Repository Links

- **GitHub Repo:** https://github.com/anjum-mansuri/gujarati-ser-recorder
- **Live App:** https://anjum-mansuri.github.io/gujarati-ser-recorder/
- **Download:** https://claude.ai/artifact/A6va4Q31LWXLLsyffmTixc

---

## 📝 Version History

- **v2.0** - Simplified filename format, name + age + unique ID
- **v1.0** - Initial release with preprocessing

---

## 💡 Technical Notes

- Audio is recorded in WebM format in browser
- Automatically converted to 48kHz mono WAV before download
- Normalization ensures consistent audio levels
- Quality check warns if recording is below recommended level
- Unique IDs prevent filename collisions

---

## 🤝 Contributing

For bug reports or feature requests, please contact the research team.

---

**Made with ❤️ for Gujarati language research**

Last updated: 2026-10-07
