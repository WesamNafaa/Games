<div align="center">

# 🎮 Games-For-Kids | ألعاب تعليمية تفاعلية للأطفال

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Vanilla JS](https://img.shields.io/badge/Vanilla_JS_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Three.js](https://img.shields.io/badge/Three.js_WebGL-000000?style=for-the-badge&logo=threedotjs&logoColor=white)](https://threejs.org/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Procedural_Synth-22d3ee?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![Bilingual](https://img.shields.io/badge/Languages-العربية_&_English-10b981?style=for-the-badge)](#)

**مجموعة ألعاب ويب تعليمية تفاعلية تعمل مباشرة على المتصفحات والهواتف الذكية والأجهزة اللوحية دون الحاجة لأي تثبيت أو أدوات بناء، مصمّمة لتعليم الأطفال الحروف العربية (٢٨ حرفاً) والإنجليزية (26 حرفاً) والأشكال الهندسية والمفردات بالصوت والصورة.**

*A curated suite of interactive, zero-build educational browser and mobile games engineered to teach children the Arabic (28 letters) and English (26 letters) alphabets, 3D shapes, and vocabulary through interactive play, speech synthesis, and procedural audio.*

**التطوير والنشر | Developed & Published by:** **Wesam Nafaa - وسام نفاع**

</div>

---

## 🗂️ شجرة المستودع | Repository Structure

```text
Games-For-Kids/
├── README.md                              # ملف التوثيق العام للمستودع (هذا الملف)
├── Letter-Basket/                         # المشروع الأول: سلة الحروف (محرك ثنائي الأبعاد 2D Canvas)
│   ├── index.html                         # التطبيق الكامل للعبة سلة الحروف 2D
│   ├── favicon.svg                        # أيقونة المتصفح المتجهة (Vector Favicon)
│   ├── favicon-32.png                     # أيقونة المتصفح القياسية (32x32)
│   ├── apple-touch-icon.png               # أيقونة الشاشة الرئيسية لأجهزة iOS/Android (180x180)
│   └── README.md                          # التوثيق التفصيلي لمشروع سلة الحروف 2D
└── Smart-Letters-Shapes-Basket/           # المشروع الثاني: سلّة الحروف والأشكال الذكية (محرك ثلاثي الأبعاد 3D WebGL)
    ├── index.html                         # التطبيق الكامل للعبة ثلاثية الأبعاد (Three.js + GLB + Procedural Icons)
    └── README.md                          # التوثيق التفصيلي لمشروع سلّة الحروف والأشكال الذكية 3D
```

---

## 🧩 نظرة تفصيلية على المشاريع | Included Projects

### 1. مشروع [`Letter-Basket`](./Letter-Basket/) — سلة الحروف (الإصدار ثنائي الأبعاد 2D)
* **المسار:** `./Letter-Basket/index.html`
* **التقنية الأساسية:** محرك رسوميات **HTML5 Canvas 2D** بلغة **Vanilla JavaScript** خالصة مع واجهة زجاجية (`Glassmorphism`) وأصول أيقونات كاملة (`SVG` و `PNG`).
* **وصف التجربة:** لعبة التقاط تفاعلية مرحة يقوم فيها الطفل بتحريك سلة ذات تعابير وجه حية (تتبع عيناها العناصر، تبتسم، وتحزن) لالتقاط الحرف الأول أو الصورة المطابقة عبر مستويات متدرجة السرعة. تتضمن نظام محاولات من ٣ قلوب، وتأخيراً ذكياً يمنع سقوط العنصر الصحيح أولاً، وزر مساعدة **«إيجاد 🔍»** يضيء الهدف ويوجه الطفل إليه، مع حفظ الأرقام القياسية لكل لغة ولكل نمط لعب محلياً.

### 2. مشروع [`Smart-Letters-Shapes-Basket`](./Smart-Letters-Shapes-Basket/) — سلّة الحروف والأشكال الذكية (الإصدار ثلاثي الأبعاد 3D)
* **المسار:** `./Smart-Letters-Shapes-Basket/index.html`
* **التقنية الأساسية:** محرك **Three.js r160 (WebGL 3D)** مع **GLTFLoader**، وفيزياء تصادم مستمرة (`Swept-Y Collision`)، وتوليد ديناميكي للأيقونات وملف `PWA Manifest` داخل ملف واحد ذاتي الاكتفاء.
* **وصف التجربة:** عالم تفاعلي ثلاثي الأبعاد متكامل يدمج مجسمات **GLB** مفتوحة المصدر متحركة (روبوت تفاعلي يرقص ويقفز ويلوّح حسب أداء الطفل، وبطة، وطيور محلّقة في السماء) مع ٦ أشكال هندسية ثلاثية الأبعاد لامعة (نجمة، مكعب، جوهرة، حلقة، سداسي، قلب). يتيح المشروع **تحكماً مزدوجاً** (تحريك السلة أفقياً أو لمس وسحب الأشكال في منتصف الهواء مباشرة نحو السلة)، وموزّع موجات ذكي من ٥ خانات، وتحكماً حياً في السرعة، وخريطة حروف تفاعلية، وشعاع جذب مغناطيسي ثلاثي الأبعاد (**«زر إيجاد 🔍»**).

---

## 📊 مقارنة سريعة بين المشروعين | Quick Comparison

| وجه المقارنة / Feature | `Letter-Basket` (2D) | `Smart-Letters-Shapes-Basket` (3D) |
| :--- | :--- | :--- |
| **المحرك الرسومي** | HTML5 2D Canvas + Offscreen Sprite Cache | Three.js r160 WebGL + ACESFilmic Tone Mapping |
| **البنية والملفات** | `index.html` + أصول أيقونات (`svg` / `png`) | ملف واحد ذاتي الاكتفاء `index.html` (توليد أيقونات برمجي) |
| **المنهج التعليمي** | 28 حرفاً عربياً + 26 حرفاً إنجليزياً | 28 حرفاً عربياً + 26 حرفاً إنجليزياً + 6 أشكال هندسية |
| **أنماط اللعب** | ٣ أنماط (حرف من صورة، صورة من حرف، خليط) | ٣ أنماط (حرف من صورة، صورة من حرف، خليط) |
| **أسلوب التحكم** | سحب السلة باللمس/الماوس أو لوحة المفاتيح | سحب السلة **أو** التقاط الأشكال في الهواء (`3D Raycasting`) |
| **زر المساعدة «إيجاد 🔍»** | شحن دائري حتى 100% لإضاءة الهدف وتعتيم البقية | شحن 100% أو استبدال `2 💎` لإطلاق شعاع جذب مغناطيسي 3D |
| **نظام التقدم** | مستويات متصاعدة + ٣ قلوب + تقييم نجوم | خريطة حروف تفاعلية + جواهر ومكافآت + تقييم دقة |
| **الصوتيات والنطق** | `Web Audio API` (موسيقى ومؤثرات) + `SpeechSynthesis` | `Web Audio API` (موسيقى ومؤثرات) + `SpeechSynthesis` |

---

## 🚀 التشغيل والنشر | Getting Started & Deployment

1. **التشغيل المحلي المباشر:**
   * افتح `Letter-Basket/index.html` أو `Smart-Letters-Shapes-Basket/index.html` مباشرة في أي متصفح حديث.
2. **التشغيل عبر خادم محلي (موصى به لتفعيل كامل ميزات PWA و ES Modules):**
   ```bash
   git clone [https://github.com/](https://github.com/)<username>/Games-For-Kids.git
   cd Games-For-Kids
   npx serve .
   ```
3. **النشر عبر GitHub Pages:**
   * عند تفعيل **GitHub Pages** للمستودع، يعمل كل مشروع على مساره المستقل مباشرة:
     * `https://<username>.github.io/Games-For-Kids/Letter-Basket/`
     * `https://<username>.github.io/Games-For-Kids/Smart-Letters-Shapes-Basket/`

---

## 👨‍💻 حقوق الملكية والنشر | Author & Copyright

* **التطوير والنشر (Developed & Published by):** **Wesam Nafaa - وسام نفاع**
* **© 2026 Wesam Nafaa - وسام نفاع. جميع الحقوق محفوظة.**
