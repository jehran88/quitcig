QuitCig v3 — GitHub upload guide
================================
এই সংস্করণে “খাই নাই!” চাপলে র‍্যান্ডমভাবে একটি ছোট craving task অথবা সূত্র-সংযুক্ত বাস্তব জীবনী দেখাবে।

গল্পের পড়ার অভিজ্ঞতা:
- গল্প ছোট popup নয়; আলাদা full-screen reader/page-এ খোলে।
- পুরো লেখা নিচে স্ক্রল করে পড়া যায়; উপরে “ফিরে যাও” বোতাম।
- “পড়া শেষ” চাপলে +20 XP পাওয়া যায়। একই গল্পের জন্য এই ডিভাইসে একবার XP দেওয়া হয়।
- পাঁচটি বাস্তব ব্যক্তির জীবনীমূলক পুনর্কথন রয়েছে, প্রতিটিতে মূল সূত্রের লিংক।
- এগুলো মূল বই/নিবন্ধের হুবহু কপি নয়; সূত্রের তথ্যের ভিত্তিতে নতুন ভাষায় লেখা। প্রতিটি লেখা পূর্ণাঙ্গ বই নয়।
- গল্পের ডেটা অ্যাপের সঙ্গে যুক্ত, তাই একবার অ্যাপ ফাইল লোড হলে গল্প অফলাইনেও পড়া যাবে।

GitHub:
1. ZIP extract করো।
2. ভিতরের QuitCig ফোল্ডারের ফাইলগুলো repository-র root-এ upload/replace করো (অথবা project subfolder-এ deploy হলে সেই ফোল্ডারে)।
3. index.html, manifest.json, service-worker.js, icon.svg একই folder-এ থাকবে।
4. GitHub Pages-এ deploy হলে site HTTPS-এ খুলো। পুরোনো cache থাকলে browser refresh করো বা site data/cache clear করে আবার খুলো।

নোট: app-এর ডেটা browser localStorage-এ থাকে। Browser data clear করলে XP/settings মুছে যেতে পারে। Medical advice নয়।
