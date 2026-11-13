<p align="center">
  <img src="assets/logo.png" width="108" height="108" alt="Wazen App Icon" />
</p>

<h1 align="center">Wazen · وازن</h1>

<p align="center">
  <strong>Cross-Platform Native AI Nutrition, Meal Vision, Diabetes CGM &amp; Fitness Platform</strong><br>
  <em>Native iOS (SwiftUI + watchOS + WidgetKit) &bull; Native Android (Kotlin + Jetpack Compose + Health Connect) &bull; Django REST &amp; Cloudflare Edge</em>
</p>

<p align="center">
  <a href="https://wazenai.com"><strong>🌐 Website (wazenai.com)</strong></a> &nbsp;&bull;&nbsp;
  <a href="https://apps.apple.com/app/wazen-%D9%88%D8%A7%D8%B2%D9%86/id6760981534"><strong>🍎 App Store (iOS 17.6+)</strong></a> &nbsp;&bull;&nbsp;
  <a href="https://play.google.com/store/apps/details?id=com.wazen.health.wazen_app"><strong>🤖 Google Play (Android 8.0+)</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/iOS-SwiftUI_17.6+-0F172A?style=flat-square&logo=apple&logoColor=white" alt="iOS SwiftUI" />
  <img src="https://img.shields.io/badge/watchOS-Companion_+_Widgets-0284C7?style=flat-square&logo=apple&logoColor=white" alt="watchOS" />
  <img src="https://img.shields.io/badge/Android-Kotlin_+_Compose-059669?style=flat-square&logo=android&logoColor=white" alt="Android Jetpack Compose" />
  <img src="https://img.shields.io/badge/Backend-Django_5_%2B_DRF_%2B_Celery-092E20?style=flat-square&logo=django&logoColor=white" alt="Django Backend" />
  <img src="https://img.shields.io/badge/Edge-Cloudflare_Workers_(TS)-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare Workers" />
  <img src="https://img.shields.io/badge/Locales-AR_%7C_EN_%7C_FR_%7C_DE_%7C_ES-6366F1?style=flat-square" alt="5 Languages" />
</p>

<p align="center">
  <img src="assets/hero-banner.png" width="100%" alt="Wazen AI Nutrition & Health Feature Graphic" />
</p>

