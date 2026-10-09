# LinkedIn update kit

Copy-paste text for updating the LinkedIn profile so it points to the project hub.
Every number here matches the live projects and their READMEs (October 2026).

**Hub link:** https://biggyatz.github.io/project-documentations-VIT/

LinkedIn headlines are not clickable, so the headlines below point to the Featured section instead of a URL.

---

## 1. Headline (pick one, max 220 characters)

**A.** AI Solutions Architect · FinTech Researcher · AI Trainer | Building data & AI systems for Nepal's capital markets | 5 live AI projects (links in Featured)

**B.** I turn manual finance work into AI pipelines | FinTech research & automation · Trained 200+ professionals (ACCA Nepal) | Live AI projects in Featured

---

## 2. Contact info → Website

- **URL:** `https://biggyatz.github.io/project-documentations-VIT/`
- **Type:** Portfolio (or "Other" with the label **Projects**)

Optional: Profile → *Add profile section* → *Custom button* → **Visit website** → `https://biggyatz.github.io/project-documentations-VIT/`

---

## 3. About (paste as is)

I build data and AI systems that replace slow, manual work in finance with pipelines a team can trust and audit.

At Laxmi Sunrise Capital I automated daily risk reporting, built a sector grading model that compares companies across nine sectors, and gave the research and portfolio teams a shared fund dashboard. At ShareSanskar I automated equity research that used to take hundreds of hours of manual data extraction. I now work on data and automation at TaskNTrade.

I also teach. Through ACCA Nepal I've trained 200+ finance professionals to use AI and Python on top of the systems they already have.

