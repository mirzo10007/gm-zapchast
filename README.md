# GM Zapchast

Avtoehtiyot qismlar do'koni uchun sotuv va ombor dasturi.

- `src/app.html` — dastur manbasi (bitta HTML fayl), `src/seed.json` — boshlang'ich mahsulotlar bazasi
- `tools/build.py` — yig'ish (esbuild bilan siqib, bitta HTML qiladi)
- `desktop/` — Windows EXE (Electron)
- `mobile/` — Android APK (Capacitor)
- `.github/workflows/build.yml` — har `main` ga push qilinganda HTML, APK va EXE yig'iladi va Releases ga joylanadi

Android imzo kaliti `mobile/signing/` da (repozitoriy maxfiy bo'lgani uchun). Uni yo'qotmang: APK yangilanishlari shu kalit bilan imzolanishi shart. Repozitoriyni hech qachon ochiq (public) qilmang. Litsenziya generatori va maxfiy kalit bu repozitoriyda **yo'q** va bo'lmasligi kerak.
