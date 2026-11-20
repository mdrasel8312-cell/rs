<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RS Online Internet Service Provider</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <script src="https://cdn.jsdelivr.net/npm/sweetalert2@11"></script>
    <style>
        .dark-navy { background-color: #0f172a; }
        .card-bg { background-color: #1e293b; }
        .accent-gold { color: #f59e0b; }
        .bkash-pink { background-color: #e21372; }
        .nagad-orange { background-color: #f36c21; }
    </style>
</head>
<body class="dark-navy text-white min-h-screen font-sans pb-10">

    <!-- Header & Welcome -->
    <header class="card-bg border-b border-slate-700 p-4 sticky top-0 z-50 shadow-lg">
        <div class="max-w-md mx-auto flex justify-between items-center">
            <div>
                <h1 class="text-xl font-bold text-amber-400">RS Online</h1>
                <p class="text-xs text-slate-400">Internet Service Provider</p>
            </div>
            <button onclick="toggleLanguage()" class="bg-slate-700 hover:bg-slate-600 px-3 py-1 rounded-full text-xs font-semibold flex items-center gap-1 border border-slate-500">
                <i class="fa-solid fa-language"></i> <span id="lang-btn-text">English</span>
            </button>
        </div>
    </header>

    <div class="max-w-md mx-auto mt-4 px-4">
        <div class="bg-gradient-to-r from-blue-900 to-indigo-900 p-5 rounded-2xl shadow-xl border border-blue-700/50 text-center relative overflow-hidden">
            <div class="absolute -right-10 -bottom-10 text-white/10 text-9xl pointer-events-none">
                <i class="fa-solid fa-wifi"></i>
            </div>
            <h2 id="welcome-title" class="text-2xl font-extrabold mb-1">স্বাগতম RS Online-এ!</h2>
            <p id="welcome-sub" class="text-sm text-blue-200">ব্যান্ডউইথ ব্যবহারকারীদের জন্য দ্রুত ও নিরবচ্ছিন্ন ইন্টারনেট সেবা।</p>
            <div class="mt-4 inline-flex items-center gap-2 bg-emerald-500/20 border border-emerald-500/50 px-3 py-1 rounded-full text-xs text-emerald-300 font-medium">
                <span class="w-2 h-2 rounded-full bg-emerald-400 animate-pulse"></span> <span id="status-text">২৪/৭ অনলাইন সাপোর্ট</span>
            </div>
        </div>

        <!-- Internet Packages -->
        <h2 id="packages-title" class="text-lg font-bold mt-8 mb-4 flex items-center gap-2 text-amber-400">
            <i class="fa-solid fa-gauge"></i> আমাদের ইন্টারনেট প্যাকেজসমূহ
        </h2>
        <div id="packages-container" class="grid grid-cols-1 gap-4">
            <!-- Packages will be injected here by JS -->
        </div>

        <!-- Bill Payment -->
        <h2 id="payment-title" class="text-lg font-bold mt-8 mb-4 flex items-center gap-2 text-amber-400">
            <i class="fa-solid fa-wallet"></i> বিল পেমেন্ট (bKash / Nagad)
        </h2>
        <div class="grid grid-cols-1 gap-4">
            <!-- bKash Card -->
            <div class="card-bg p-5 rounded-2xl border border-slate-700 shadow-lg relative overflow-hidden">
                <div class="flex justify-between items-start mb-3">
                    <span class="bkash-pink text-white px-3 py-1 rounded-lg text-xs font-bold tracking-wider">bKash Merchant</span>
                    <span class="text-xs text-slate-400">Personal / Business</span>
                </div>
                <div class="flex items-center justify-between bg-slate-900 p-3 rounded-xl border border-slate-800 my-3">
                    <div>
                        <p class="text-xs text-slate-400">Account Number</p>
                        <p id="bkash-num" class="text-xl font-bold tracking-wider text-pink-400">01759887499</p>
                    </div>
                    <button onclick="copyNumber('01759887499', 'bKash')" class="bg-pink-600 hover:bg-pink-700 text-white px-4 py-2 rounded-lg text-xs font-bold flex items-center gap-1 transition shadow">
                        <i class="fa-regular fa-copy"></i> <span id="copy-text-1">Copy</span>
                    </button>
                </div>
            </div>

            <!-- Nagad Card -->
            <div class="card-bg p-5 rounded-2xl border border-slate-700 shadow-lg relative overflow-hidden">
                <div class="flex justify-between items-start mb-3">
                    <span class="nagad-orange text-white px-3 py-1 rounded-lg text-xs font-bold tracking-wider">Nagad Account</span>
                    <span class="text-xs text-slate-400">Personal / Business</span>
                </div>
                <div class="flex items-center justify-between bg-slate-900 p-3 rounded-xl border border-slate-800 my-3">
                    <div>
                        <p class="text-xs text-slate-400">Account Number</p>
                        <p id="nagad-num" class="text-xl font-bold tracking-wider text-orange-400">01869466643</p>
                    </div>
                    <button onclick="copyNumber('01869466643', 'Nagad')" class="bg-orange-600 hover:bg-orange-700 text-white px-4 py-2 rounded-lg text-xs font-bold flex items-center gap-1 transition shadow">
                        <i class="fa-regular fa-copy"></i> <span id="copy-text-2">Copy</span>
                    </button>
                </div>
            </div>

            <!-- Payment Reminder Box -->
            <div class="bg-amber-500/10 border-l-4 border-amber-500 p-4 rounded-r-xl text-xs text-amber-300">
                <p class="font-bold mb-1"><i class="fa-solid fa-triangle-exclamation"></i> গুরুত্বপূর্ণ নির্দেশনা:</p>
                <span id="payment-note">টাকা পাঠানোর পর অবশ্যই আপনার ইউজার আইডি (User ID) রেফারেন্স (Reference) হিসেবে ব্যবহার করুন এবং ট্রানজেকশন আইডি (TrxID) সংরক্ষণ করুন।</span>
            </div>
        </div>

        <!-- Support & Contact -->
        <h2 id="support-title" class="text-lg font-bold mt-8 mb-4 flex items-center gap-2 text-amber-400">
            <i class="fa-solid fa-headset"></i> সাপোর্ট ও যোগাযোগ
        </h2>
        <div class="grid grid-cols-1 gap-3">
            <div class="card-bg p-4 rounded-xl border border-slate-700 flex justify-between items-center">
                <div>
                    <span class="text-xs text-slate-400 block" id="contact-label">Contact Number</span>
                    <span class="text-base font-bold text-blue-400">01933562390</span>
                </div>
                <a href="tel:01933562390" class="bg-blue-600 hover:bg-blue-700 p-3 rounded-lg text-white font-bold transition">
                    <i class="fa-solid fa-phone"></i>
                </a>
            </div>

            <div class="card-bg p-4 rounded-xl border border-slate-700 flex justify-between items-center">
                <div>
                    <span class="text-xs text-slate-400 block" id="support-label">Support / Helpline</span>
                    <span class="text-base font-bold text-emerald-400">09697203499</span>
                </div>
                <a href="tel:09697203499" class="bg-emerald-600 hover:bg-emerald-700 p-3 rounded-lg text-white font-bold transition">
                    <i class="fa-solid fa-headset"></i>
                </a>
            </div>
        </div>

        <!-- Footer -->
        <footer class="mt-12 text-center text-xs text-slate-500 pb-6">
            <p>© 2026 RS Online Internet Service Provider. All rights reserved.</p>
        </footer>
    </div>

    <script>
        let isBangla = true;

        const translations = {
            bn: {
                langBtn: "English",
                welcomeTitle: "স্বাগতম RS Online-এ!",
                welcomeSub: "ব্যান্ডউইথ ব্যবহারকারীদের জন্য দ্রুত ও নিরবচ্ছিন্ন ইন্টারনেট সেবা।",
                statusText: "২৪/৭ অনলাইন সাপোর্ট",
                packagesTitle: "আমাদের ইন্টারনেট প্যাকেজসমূহ",
                paymentTitle: "বিল পেমেন্ট (bKash / Nagad)",
                copyText1: "কপি",
                copyText2: "কপি",
                paymentNote: "টাকা পাঠানোর পর অবশ্যই আপনার ইউজার আইডি (User ID) রেফারেন্স (Reference) হিসেবে ব্যবহার করুন এবং ট্রানজেকশন আইডি (TrxID) সংরক্ষণ করুন।",
                supportTitle: "সাপোর্ট ও যোগাযোগ",
                contactLabel: "কন্টাক্ট নম্বর",
                supportLabel: "সাপোর্ট / হেল্পলাইন নম্বর",
                taka: "টাকা / মাস"
            },
            en: {
                langBtn: "বাংলা",
                welcomeTitle: "Welcome to RS Online!",
                welcomeSub: "Fast and uninterrupted internet service for broadband users.",
                statusText: "24/7 ONLINE SUPPORT",
                packagesTitle: "Our Internet Packages",
                paymentTitle: "Bill Payment (bKash / Nagad)",
                copyText1: "Copy",
                copyText2: "Copy",
                paymentNote: "After sending money, you must use your User ID as a reference and save the Transaction ID (TrxID).",
                supportTitle: "Support & Contact",
                contactLabel: "Contact Number",
                supportLabel: "Support / Helpline Number",
                taka: "Taka / month"
            }
        };

        const packages = [
            { mbps: "20 Mbps", priceBn: "৬০০", priceEn: "600" },
            { mbps: "30 Mbps", priceBn: "৭০০", priceEn: "700" },
            { mbps: "40 Mbps", priceBn: "৮০০", priceEn: "800" },
            { mbps: "50 Mbps", priceBn: "৯০০", priceEn: "900", tag: "Popular" },
            { mbps: "60 Mbps", priceBn: "১,০০০", priceEn: "1,000" },
            { mbps: "70 Mbps", priceBn: "১,১৫০", priceEn: "1,150" },
            { mbps: "100 Mbps", priceBn: "১,২৫০", priceEn: "1,250", tag: "Best Value" }
        ];

        function renderPackages() {
            const container = document.getElementById('packages-container');
            container.innerHTML = '';
            const t = isBangla ? translations.bn : translations.en;

            packages.forEach((pkg, index) => {
                const price = isBangla ? pkg.priceBn : pkg.priceEn;
                const card = document.createElement('div');
                card.className = `card-bg p-4 rounded-xl border transition hover:border-amber-500 relative ${pkg.tag ? 'border-amber-500/50 shadow-lg shadow-amber-500/10' : 'border-slate-700'}`;
                
                if (pkg.tag) {
                    const tagBg = pkg.tag === 'Popular' ? 'bg-amber-500 text-slate-900' : 'bg-blue-600 text-white';
                    card.innerHTML += `<span class="absolute -top-3 right-4 ${tagBg} text-[10px] font-bold px-2 py-0.5 rounded-full uppercase tracking-wider">${pkg.tag}</span>`;
                }

                card.innerHTML += `
                    <div class="flex justify-between items-center">
                        <div>
                            <h3 class="text-lg font-bold text-amber-400">${pkg.mbps}</h3>
                            <p class="text-xs text-slate-400 mt-1">High Speed Broadband</p>
                        </div>
                        <div class="text-right">
                            <span class="text-xl font-extrabold text-white">${price}</span>
                            <span class="text-xs text-slate-400 block">${t.taka}</span>
                        </div>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        function toggleLanguage() {
            isBangla = !isBangla;
            const t = isBangla ? translations.bn : translations.en;

            document.getElementById('lang-btn-text').innerText = t.langBtn;
            document.getElementById('welcome-title').innerText = t.welcomeTitle;
            document.getElementById('welcome-sub').innerText = t.welcomeSub;
            document.getElementById('status-text').innerText = t.statusText;
            document.getElementById('packages-title').innerText = t.packagesTitle;
            document.getElementById('payment-title').innerText = t.paymentTitle;
            document.getElementById('copy-text-1').innerText = t.copyText1;
            document.getElementById('copy-text-2').innerText = t.copyText2;
            document.getElementById('payment-note').innerText = t.paymentNote;
            document.getElementById('support-title').innerText = t.supportTitle;
            document.getElementById('contact-label').innerText = t.contactLabel;
            document.getElementById('support-label').innerText = t.supportLabel;

            renderPackages();
        }

        function copyNumber(number, provider) {
            navigator.clipboard.writeText(number).then(() => {
                Swal.fire({
                    toast: true,
                    position: 'top-end',
                    icon: 'success',
                    title: `${provider} number ${number} copied to clipboard!`,
                    showConfirmButton: false,
                    timer: 2000,
                    background: '#1e293b',
                    color: '#fff'
                });
            }).catch(err => {
                console.error("Failed to copy: ", err);
            });
        }

        // Initial render
        renderPackages();
    </script>
</body>
</html>
