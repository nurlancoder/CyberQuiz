# 🔒 CyberQuiz Pro - Kibertəhlükəsizlik Bilik Testi

<div align="center">

![CyberQuiz Pro](https://img.shields.io/badge/Version-2.0-00ff88?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-00ccff?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Kibertəhlükəsizlik sahəsində biliklərini yoxla və inkişaf etdir!**

[Demo](https://nurlancoder.github.io/CyberQuiz) • [Xüsusiyyətlər](#-xüsusiyyətlər) • [Quraşdırma](#-quraşdırma) • [İstifadə](#-istifadə)

</div>

---

## 📖 Haqqında

**CyberQuiz Pro** - kibertəhlükəsizlik sahəsində biliklərini test etmək və inkişaf etdirmək üçün interaktiv, müasir dizaynlı quiz platformasıdır. Tələbələr, IT mütəxəssisləri və kibertəhlükəsizlik sahəsi ilə maraqlananlara yönəlib.

### 🎯 Məqsəd

- 📚 Kibertəhlükəsizlik sahəsində bilikləri artırmaq
- 🎓 Özünü sınamaq və zəif cəhətləri müəyyən etmək
- 🏆 Rəqabətli mühitdə öyrənmək
- 📊 İrəliləyişi izləmək və statistikaya baxmaq

---

## ✨ Xüsusiyyətlər

### 🎨 Interfeys
- ✅ Modern, responsive dizayn (mobil, tablet, desktop)
- ✅ Dark mode interfeys
- ✅ Animasiyalı keçidlər və effektlər
- ✅ Dinamik hissəcik (particle) animasiyaları
- ✅ Smooth scroll və hover effektləri
- ✅ Gradient və glassmorphism dizayn elementləri

### 📚 Kontent
- ✅ **30+ kibertəhlükəsizlik suali** 5 kateqoriyada
- ✅ **5 əsas kateqoriya:**
  - 🌐 Network Security (Şəbəkə təhlükəsizliyi)
  - 🦠 Malware & Viruses (Zərərli proqramlar)
  - 🔐 Cryptography (Kriptoqrafiya)
  - 🎭 Social Engineering (Sosial mühəndislik)
  - 🌍 Web Security (Veb təhlükəsizliyi)
- ✅ Hər sual üçün ətraflı izahlar
- ✅ Azərbaycan dilində tam dəstək

### ⚡ Funksionallıq
- ✅ **3 çətinlik səviyyəsi:** Asan, Orta, Çətin
- ✅ **Vaxt limitli suallar** (30/20/15 saniyə)
- ✅ **Real-time progress bar** və statistika
- ✅ **Səs effektləri** (aktiv/deaktiv edilə bilər)
- ✅ **LocalStorage** ilə nəticələrin saxlanması
- ✅ **Leaderboard sistemi** (ən yaxşı 10 nəticə)
- ✅ **Paylaşma funksiyası** (Telegram, WhatsApp, Twitter)
- ✅ **Detailed results view** - bütün cavabların təhlili

### 🎮 İstifadəçi Təcrübəsi
- ✅ Responsive dizayn - bütün cihazlarda işləyir
- ✅ Keyboard navigasiya dəstəyi
- ✅ Visual feedback (doğru/yanlış cavab animasiyaları)
- ✅ Timer warning sistemi (vaxt bitəndə xəbərdarlıq)
- ✅ Auto-scroll funksiyası
- ✅ Progress tracking

---

## 🚀 Quraşdırma

### Tələblər
- Modern veb brauzer (Chrome, Firefox, Safari, Edge)
- İnternet bağlantısı (ilk yükləmə üçün)

### Lokal İstifadə

1. **Layihəni klonlayın:**
```bash
git clone https://github.com/nurlancoder/CyberQuiz.git
cd CyberQuiz
```

2. **Faylı açın:**
```bash
# Sadəcə index.html faylını brauzerdə açın
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### GitHub Pages ilə Deploy

1. GitHub-da repository yaradın
2. Faylları yükləyin
3. Settings → Pages → Source: main branch seçin
4. Saytınız `https://username.github.io/CyberQuiz` ünvanında açılacaq

### Netlify/Vercel ilə Deploy

**Netlify:**
```bash
# Netlify CLI quraşdırın
npm install -g netlify-cli

# Deploy edin
netlify deploy --prod
```

**Vercel:**
```bash
# Vercel CLI quraşdırın
npm install -g vercel

# Deploy edin
vercel --prod
```

---

## 📱 İstifadə

### İlk Başlama

1. **Səhifəni açın** - `index.html` faylını brauzerdə açın
2. **Kateqoriya seçin** - 5 kateqoriyadan birini və ya "Hamısı"nı seçin
3. **Çətinlik səviyyəsi** - Asan, Orta və ya Çətin seçin
4. **"Başla" düyməsi** - Quiz-i başladın

### Quiz Zamanı

- ⏱️ **Vaxt limiti:** Hər sual üçün müəyyən vaxt var
- 🎯 **Cavab seçimi:** A, B, C və ya D variant seçin
- 💡 **İzah:** Cavab verdikdən sonra izah göstərilir
- ⏭️ **Növbəti sual:** "Növbəti Sual" düyməsi ilə davam edin

### Nəticələr

- 📊 **Statistika:** Doğru/yanlış cavablar, ümumi vaxt
- 🏆 **Performance badge:** Nəticəyə görə medal
- 📈 **Leaderboard:** Ən yaxşı 10 nəticə
- 📤 **Paylaşma:** Sosial mediada paylaş
- 🔄 **Yenidən başlama:** Yeni quiz başlat

---

## 🎓 Quiz Strukturu

### Kateqoriyalar və Suallar

| Kateqoriya | Sual Sayı | Çətinlik |
|-----------|-----------|----------|
| Network Security | 8+ | Easy-Hard |
| Malware & Viruses | 8+ | Easy-Hard |
| Cryptography | 8+ | Easy-Hard |
| Social Engineering | 8+ | Easy-Hard |
| Web Security | 8+ | Easy-Hard |

### Çətinlik Səviyyələri

- 🟢 **Asan (Easy):** 30 saniyə, əsas anlayışlar
- 🟡 **Orta (Medium):** 20 saniyə, texniki məlumatlar
- 🔴 **Çətin (Hard):** 15 saniyə, mürəkkəb ssenarilar

### Qiymətləndirmə Sistemi

| Faiz | Badge | Qiymət |
|------|-------|--------|
| 90-100% | 🥇 ƏLAAA! | Mükəmməl bilik |
| 70-89% | 🥈 ÇOX YAXŞI! | Yaxşı bilik |
| 50-69% | 🥉 YAXŞI! | Əsas bilik |
| 0-49% | 📚 DAVAM ET! | Təkmilləşdirmə lazımdır |

---

## 🛠️ Texniki Detallar

### Texnologiyalar

- **HTML5** - Struktur və semantik markup
- **CSS3** - Animations, Gradients, Flexbox, Grid
- **Vanilla JavaScript** - Logic və interaktivlik
- **LocalStorage API** - Məlumatların saxlanması
- **Web Audio API** - Səs effektləri

### Fayl Strukturu

```
CyberQuiz/
│
├── index.html          # Əsas HTML fayl
├── README.md           # Sənədləşmə
├── LICENSE            # MIT Lisenziya
│
└── assets/            # (optional)
    ├── images/
    └── sounds/
```

### Brauzer Dəstəyi

| Brauzer | Minimum Versiya |
|---------|----------------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |
| Opera | 76+ |

---

## 📊 Xüsusiyyətlərin Detallı Təsviri

### 1. LocalStorage İstifadəsi

```javascript
// Nəticələrin saxlanması
localStorage.setItem('bestScore', percentage);
localStorage.setItem('leaderboard', JSON.stringify(leaderboard));

// Oxunması
const bestScore = localStorage.getItem('bestScore');
const leaderboard = JSON.parse(localStorage.getItem('leaderboard'));
```

### 2. Səs Sistemi

```javascript
// Web Audio API ilə real-time səs generasiyası
const audioContext = new AudioContext();
const oscillator = audioContext.createOscillator();
// Doğru/yanlış cavab üçün fərqli tezliklər
```

### 3. Timer Mexanizmi

```javascript
// Çətinlik səviyyəsinə görə vaxt
const timeLimit = {
  easy: 30,
  medium: 20,
  hard: 15
};
```

### 4. Progress Tracking

```javascript
// Real-time progress hesablama
const progress = (currentQuestion / totalQuestions) * 100;
progressBar.style.width = progress + '%';
```

---

## 🎨 Dizayn Prinsipləri

### Rəng Paleti

```css
/* Əsas rənglər */
Primary: #00ff88    /* Yaşıl neon */
Secondary: #00ccff  /* Mavi neon */
Accent: #ffaa00     /* Narıncı */
Danger: #ff0066     /* Qırmızı */
Background: #0a0e27 /* Tünd göy */
```

### Animasiyalar

- **Particle System** - 50 dinamik hissəcik
- **Glow Effects** - Neon parlama effektləri
- **Smooth Transitions** - 0.3s ease keçidlər
- **Hover Effects** - Scale və transform
- **Loading Animations** - Pulse və rotate

---

## 🤝 Töhfə Vermək (Contributing)

Töhfələriniz xoş qarşılanır! Layihəni təkmilləşdirmək üçün:

1. **Fork edin** bu repository-ni
2. **Branch yaradın** (`git checkout -b feature/YeniXususiyyet`)
3. **Commit edin** (`git commit -m 'Yeni xüsusiyyət əlavə edildi'`)
4. **Push edin** (`git push origin feature/YeniXususiyyet`)
5. **Pull Request açın**

### Töhfə Sahələri

- 📝 Yeni suallar əlavə etmək
- 🌍 Digər dillərə tərcümə
- 🎨 Dizayn təkmilləşdirmələri
- 🐛 Bug fix-lər
- 📚 Sənədləşdirmənin genişləndirilməsi
- ⚡ Performance təkmilləşdirmələri

---

## 📝 Yeni Sual Əlavə Etmək

### Format

```javascript
{
    question: "Sualın mətni?",
    options: [
        "A) Variant 1",
        "B) Variant 2", 
        "C) Variant 3",
        "D) Variant 4"
    ],
    correct: "B",  // Doğru cavab (A, B, C və ya D)
    explanation: "Cavabın izahı.",
    difficulty: "medium"  // easy, medium və ya hard
}
```

### Nümunə

```javascript
// quizData obyektinə əlavə edin
network: [
    {
        question: "SSH protokolu hansı portu istifadə edir?",
        options: [
            "A) 21",
            "B) 22",
            "C) 23",
            "D) 25"
        ],
        correct: "B",
        explanation: "SSH (Secure Shell) protokolu 22 nömrəli portu istifadə edir.",
        difficulty: "medium"
    }
]
```

---

## 🐛 Məlum Məsələlər (Known Issues)

- ⚠️ Safari-də bəzi səs effektləri işləməyə bilər
- ⚠️ Çox köhnə brauzerlərdə CSS Grid dəstəyi olmaya bilər
- ⚠️ iOS-da LocalStorage limiti 5-10MB

---

## 🔮 Gələcək Planlar (Roadmap)

- [ ] **Multiplayer Mode** - Dostlarla rəqabət
- [ ] **AI Quiz Generator** - Süni intellekt ilə sual yaratma
- [ ] [ ] **Certificate System** - PDF sertifikat yaratma
- [ ] **Dark/Light Mode Toggle** - Tema dəyişdirmə
- [ ] **English Version** - İngilis dili dəstəyi
- [ ] **Backend Integration** - Server tərəfli məlumat saxlama
- [ ] **Mobile App** - React Native versiya
- [ ] **Advanced Analytics** - Ətraflı statistika dashboard
- [ ] **Topic-based Learning** - Mövzular üzrə öyrənmə
- [ ] **Quiz Creator** - İstifadəçilər öz quiz-lərini yarada bilsin

---

## 📜 Lisenziya

Bu layihə **MIT Lisenziyası** altında lisenziyalaşdırılıb. Ətraflı məlumat üçün [LICENSE](LICENSE) faylına baxın.

```
MIT License

Copyright (c) 2024 Nurlan Coder

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

---

## 👨‍💻 Müəllif

**Nurlan Coder**

- 🌐 GitHub: [@nurlancoder](https://github.com/nurlancoder)
- 💼 LinkedIn: [Nurlan](https://linkedin.com/in/nurlancoder)
- 📧 Email: nurlan@example.com
- 🐦 Twitter: [@nurlancoder](https://twitter.com/nurlancoder)

---

## 🙏 Təşəkkür

Bu layihənin hazırlanmasında köməyi olan:

- **OWASP** - Kibertəhlükəsizlik bilikləri
- **MDN Web Docs** - Veb texnologiyaları sənədləri
- **GitHub Community** - Açıq mənbə dəstəyi
- **Azerbaijan Cyber Security Community** - Sualların yoxlanması

---

## 📞 Əlaqə və Dəstək

### Problem bildirmək

GitHub Issues vasitəsilə problem bildirin:
1. [Issues](https://github.com/nurlancoder/CyberQuiz/issues) səhifəsinə gedin
2. "New Issue" düyməsini klikləyin
3. Problemi ətraflı təsvir edin

### Suallar

- 💬 **Discord:** [CyberQuiz Community](https://discord.gg/cyberquiz)
- 📧 **Email:** support@cyberquiz.az
- 💬 **Telegram:** [@CyberQuizAZ](https://t.me/CyberQuizAZ)

---

## 📈 Statistika

![GitHub Stars](https://img.shields.io/github/stars/nurlancoder/CyberQuiz?style=social)
![GitHub Forks](https://img.shields.io/github/forks/nurlancoder/CyberQuiz?style=social)
![GitHub Issues](https://img.shields.io/github/issues/nurlancoder/CyberQuiz)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/nurlancoder/CyberQuiz)

---

## 🌟 Star History

Əgər layihə xoşunuza gəlibsə, ⭐ verməyi unutmayın!

```
⭐ Star layihəni - Daha çox adamın görməsi üçün
🔀 Fork edin - Öz versiyınızı yaradın
📢 Paylaşın - Dostlarınızla bölüşün
```

---

<div align="center">

**CyberQuiz Pro ilə Kibertəhlükəsizlik biliklərini inkişaf etdir! 🚀**

Made with ❤️ by [Nurlan Coder](https://github.com/nurlancoder)

[⬆ Yuxarı qalx](#-cyberquiz-pro---kibertəhlükəsizlik-bilik-testi)

</div>
