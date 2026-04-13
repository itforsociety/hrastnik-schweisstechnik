# Plan: Trojezična SEO Stranica za Varenje

## Cilj
Izraditi besplatnu statičku web stranicu na GitHub Pages s punom podrškom za njemački, hrvatski i engleski jezik. Primarni SEO fokus je DACH tržište (DE/AT/CH), uz vizualni identitet s SVG animacijama vezanim uz varenje i cijevi.

## Potvrđene odluke
- Tip projekta: firma (trenutno jedan član), spremno za rast tima.
- Primarno tržište: njemačko govorno područje.
- Usluga v1: zavarivanje cijevi.
- Kontakt: email, LinkedIn, telefon i kontakt forma (Formspree).
- Deploy: početno GitHub Pages URL, bez custom domene u v1.
- Experience sekcija: puni nazivi kompanija su dozvoljeni.
- Glavni DE CTA: "Angebot anfragen".

## Faze implementacije
1. Informacijska arhitektura i sadržajni okvir.
2. Tehnička osnova i i18n model (/de/, /hr/, /en/).
3. Tehnički SEO (hreflang, canonical, sitemap, robots, schema).
4. Vizualni sustav i SVG animacije (welding/pipe scene).
5. Konverzija i kontakt (forma + CTA + trust signali).
6. Deploy i QA (GitHub Pages + Lighthouse + SEO validacija).
7. Post-launch SEO iteracije.

## Content integration (profil)
- Hero poruka DE: QA/QC Schweißfachmann, pouzdana industrijska isporuka.
- Lokacija: Ahaus, North Rhine-Westphalia, Germany.
- Top skills: IWS, VT2, Vorrichter.
- Experience prioritet:
  - ExxonMobil (QA/QC, Antwerpen)
  - HOLBORN Europa Raffinerie GmbH (QC/QA, Hamburg, HVO)
  - Verbio SE (QA/QC, Bitterfeld, Ethenolyse)
  - 2G Energy AG (Leiter Qualitätssicherung/Supervisor/Qualitätskontrolle)

## Profilna fotografija
- Koristi se kao primarni personal branding element na početnoj i About sekciji.
- Potrebne varijante: hero (1:1), about (4:5), thumbnail (1:1).
- Format: WebP + JPG fallback.
- Alt opis treba biti jezično lokaliziran (DE/HR/EN).

## Verifikacija
- SEO: hreflang/canonical/sitemap/robots bez grešaka.
- i18n: svaka ruta prikazuje ispravan jezik i metadata.
- Performance: Lighthouse mobile cilj 85+.
- Accessibility: kontrast, fokus, reduced-motion, alt opisi.
- Kontakt: forma radi i anti-spam zaštita aktivna.
