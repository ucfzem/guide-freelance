# InFreelancing — Guide Freelance (Backup)

## URLs
- **GitHub Pages:** https://ucfzem.github.io/guide-freelance/
- **Vercel:** (deploy link)

## Features
- 4 languages: 🇫🇷 FR, 🇬🇧 EN, 🇪🇸 ES, 🇲🇦 AR (Moroccan flag)
- RTL support for Arabic
- Dark/Light theme toggle
- Interactive checklist with progress bar
- Responsive design
- Gold/brown luxury theme

## Files
- `index.html` — Main file (HTML + CSS + JS + i18n)
- `BACKUP.md` — This backup file

## Translations
All 4 languages are embedded in `index.html` via the `I18N` JavaScript object.

### Language Keys
- `ornament`, `subtitle`, `desc`, `progress`
- `intro_strong`, `intro_text`
- `sec1_title`, `sec2_title`, `sec3_title`
- `step`, `step2`, `step3`, `step4`, `step5`
- `s1_title` through `s5_title`
- `s1_li1_strong` through `s1_li5_text`
- `s2_text`, `s2_tip_strong`, `s2_tip_text`
- `s3_text`, `s4_text`, `s5_text`
- `oblig_monthly`, `oblig_yearly`
- `oblig_m1` through `oblig_m3`, `oblig_y1` through `oblig_y4`
- `tip_rappel_strong`, `tip_rappel_text`
- `checklist_label`
- `cl1` through `cl11`, `cl1_sub` through `cl11_sub`
- `reset`, `footer_quote`, `footer_small`
- `theme_night`, `theme_day`

## Deploy
```bash
# GitHub Pages
cd guide-freelance
git add -A && git commit -m "Update"
git push origin main

# Vercel
vercel --prod
```

## Theme Tokens
```css
--gold: #C9A84C;
--gold-light: #F0C866;
--gold-dim: #8A6A1E;
--dark-bg: #1A1208;
--dark-surface: #231A0A;
--dark-card: #2E2010;
--light-bg: #FAF3E8;
--light-card: #FFFAF2;
```

## Created
- Date: 2026-06-27
- Author: Azer (ucfzem)
