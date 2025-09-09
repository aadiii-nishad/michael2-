# Telegram चैनल — GitHub Pages Landing Page (Template)

यह टेम्पलेट आपको अपने Telegram चैनल के लिए एक **सादा, तेज़ और सुंदर** लैंडिंग पेज GitHub Pages पर बनाने में मदद करेगा।

## कैसे इस्तेमाल करें (Step-by-step)

### 1) तैयारी
- अपना Telegram चैनल यूज़रनेम नोट करें — जैसे `YOUR_CHANNEL_USERNAME`.
- अपना GitHub अकाउंट लॉग‑इन करें।

### 2) GitHub पर नई रेपो बनाएं
- **Option A (Personal site):** repo का नाम रखें: `YOUR_GITHUB_USERNAME.github.io`  
  इस नाम से पेज अपने‑आप `https://YOUR_GITHUB_USERNAME.github.io/` पर खुलेगा।
- **Option B (Project site):** कोई भी नाम रख सकते हैं, जैसे `telegram-landing`.  
  ये `https://YOUR_GITHUB_USERNAME.github.io/telegram-landing/` पर खुलेगा।

### 3) इस टेम्पलेट को अपलोड करें
- इस ZIP को डाउनलोड करें और अनज़िप करें।
- फोल्डर की फाइलें (`index.html`, `styles.css`, `assets/*`) अपनी नयी GitHub रेपो में अपलोड करें।
- `index.html` में यह 3 जगहें बदलें:
  - `@YOUR_CHANNEL_USERNAME` → `@yourchannel`
  - `tg://resolve?domain=YOUR_CHANNEL_USERNAME` → `tg://resolve?domain=yourchannel`
  - `https://t.me/YOUR_CHANNEL_USERNAME` → `https://t.me/yourchannel`
  - चाहें तो `<title>` और टेक्स्ट भी बदलें।

### 4) GitHub Pages ऑन करें (अगर प्रोजेक्ट साइट है)
- **Settings → Pages** में जाएँ
- **Build and deployment → Source**: `Deploy from a branch`
- **Branch**: `main` (root) चुनें और **Save** करें
- 1–2 मिनट बाद आपका पेज लाइव हो जाएगा।

> Personal site (username.github.io) के लिए अक्सर कुछ भी सेट करने की जरूरत नहीं पड़ती — बस `main` ब्रांच में फाइलें हों।

### 5) टेस्ट करें
- डेस्कटॉप और मोबाइल, दोनों पर पेज खोलकर देखें।
- “Telegram ऐप में खोलें” बटन पर क्लिक करने पर अगर ऐप खुलता नहीं है, तो स्क्रिप्ट अपने‑आप वेब लिंक पर ले जाएगी।

### 6) कस्टम डोमेन (ऐच्छिक)
- **Settings → Pages → Custom domain** में अपना डोमेन डालें (e.g. `link.mydomain.in`)
- अपने DNS में `CNAME` रिकॉर्ड जोड़ें: `link.mydomain.in` → `YOUR_GITHUB_USERNAME.github.io`
- रेपो रूट में `CNAME` फाइल बन जाए तो ठीक है।

## फाइल स्ट्रक्चर
```
/
├─ index.html      # पेज मार्कअप (लिंक्स, मेटा, ओपन‑ग्राफ)
├─ styles.css      # मिनिमल, मॉडर्न स्टाइल्स
└─ assets/
   ├─ telegram.svg # लोगो
   ├─ favicon.png  # छोटा आइकन (आप बदल सकते हैं)
   └─ cover.png    # शेयर‑इमेज (OG/Twitter)
```

## टिप्स
- OG इमेज `assets/cover.png` को अपने ब्रांड के हिसाब से बदलें ताकि शेयर प्रीव्यू अच्छा दिखे।
- चैनल लिंक में `?start=utm` जैसे पैरामीटर जोड़कर ट्रैकिंग कर सकते हैं।
- पेज का टेक्स्ट छोटा, स्पष्ट रखें — कन्वर्ज़न बेहतर होगा।

शुभकामनाएँ! 🙌
