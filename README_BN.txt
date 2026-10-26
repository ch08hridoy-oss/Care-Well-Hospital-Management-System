CAReWELL — GITHUB PAGES / VS CODE READY

এই ZIP-এ static HTML, CSS, JavaScript আছে; Python/Flask চালাতে হবে না।

VS Code:
1. ZIP Extract করুন।
2. VS Code → File → Open Folder → CareWell_GitHub_Ready নির্বাচন করুন।
3. index.html খুলে Live Server extension থাকলে Go Live চাপুন; না থাকলে index.html ব্রাউজারে খুলুন।

GitHub Pages:
1. GitHub-এ নতুন repository বানান।
2. ZIP extract করে ভেতরের ফাইলগুলো repository root-এ upload করুন। ZIP-টিকে শুধু upload করলে website deploy হবে না।
3. Settings → Pages → Deploy from a branch → Branch main → /(root) → Save।
4. কিছুক্ষণ পরে Pages URL পাওয়া যাবে।

ফিচার: responsive dashboard, patient registration, search, status update, delete, departments, colorful SVG graphics, demo patient records।

সীমাবদ্ধতা: GitHub Pages static hosting; ডেটা browser localStorage-এ থাকে এবং শুধু একই browser/device-এ থাকবে। এটি shared backend database নয়। বাস্তব রোগীর তথ্য ব্যবহার করবেন না। Production ব্যবহারের আগে secure backend, database, authentication, authorization, audit logs, CSRF protection, backups ও security review আবশ্যক।

Canva assets: assets/images/hospital-hero-banner.svg, department-cards.svg, appointment-promo.svg, carewell-logo.svg. Canva → Uploads → Upload files দিয়ে upload করুন। এগুলো custom SVG, Canva-generated বলে দাবি করবেন না; assignment-এ Canva editor design লাগলে Canva-তে editable design হিসেবে আলাদা করে তৈরি/সেভ করুন।
