# Nabız Güneşi

Kerem'in kişisel sağlık uygulaması. Telefonda ana ekrana eklenen bir web uygulaması (PWA).

- **Veri:** Garmin Personal API → Supabase (`garmin-sync` fonksiyonu, saatte bir).
- **Giriş:** Supabase hesabı (e-posta + şifre). Veriyi satır düzeyinde güvenlik (RLS) korur; bu depoda sağlık verisi yok.
- **Plan ve koç notları:** Claude'daki panel açıldığında Supabase'e aktarılır.
- **Hava:** Open-Meteo, Prenzlauer Berg.

Dosyalar: `index.html` (uygulamanın tamamı), `sw.js` (çevrimdışı kabuk), `manifest.webmanifest`, simgeler.