> [!NOTE]
> **Portfolio & Architecture Showcase:** Wazen is a shipped commercial production product on the [Apple App Store](https://apps.apple.com/app/wazen-%D9%88%D8%A7%D8%B2%D9%86/id6760981534) and [Google Play](https://play.google.com/store/apps/details?id=com.wazen.health.wazen_app). Source code is kept in a private repository; this public repository presents the product architecture, engineering scope, technology stack, and live UI showcase.

---

## 👤 Role & Project Scope

* **Role:** Full-Stack Mobile Architect & Product Engineer ([Salim Moussaoui](https://github.com/salimmous))
* **Production Platforms Shipped:** iOS App (`v2.0.2`), Apple Watch companion + WidgetKit extensions, Android App (`v7.9`), Django API server, Cloudflare Workers Edge AI gateway, and multilingual SEO/GEO web portal (`wazenai.com`).
* **AI-Accelerated Delivery:** End-to-end architecture, native dual-platform UI/UX parity, backend ingestion/queues, and automated release pipelines.

---

## 🚀 What Wazen Does (Core Capabilities)

### 1. 📸 AI Meal Vision, Portion Editing & Barcode Scanning
* **Instant Meal Recognition:** Captures food photos and decomposes dishes into structured ingredients, gram weights, calories, macros, fiber, vitamins, and minerals.
* **Regional & Mixed Cuisine Calibration:** Tuned specifically for complex Middle Eastern, North African, Gulf, Levantine, Egyptian, and international dishes (*Tagine, Couscous, Harira, Kabsa, Shawarma, Machboos, Koshari, home stews*) including cooking oils and hidden sauces.
* **Interactive Ingredient & Gram Editor:** Quick-edit numbered pins, inline weight stepper presets, drink/main meal flows, and oil/sauce adjustments in one tap.
* **Barcode (`GTIN`) Scanner:** Native camera scanning (`CameraX` + `ML Kit` on Android, `AVFoundation` on iOS) with packaged ingredient breakdown.

### 2. 💬 Real-Time Voice, Text & Coach Telemetry
* **Conversational AI Nutrition Coach:** Bidirectional voice and text chat grounded in the user's actual calorie budget, weight trend, macros, and workout logs.
* **Natural Language Meal Logging:** Log meals by voice or free-text descriptions across **5 supported languages** (`Arabic RTL`, `English`, `French`, `German`, `Spanish`).
* **Multi-Model Routing:** Hosted Cloudflare Workers AI gateway (`TypeScript`, streaming audio & vision payloads, credit/usage ledger) alongside user-configurable provider routing (`LiteRTLM` on-device + cloud models).

### 3. 🩸 Diabetes & Blood Glucose Hub (CGM + Safe Fasting)
* **Daily Glucose Telemetry:** Live CGM trend summary (`mg/dL`, Time-in-Range `%`, min/peak metrics) and manual fingerstick logging synced via **Apple HealthKit** & **Android Health Connect**.
* **Meal-Spike Attribution:** Correlates post-meal glycemic rises with exact logged meals and provides actionable nutritional guidance.
* **Safe Fasting, Ramadan Mode & Companion Alerts:** Built-in intermittent fasting & Ramadan schedules with safety thresholds, daily vitamin/supplement tracking, and caregiver/companion emergency notifications.

### 4. 🏋️ Workouts Library, Smart Budget & Community
* **875+ Illustrated Exercises:** Categorized by muscle group, equipment, and difficulty with full Arabic instructions, in-app exercise video playback, sets/reps/RPE tracking, and burnt-calorie syncing.
* **Smart Food Budget & Grocery Planner:** Generates balanced meal plans calibrated to a daily food budget and regional currency.
* **Wazen Community & Ecosystem Integration:** Community feed, Apple Watch standalone companion (`watchOS`), Interactive Lock Screen / Home Screen widgets (`WidgetKit` & Android `Glance`), local push reminders (`WorkManager` / `FCM` / `APNs`).

---

## 📱 Product Showcase (Live Light-Mode UI)

<table align="center">
  <tr>
    <td align="center" width="25%"><img src="assets/screenshots/01-home-dashboard.png" alt="Smart Home Dashboard" /><br /><sub><b>1. Home Dashboard</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/02-snap-camera.png" alt="AI Meal & Barcode Scanner" /><br /><sub><b>2. AI Camera &amp; Barcode</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/03-food-result.png" alt="Ingredient Breakdown" /><br /><sub><b>3. Meal Breakdown</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/04-coach.png" alt="Personal AI Coach" /><br /><sub><b>4. AI Coach</b></sub></td>
  </tr>
  <tr>
    <td align="center" width="25%"><img src="assets/screenshots/05-progress.png" alt="Weight & TDEE Progress" /><br /><sub><b>5. Progress &amp; Trends</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/06-workouts.png" alt="Workouts Library" /><br /><sub><b>6. Workouts (877+)</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/07-diabetes-health-hub.png" alt="CGM Blood Sugar Hub" /><br /><sub><b>7. Glucose &amp; CGM Hub</b></sub></td>
    <td align="center" width="25%"><img src="assets/screenshots/08-voice-text-meal.png" alt="Voice & Text Meal Logging" /><br /><sub><b>8. Voice &amp; Text Logging</b></sub></td>
  </tr>
</table>

---

## 🏛️ System Architecture

```mermaid
flowchart TB
    subgraph Clients["Native Mobile & Wearable Clients"]
        IOS["iOS App (SwiftUI, iOS 17.6+)<br/>watchOS App • WidgetKit • Share Ext • HealthKit • LiteRTLM"]
        AND["Android App (Kotlin, Compose M3, API 26+)<br/>CameraX + ML Kit • Health Connect • Glance Widgets • WorkManager"]
    end

    subgraph Edge["Edge & Web Platform (Cloudflare)"]
        CFW["Cloudflare Workers (TypeScript)<br/>Hosted AI Vision & Audio Proxy • Auth Ledger (KV / D1)"]
        WEB["wazenai.com Portal<br/>Multilingual AR/EN/FR • SEO/GEO (llms.txt, JSON-LD) • AASA & AssetLinks"]
    end

    subgraph Core["Backend Services (Dockerized Python)"]
        API["Django 5.0 + Django REST Framework<br/>SimpleJWT • django-allauth • drf-spectacular (OpenAPI)"]
        DB[(PostgreSQL)]
        MQ[(Redis + Celery / Beat)]
        PUSH["FCM & APNs Notification Pipeline"]
    end

    IOS -->|HTTPS / JWT / Universal Links| CFW
    IOS -->|REST API| API
    AND -->|HTTPS / JWT / App Links| CFW
    AND -->|REST API| API
    WEB -->|Deep Links & Meal Shares| Clients
    CFW -->|Inference Routing| AI["Multimodal Vision & Voice AI Providers"]
    API --> DB
    API --> MQ
    MQ --> PUSH
```

---

## 🛠️ Technology Stack

| Layer | Technologies Used |
| :--- | :--- |
| **iOS & Wearables** | Swift, SwiftUI (`iOS 17.6+`), `watchOS` Companion, `WidgetKit`, Share Extension, `HealthKit`, `AVFoundation`, On-device `LiteRTLM` |
| **Android** | Kotlin, Jetpack Compose (Material 3), `CameraX`, `ML Kit` Barcode (`GTIN`), `Health Connect`, `Glance` AppWidgets, `WorkManager`, Encrypted DataStore, `Coil`, `RevenueCat` SDK |
| **Edge / AI Gateway** | Cloudflare Workers (`TypeScript`), Wrangler, Cloudflare KV & D1 Migrations, Streaming Vision & Audio AI Proxy |
| **Backend API** | Python, Django `5.0.6`, Django REST Framework `3.15`, PostgreSQL (`psycopg2`), Redis, Celery & Celery Beat, Flower, JWT (`SimpleJWT`), `django-allauth`, `drf-spectacular`, `firebase-admin` / `fcm-django`, Docker Compose |
| **Web & Growth** | Multilingual HTML/CSS/JS (`wazenai.com` in `AR`, `EN`, `FR` + 8 regional landing pages), Schema.org JSON-LD, `llms.txt` / GEO, `hreflang`, Apple AASA & Android AssetLinks |
| **Localization** | Full RTL & LTR support across **Arabic, English, French, German, and Spanish** + automated multi-locale Play Store asset generator (`Pillow` + `arabic_reshaper` + `python-bidi`) |

---

## 🌍 نظرة مختصرة بالعربية

**وازن (Wazen)** تطبيق ذكي شامل للتغذية، حساب السعرات والماكروز، متابعة سكر الدم (CGM)، واللياقة البدنية متوفر رسمياً على [**App Store**](https://apps.apple.com/app/wazen-%D9%88%D8%A7%D8%B2%D9%86/id6760981534) و [**Google Play**](https://play.google.com/store/apps/details?id=com.wazen.health.wazen_app) وعلى الويب عبر [**wazenai.com**](https://wazenai.com).  
صُمّم وطُوّر ببنية متعددة المنصات (**SwiftUI / watchOS** لنظام iOS، و **Kotlin / Jetpack Compose** لنظام Android، مع **Cloudflare Workers** و **Django REST / PostgreSQL / Celery** في الواجهة الخلفية) لتقديم تجربة عربية وعالمية متكاملة بـ **5 لغات**.

> 📄 Ready-to-copy CV & LinkedIn resume bullet points: see [`CV_RESUME_BULLETS.md`](CV_RESUME_BULLETS.md).