Some things you can try right now, free and in your browser:
🏠 Nepal Property Price Estimator: 1,900+ real listings, 111 localities
🚗 Nepal Used Car Value Estimator: 68 models, ±7.7% typical error
🩻 MediQNet: ask questions about radiology images (would rank #5 of 18 in the VQA-Med 2019 challenge)
⚽ Premier League 2020/21 interactive dashboard
🎓 Student Performance Insights: explainable ML
🌱 Farmkart: an online store for farmers (VIT team project)

Everything is in one place: https://biggyatz.github.io/project-documentations-VIT/

Open to research, consulting and AI training work. WhatsApp is the fastest way to reach me.

---

## 4. Featured section (Profile → Add section → Featured → Add a link)

Add in this order; LinkedIn pulls the preview image from each page.

| # | Link | Title | Description |
|---|---|---|---|
| 1 | https://biggyatz.github.io/project-documentations-VIT/ | All my projects in one place | Live AI demos, code, case studies and research, with links to try each one. |
| 2 | https://biggyatz.github.io/nepal-property-price-estimator/ | Nepal Property Price Estimator | What is a house or plot of land worth? Built on 1,900+ real listings across 111 localities. Works in ropani-aana and bigha-kattha-dhur. |
| 3 | https://biggyatz.github.io/nepal-used-car-value-estimator/web/ | Nepal Used Car Value Estimator | Value a used car from real listings, compare with today's showroom price, see depreciation. 68 models, ±7.7% typical error. |
| 4 | https://biggyatz.github.io/MediQNet-VQA-system/ | MediQNet: Medical Visual Q&A | Ask a radiology image about modality, plane, organ or abnormality. 60.2% on the VQA-Med 2019 test set; runs on your device. |
| 5 | https://www.linkedin.com/posts/biggyat-kumar-pandey_acca-accanepal-collaboration-activity-7483201707242573826-hLtd | AI for Finance: ACCA Nepal sessions | (keep the existing post) |

---

## 5. Projects section (Profile → Add section → Recommended → Add projects)

For each: **Name**, **Description**, **Skills**, **Project URL** (via *Add media → Add a link*), associated with the listed experience if relevant.

### Nepal Property Price Estimator
- **Dates:** Oct 2026
- **URL:** https://biggyatz.github.io/nepal-property-price-estimator/
- **Description:** A free web app that estimates the asking price of a house or land anywhere in Nepal. I collected 2,000+ public listings from 99aana.com and Hamrobazar (robots.txt-compliant, no personal data). I parsed Nepali prices and land units (crore and lakh; ropani-aana-paisa-dam and bigha-kattha-dhur) and fitted a hedonic regression across 111 localities. The app gives an estimate with a likely range, price per aana and comparable listings, and runs entirely in the browser.
- **Skills:** Python · Web Scraping · Machine Learning · Regression Analysis · JavaScript · Data Visualization

### Nepal Used Car Value Estimator
- **Dates:** Oct 2026 (rebuilt from my 2024 SmartInternz car-performance project)
- **URL:** https://biggyatz.github.io/nepal-used-car-value-estimator/web/
- **Description:** Estimates the market value of a used car in Nepal from real Hamrobazar listings and compares it with 2026 showroom prices from NepalDrives. Free-text titles are mapped to 68 make/model families, Bikram Sambat years are converted, and a regularised regression achieves a 7.7% median error on held-out listings. It shows value retained versus new and a depreciation curve.
- **Skills:** Python · Data Cleaning · Machine Learning · Pricing Models · JavaScript

### MediQNet: Medical Visual Question Answering
- **Dates:** 2024 (VIT capstone), demo Oct 2026
- **URL:** https://biggyatz.github.io/MediQNet-VQA-system/
- **Description:** A deep-learning system that answers questions about radiology images. The research version fuses BioBERT and a Swin Transformer. The live demo is a compact model (MobileNetV3 plus a question encoder) exported to ONNX that runs on the user's device. It scores 60.2% exact-match on the official ImageCLEF VQA-Med 2019 test set, which would rank 5th of 18 teams, and its plane accuracy beats the winning team's.
- **Skills:** Deep Learning · PyTorch · Computer Vision · NLP · ONNX · Medical Imaging

### Premier League 2020/21 in Numbers
- **URL:** https://biggyatz.github.io/EPL-2020-2021-analysis/
- **Description:** An interactive season dashboard built from 488 players' statistics: 13 leaderboards, shots-vs-goals finishing efficiency, which team stats correlate with wins (goals r = 0.85; tackles r = −0.40) and per-position percentile profiles.
- **Skills:** Data Visualization · R · JavaScript · Statistics

### Student Performance Insights
- **URL:** https://biggyatz.github.io/student-performance-insights/
- **Description:** An end-to-end ML pipeline (ingestion, transformation, model selection) predicting maths scores (test R² 0.88), with an explainable web app showing how each input moves the prediction. I diagnosed and fixed a dummy-variable trap in the original model.
- **Skills:** Machine Learning · Explainable AI · Python · CI/CD

### Farmkart: Online Store for Farmers
- **Dates:** Fall 2023 (VIT, CSE3002, with Pawar Adwyait Shivaji)
- **URL:** https://biggyatz.github.io/project-documentations-VIT/farmkart/
- **Description:** A full-stack e-commerce site for farming essentials: seeds, flowering and fruit plants, tools and pest control, with guidance on what to sow each season. Built in PHP and MySQL; the live version is a static rebuild of the 117-product catalogue with search, filters, a cart and a simulated checkout.
- **Skills:** PHP · MySQL · JavaScript · Web Development

---

## 6. Launch post (optional)

> I've just put five of my AI projects online, free to use, with no sign-up. Everything runs in your browser.
>
> 🏠 What is a house in Kathmandu actually listed for? My Nepal Property Price Estimator learned from 1,900+ real listings across 111 localities, and it speaks ropani-aana.
> 🚗 How much is your used car worth, and how fast is it losing value? 68 models, ±7.7% typical error.
> 🩻 MediQNet answers questions about radiology images on your device. Its score would have placed 5th of 18 teams in the ImageCLEF VQA-Med 2019 challenge.
>
> Plus an interactive Premier League 2020/21 dashboard and an explainable student-performance model.
>
> All of them, with code and methodology: https://biggyatz.github.io/project-documentations-VIT/
>
> Which one should I build out next? 👇
>
> #AI #MachineLearning #DataScience #FinTech #Nepal #OpenSource
