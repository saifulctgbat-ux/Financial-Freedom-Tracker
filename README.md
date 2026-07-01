# Freedom Financial System — Master Dashboard

## GitHub Pages এ Deploy করার নিয়ম

1. GitHub-এ নতুন একটা repository তৈরি করুন (public হতে হবে) — যেমন `ffs-dashboard`.
2. এই দুইটা ফাইল repo-তে আপলোড করুন:
   - `index.html`
   - `FFS_Master_Template.xlsx` (ইচ্ছা হলে, রেফারেন্সের জন্য)
3. Repo → **Settings → Pages** এ যান।
4. **Source** এ `main` branch এবং `/ (root)` সিলেক্ট করে **Save** করুন।
5. কিছুক্ষণ পর একটা লিংক পাবেন: `https://<your-username>.github.io/ffs-dashboard/`
6. ঐ লিংকে ঢুকে Excel ফাইল আপলোড করলেই ড্যাশবোর্ড লোড হয়ে যাবে।

## নোট
- এই ফাইলটা সম্পূর্ণ client-side (কোনো backend/server লাগে না), তাই GitHub Pages-এর static hosting-এই পুরোপুরি চলবে।
- ডাটা browser memory-তে থাকে (localStorage ব্যবহার হয়নি), তাই পেজ রিফ্রেশ করলে আবার Excel আপলোড করতে হবে।
