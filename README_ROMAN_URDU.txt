NAMAZ SCHEDULE - ANDROID APK PROJECT

Yeh project aapki index.html ko Android app ke andar rakhta hai.
App ka main page local asset se load hota hai, is liye internet ki zaroorat nahi hoti.

MOBILE SE APK BANANE KA TAREEQA (GitHub account zaroori hai):
1. Is ZIP ko extract karein.
2. Chrome mein github.com kholein aur sign in karein.
3. New repository banayein, naam NamazSchedule rakhein, Public ya Private dono theek hain.
4. Repository mein Add file > Upload files se ZIP ko extract kar ke andar ki SAARI files/folders upload karein. ZIP file khud upload na karein.
5. Commit changes karein.
6. Repository ke Actions tab mein "Build Namaz Schedule APK" workflow kholein.
7. Agar workflow khud start na ho to Run workflow dabayein.
8. Green tick aane par run open karein; Artifacts mein Namaz-Schedule-APK download karein.
9. Downloaded artifact ZIP extract karein. Andar app-debug.apk hogi. Use tap karke install karein. Android unknown-app install permission maang sakta hai; sirf apni banayi hui file ke liye allow karein.

NOTE: Yeh project build karne ke liye internet/GitHub chahiye, lekin install hone ke baad app ka HTML page offline chalta hai. Yeh debug APK hai, Play Store release package nahi.
