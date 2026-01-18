# NeuroSpectrum 🧠

![Version](https://img.shields.io/badge/version-5.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![Languages](https://img.shields.io/badge/languages-PT%20|%20EN%20|%20ES-orange) ![Status](https://img.shields.io/badge/status-active-success)

> A professional, multilingual, and ethically designed psychoeducational screening tool for neurodivergent traits.

📋 Overview

NeuroSpectrum is an open-source single-page application (SPA) designed to assist in the preliminary identification of autism spectrum traits and related neurodivergences.

Unlike generic online quizzes, NeuroSpectrum implements a differential diagnosis logic inspired by DSM-5 criteria, distinguishing between core spectrum traits and potential "mimics" such as high stress, burnout, or anxiety.

⚠️ Medical Disclaimer

This tool is for educational and self-knowledge purposes only. > It does not provide a medical diagnosis.

Always consult a qualified neuropsychologist or psychiatrist for clinical evaluation.

**🔗 [Try the Live Demo](https://webrjpro.github.io/neurospectrum)**

✨ Features

🌍 Multilingual Support (i18n)

Auto-detection based on browser language

Fully localized for Portuguese (PT-BR), English (EN-US), and Spanish (ES)

Easy to add new languages (see Translation Guide)

🧠 Clinical Logic Layer

Childhood History Module: Aligns with DSM-5 Criterion C

Functional Impact Assessment: Measures Criterion D

Emotional Context Detection: Flags stress/anxiety as confounding factors

Dynamic Age Adjustment: Different phrasing for adults vs. adolescents

📊 Professional Reporting

Radar Chart Visualization: 5 domains (Social, Routine, Sensory, Masking, Context)

PDF Export: Print-optimized CSS for physical reports

JSON Export: Share raw data with clinicians

🎨 Modern UX/UI

Glassmorphism design with smooth animations

Dark mode optimized

WCAG 2.1 AA compliant (accessibility-first)

🔒 Privacy-First

100% client-side: No data sent to servers

LocalStorage persistence: Resume anytime

Data sovereignty: Export and delete data at will

🛠️ Tech Stack

Built with simplicity and longevity in mind:

Technology

Purpose

HTML5 Semantic

Structure

Tailwind CSS (CDN)

Styling

Vanilla JavaScript (ES2023+)

Logic

Canvas API

Chart rendering

Why no frameworks?

⚡ Zero build steps

📦 No dependencies to maintain

🌐 Works offline out-of-the-box

🔧 Easy for contributors to understand

🧬 Scientific Methodology

NeuroSpectrum adapts questions from validated instruments:

1. RAADS-R (Ritvo Autism Asperger Diagnostic Scale-Revised)

Focus on adult traits and sensory processing

80-item clinical scale adapted to 14 core questions

2. CAT-Q (Camouflaging Autistic Traits Questionnaire)

Heavy emphasis on social masking

3-factor structure (Compensation, Masking, Assimilation)

3. DSM-5 Criteria for Autism Spectrum Disorder

Criterion A: Social communication deficits

Criterion B: Restricted, repetitive patterns

Criterion C: Symptoms present in early development

Criterion D: Clinically significant impairment

Differential Diagnosis Logic:

High traits + No history → Suggests re-evaluation (possible mimicry)

High traits + High stress → Flags emotional context

High traits + History + Impact → High compatibility (referral suggested)

For detailed methodology, see docs/methodology.md.

🚀 Installation & Usage

Option 1: Online Demo

Visit **[neurospectrum.app](https://webrjpro.github.io/neurospectrum)** (GitHub Pages hosted)

Option 2: Local Setup

Since this is a zero-dependency project, no npm or node required!

## Clone the repository

```bash
git clone https://github.com/webrjpro/neurospectrum.git
cd neurospectrum
```

## Open the file

```bash
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```
```bash
npx serve .
```

Then visit [http://localhost:3000](http://localhost:3000) in your
npx serve .
## Visit [http://localhost:3000](http://localhost:3000)

Or open directly in browser.


🤝 Contributing

We welcome contributions from developers, psychologists, and translators!

For Developers

Fork the project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to Branch (git push origin feature/AmazingFeature)

Open a Pull Request

See CONTRIBUTING.md for code style guidelines.

For Psychologists/Clinicians

Don't know how to code? You can still help!

📝 Validate question phrasing

🌍 Review translations for cultural sensitivity

📊 Suggest improvements to scoring logic

📚 Provide anonymized case studies

Contact: **carlospiquet.projetos@gmail.com** ou [abra uma issue](https://github.com/webrjpro/neurospetrum/issues/new)

Translation Guide

To add a new language:

Add a new key to the I18N object in index.html

Translate all QUESTIONS array entries

Test thoroughly

Submit PR with screenshots

See docs/translation-guide.md for details.

🗺️ Roadmap

[x] v1.0 - Core screening logic (PT only)

[x] v3.0 - LocalStorage persistence

[x] v4.0 - Multilingual support (EN/ES)

[x] v5.0 - JSON export + Auto-language detection

[ ] v6.0 - Temporal tracking (compare results over time)

[ ] v7.0 - Offline PWA mode

[ ] v8.0 - AI-powered personalized insights (Claude API)

Suggest a feature →

📚 Citation

If you use NeuroSpectrum in research or clinical practice, please cite:

@software{neCarlos Antonio de Oliveira Piquet},
  title = {NeuroSpectrum: Multilingual Screening Tool for Neurodivergent Traits},
  year = {2026},
  version = {5.0},
  url = {https://github.com/webrjpro/neurospec
  url = {https://github.com/webrjpro/neurospetrum},
  note = {Open-source psychoeducational tool based on DSM-5, RAADS-R, and CAT-Q}
}


📄 License

Distributed under the MIT License. See LICENSE for details.

This means you can:

✅ Use commercially

✅ Modify and redistribute

✅ Use privately

❌ Hold author liable

❤️ Acknowledgments

ABRAÇA - Brazilian advocacy for autistic rights

Neurodiversity Library - International research hub

Confederación Autismo España - Spanish autism federation

Open Source Community - For continuous feedback and contributions

Made with 🧠 and ❤️ for the Neurodivergent Community

[⭐ Star this project](https://github.com/webrjpro/neurospetrum/stargazers) if it helped you!
