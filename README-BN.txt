QUITCIG — শুরু করার নির্দেশনা (Windows + iPhone)

এই ফোল্ডারে আছে:
- index.html: অ্যাপের UI ও ফিচার
- manifest.json: Home Screen PWA পরিচিতি
- service-worker.js: অ্যাপের ফাইল অফলাইনে ক্যাশ করে
- icon.svg: অ্যাপ আইকন

গুরুত্বপূর্ণ:
PWA অফলাইন কাজ করার জন্য HTTPS hosting অথবা localhost প্রয়োজন। index.html-এ ফাইল ডাবল-ক্লিক করে খুললে service worker কাজ করবে না।

বিনা খরচে চালানোর সহজ পদ্ধতি:
1. Windows-এ এই ফোল্ডারটি GitHub-এ একটি নতুন repository-তে আপলোড করুন।
2. Repository Settings → Pages → Deploy from a branch → main / root নির্বাচন করে Save করুন।
3. GitHub Pages HTTPS URL তৈরি হলে iPhone-এর Safari-তে URL খুলুন।
4. Share → Add to Home Screen → Add চাপুন।
5. প্রথমবার অ্যাপটি অনলাইনে খুলে কয়েক সেকেন্ড অপেক্ষা করুন। তারপর Airplane Mode দিয়ে পরীক্ষা করুন।

ডেটা ও সীমাবদ্ধতা:
- এই prototype-এর settings, XP, daily counts localStorage-এ একই browser/device-এ থাকে।
- iPhone ও Windows-এর মধ্যে ডেটা নিজে থেকে sync হবে না; তার জন্য আলাদা backend/sync ব্যবস্থা প্রয়োজন।
- Safari data clear করলে বা browser storage মুছলে স্থানীয় ডেটা হারাতে পারে।
- "খাই নাই" বাটনটি self-report; এটি সিগারেট না খাওয়ার প্রমাণ নয়।
- সেভিংস আনুমানিক হিসাব এবং আপনার দেওয়া দাম/পরিমাণের ওপর নির্ভর করে।
- এটি চিকিৎসা-পরামর্শ বা নিকোটিন-নির্ভরতা চিকিৎসার বিকল্প নয়।

প্রথম সংস্করণের ফিচার:
✓ Cigarette pack price, pack size, usual daily count
✓ "খাই নাই" craving button and random healthy mini-task
✓ Task completion XP and levels
✓ Cigarette log, daily counters, estimated savings
✓ Offline app shell + local browser storage
✓ Mobile-friendly dark UI, Bangla-English copy

আরও উন্নত সংস্করণে যোগ করা যেতে পারে:
- Export/import backup
- Craving history calendar
- Task history and reminder options
- Device-to-device cloud sync
