<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gupta Traders (गुप्ता ट्रेडर्स) - Fakharpur, Bahraich</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Poppins', sans-serif; }
    @media print { .no-print { display: none !important; } .print-only { display: block !important; } }
  </style>
</head>
<body class="bg-slate-50 text-slate-900">

  <div class="bg-slate-900 text-amber-400 text-xs sm:text-sm py-2 px-4 border-b border-slate-800 no-print">
    <div class="max-w-6xl mx-auto flex flex-wrap justify-between items-center gap-2">
      <div class="font-medium">📍 फखरपुर, बहराइच (उ.प्र.) | MSME Registered Building Material Store</div>
      <div class="flex items-center gap-3">
        <a href="tel:6394928538" class="text-white font-semibold">📞 Call: 6394928538</a>
        <a href="https://wa.me/919919359116" target="_blank" class="bg-emerald-600 text-white px-2.5 py-0.5 rounded font-semibold">💬 WhatsApp: 9919359116</a>
      </div>
    </div>
  </div>

  <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200 no-print">
    <div class="max-w-6xl mx-auto px-4 py-3.5 flex flex-wrap justify-between items-center gap-3">
      <div class="flex items-center gap-3">
        <div class="w-12 h-12 rounded-xl bg-amber-500 text-slate-950 font-extrabold text-2xl flex items-center justify-center shadow">GT</div>
        <div>
          <h1 class="text-xl sm:text-2xl font-extrabold text-slate-900">GUPTA TRADERS <span class="text-amber-600 text-base font-bold">(गुप्ता ट्रेडर्स)</span></h1>
          <p class="text-xs text-slate-500 font-medium">असली सीमेंट, गैलेंट सरिया, मोरंग और गिट्टी के थोक व फुटकर विक्रेता — फखरपुर, बहराइच</p>
        </div>
      </div>
      <div class="flex items-center gap-2">
        <a href="#calculator" class="bg-slate-100 text-slate-800 text-xs font-semibold px-3 py-2 rounded-lg">🧮 मकान कैलकुलेटर</a>
        <a href="#cartSection" class="bg-amber-500 text-slate-950 text-xs font-bold px-3.5 py-2 rounded-lg shadow flex items-center gap-1.5">
          <span>🛒 एस्टीमेट पर्ची</span>
          <span id="cartCountBadge" class="bg-slate-900 text-amber-400 px-1.5 py-0.5 rounded-full text-xs">3</span>
        </a>
      </div>
    </div>
  </header>

  <section class="bg-gradient-to-br from-slate-900 via-slate-800 to-slate-900 text-white py-8 px-4 no-print">
    <div class="max-w-6xl mx-auto grid md:grid-cols-12 gap-6 items-center">
      <div class="md:col-span-7 space-y-3">
        <div class="inline-block bg-amber-500/20 border border-amber-400/40 text-amber-300 text-xs font-semibold px-3 py-1 rounded-full">
          ✅ 100% ओरिजिनल ब्रांड्स • धर्मकांटा से सटीक तौल • ट्रैक्टर ट्रॉली व पिकअप डिलीवरी
        </div>
        <h2 class="text-3xl font-extrabold leading-tight">मजबूत मकान की नींव, <span class="text-amber-400">गुप्ता ट्रेडर्स</span> के भरोसे के साथ</h2>
        <p class="text-slate-300 text-sm">हमारे यहाँ <b>ACC Gold</b>, <b>Prism Champion Plus / Duratech</b>, <b>UltraTech Cement</b>, और <b>Gallant TMT Sariya (Fe 500D)</b> उचित रेट पर उपलब्ध हैं।</p>
        <div class="flex flex-wrap gap-3 pt-2">
          <a href="https://wa.me/919919359116?text=नमस्ते%20गुप्ता%20ट्रेडर्स,%20मुझे%20बिल्डिंग%20मटेरियल%20का%20रेट%20चाहिए।" target="_blank" class="bg-emerald-500 text-white font-bold px-5 py-3 rounded-xl shadow text-sm">💬 WhatsApp पर ऑर्डर करें (9919359116)</a>
          <a href="tel:6394928538" class="bg-white/10 border border-white/20 text-white font-semibold px-5 py-3 rounded-xl text-sm">📞 सीधी बात करें: 6394928538</a>
        </div>
      </div>

      <div class="md:col-span-5 bg-slate-800/90 border border-slate-700 rounded-2xl p-5 shadow-xl">
        <div class="flex justify-between items-center border-b border-slate-700 pb-3 mb-3">
          <div>
            <h3 class="font-bold text-amber-400 text-base">📊 आज का ताज़ा रेट (Showroom Rates)</h3>
            <p class="text-xs text-slate-400">फखरपुर, बहराइच • गुप्ता ट्रेडर्स</p>
          </div>
          <span class="bg-emerald-500/20 text-emerald-300 text-xs font-bold px-2.5 py-1 rounded-full">● Live Stock</span>
        </div>
        <div id="liveRateBoard" class="space-y-2 text-sm">
          <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Prism Champion Plus (50Kg)</span><span class="font-bold text-amber-400">₹370 / Bag</span></div>
          <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Prism Duratech (50Kg)</span><span class="font-bold text-amber-400">₹395 / Bag</span></div>
          <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Gallant TMT (10mm–20mm)</span><span class="font-bold text-emerald-400">₹6200 / क्विंटल</span></div>
          <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Gallant TMT (8mm सरिया)</span><span class="font-bold text-emerald-400">₹6400 / क्विंटल</span></div>
          <div class="flex justify-between py-1"><span>रेडीमेड छल्ला (TMT Rings)</span><span class="font-bold text-amber-400">₹63 / Kg</span></div>
        </div>
      </div>
    </div>
  </section>

  <main class="max-w-6xl mx-auto px-4 py-8 space-y-10 no-print">
    <section id="catalog">
      <div class="flex flex-wrap justify-between items-end gap-4 mb-5">
        <div>
          <h2 class="text-2xl font-extrabold text-slate-900">🧱 हमारे प्रोडक्ट्स और आज के रेट</h2>
          <p class="text-sm text-slate-600">वेरिएंट (साइज या ब्रांड) पर टैप करके असली रेट देखें और अपनी एस्टीमेट पर्ची में जोड़ें</p>
        </div>
        <div class="flex flex-wrap gap-2">
          <button onclick="filterCategory('all')" class="bg-slate-900 text-white px-3.5 py-2 rounded-lg text-xs font-bold">सभी सामान (All)</button>
          <button onclick="filterCategory('cement')" class="bg-white border border-slate-300 text-slate-700 px-3.5 py-2 rounded-lg text-xs font-semibold">सीमेंट (Cement)</button>
          <button onclick="filterCategory('steel')" class="bg-white border border-slate-300 text-slate-700 px-3.5 py-2 rounded-lg text-xs font-semibold">गैलेंट सरिया व छल्ला (TMT)</button>
          <button onclick="filterCategory('aggregates')" class="bg-white border border-slate-300 text-slate-700 px-3.5 py-2 rounded-lg text-xs font-semibold">मोरंग व गिट्टी</button>
        </div>
      </div>
      <div id="productGrid" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-5"></div>
    </section>

    <section id="calculator" class="bg-white rounded-2xl border border-slate-200 shadow-sm p-5">
      <span class="text-xs font-bold uppercase text-amber-600 bg-amber-50 px-2.5 py-1 rounded">Smart Tool</span>
      <h2 class="text-xl font-extrabold text-slate-900 mt-1">📐 मकान एरिया मटेरियल कैलकुलेटर (Sq.Ft Estimator)</h2>
      <div class="grid md:grid-cols-3 gap-4 mt-4">
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">एरिया (Square Feet में)</label>
          <input type="number" id="calcArea" value="1000" min="100" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm font-semibold" oninput="runAreaCalculator()" />
        </div>
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">मंजिल (Floors)</label>
          <select id="calcFloors" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm font-semibold" onchange="runAreaCalculator()">
            <option value="1">1 मंजिल (Ground Floor)</option>
            <option value="2">2 मंजिल (G + 1)</option>
            <option value="3">3 मंजिल (G + 2)</option>
          </select>
        </div>
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">निर्माण का काम</label>
          <select id="calcStage" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm font-semibold" onchange="runAreaCalculator()">
            <option value="slab">सिर्फ छत ढलाई (RCC Slab Only)</option>
            <option value="full">पूरा ढांचा (Foundation + Slab + Brick)</option>
          </select>
        </div>
      </div>
      <div id="calcOutput" class="grid grid-cols-2 sm:grid-cols-4 gap-3 mt-4"></div>
    </section>

    <section id="cartSection" class="bg-white rounded-2xl border-2 border-amber-500/70 shadow-md p-5">
      <div class="flex flex-wrap justify-between items-center gap-3 border-b border-slate-200 pb-3">
        <div>
          <h2 class="text-xl font-extrabold text-slate-900">🧾 आपकी कच्चा एस्टीमेट पर्ची (Estimate Cart)</h2>
          <p class="text-xs text-slate-600">सामान जोड़ें, कुल रकम देखें और सीधे WhatsApp (9919359116) पर भेजें</p>
        </div>
        <button onclick="window.print()" class="bg-slate-800 text-white text-xs font-semibold px-4 py-2 rounded-lg">🖨️ पर्ची प्रिंट / PDF सेव करें</button>
      </div>
      <div id="cartItemsContainer" class="mt-3"></div>
      <div class="grid sm:grid-cols-3 gap-4 mt-5 pt-4 border-t border-slate-200">
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">आपका नाम (Customer Name)</label>
          <input type="text" id="custName" placeholder="अपना नाम लिखें..." class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm" />
        </div>
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">गाँव / साइट का पता (Fakharpur / Bahraich)</label>
          <input type="text" id="custVillage" placeholder="जैसे: फखरपुर बाज़ार..." class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm" />
        </div>
        <div>
          <label class="block text-xs font-bold text-slate-700 mb-1">डिलीवरी गाड़ी (Delivery Option)</label>
          <select id="custVehicle" class="w-full border border-slate-300 rounded-lg px-3 py-2 text-sm font-medium">
            <option value="ट्रैक्टर ट्रॉली (Tractor Trolley)">🚜 ट्रैक्टर ट्रॉली (Tractor Trolley)</option>
            <option value="पिकअप / छोटा लोडर (Pickup)">🛻 पिकअप / छोटा लोडर (Pickup)</option>
            <option value="दुकान से खुद ले जाएंगे (Self Pickup)">🏪 दुकान से खुद ले जाएंगे (Self Pickup)</option>
          </select>
        </div>
      </div>
      <div class="mt-5 flex flex-wrap justify-between items-center gap-4 bg-amber-50 border border-amber-200 rounded-xl p-4">
        <div>
          <div class="text-xs text-slate-600 font-semibold">अनुमानित कुल योग (Estimated Total):</div>
          <div id="grandTotalDisplay" class="text-2xl font-extrabold text-slate-900">₹82,075</div>
          <div class="text-[11px] text-slate-500">* भाड़ा दूरी के अनुसार अलग से जोड़ा जा सकता है।</div>
        </div>
        <button onclick="sendOrderOnWhatsApp()" class="bg-emerald-600 hover:bg-emerald-700 text-white font-bold px-5 py-3 rounded-xl shadow text-sm">
          💬 WhatsApp पर ऑर्डर / एस्टीमेट भेजें (9919359116)
        </button>
      </div>
    </section>
  </main>

  <footer class="bg-slate-900 text-slate-400 py-8 px-4 mt-10 no-print">
    <div class="max-w-6xl mx-auto flex flex-wrap justify-between items-center gap-4">
      <div>
        <h3 class="text-white font-bold text-lg">GUPTA TRADERS (गुप्ता ट्रेडर्स)</h3>
        <p class="text-xs mt-1">📍 फखरपुर, जिला बहराइच, उत्तर प्रदेश | 📞 6394928538 | 💬 WhatsApp: 9919359116</p>
      </div>
      <button onclick="openAdminModal()" class="bg-slate-800 text-amber-400 border border-slate-700 text-xs font-semibold px-3.5 py-2 rounded-lg">
        🔐 Shop Admin
      </button>
    </div>
  </footer>

  <div id="adminModal" class="fixed inset-0 bg-black/70 hidden items-center justify-center p-4 z-50 no-print">
    <div class="bg-white rounded-2xl max-w-lg w-full p-5 shadow-2xl max-h-[90vh] overflow-y-auto">
      <div class="flex justify-between items-center border-b pb-3 mb-4">
        <h3 class="font-extrabold text-base text-slate-900">🔐 Gupta Traders — Owner Rate Panel</h3>
        <button onclick="closeAdminModal()" class="text-slate-500 font-bold text-lg">✕</button>
      </div>
      <div id="pinGateSection">
        <label class="block text-xs font-bold text-slate-700 mb-1">Owner Secret PIN डालें:</label>
        <div class="flex gap-2">
          <input type="password" id="adminPinInput" placeholder="Enter PIN" class="border border-slate-300 rounded-lg px-3 py-2 text-sm w-full font-bold" />
          <button onclick="verifyAdminPin()" class="bg-amber-500 text-slate-950 font-bold px-4 py-2 rounded-lg text-sm">Unlock</button>
        </div>
        <p id="pinErrorMsg" class="text-xs text-red-600 mt-1 hidden">❌ गलत पिन! केवल दुकान मालिक ही लॉगिन कर सकते हैं।</p>
      </div>
      <div id="rateEditorSection" class="hidden space-y-3">
        <div id="adminRateInputs" class="space-y-3"></div>
        <div class="flex justify-between pt-3 border-t">
          <button onclick="resetDefaultRates()" class="text-xs text-red-600 font-semibold">Reset Default</button>
          <button onclick="saveNewRates()" class="bg-emerald-600 text-white font-bold px-5 py-2 rounded-lg text-sm">💾 Save Rates</button>
        </div>
      </div>
    </div>
  </div>

  <script>
    const OWNER_PIN = "9555";
    const DEFAULT_PRODUCTS = [
      { id: "prism-cement", category: "cement", name: "Prism Cement (प्रिज्म सीमेंट)", badge: "Top Selling", unit: "Bag (50 Kg)", desc: "छत ढलाई, बीम और प्लास्टर के लिए शानदार मजबूती।", selectedVariantIndex: 0, variants: [{ label: "Prism Champion Plus (50Kg)", price: 370 }, { label: "Prism Duratech (50Kg)", price: 395 }] },
      { id: "acc-cement", category: "cement", name: "ACC Gold Water Shield Cement", badge: "Water Resistant", unit: "Bag (50 Kg)", desc: "सीपेज और नमी से सुरक्षा देने वाला प्रीमियम ACC सीमेंट।", selectedVariantIndex: 0, variants: [{ label: "ACC Gold Water Shield (50Kg)", price: 410 }, { label: "ACC Concrete+ (50Kg)", price: 395 }] },
      { id: "ultratech-cement", category: "cement", name: "UltraTech Cement (अल्ट्राटेक सीमेंट)", badge: "Heavy RCC", unit: "Bag (50 Kg)", desc: "फाउंडेशन, पिलर और स्लैब के लिए भरोसेमंद सीमेंट।", selectedVariantIndex: 0, variants: [{ label: "UltraTech Standard (50Kg)", price: 400 }, { label: "UltraTech Super (50Kg)", price: 415 }] },
      { id: "gallant-tmt", category: "steel", name: "Gallant TMT Sariya (गैलेंट सरिया Fe 500D)", badge: "धर्मकांटा तौल", unit: "Quintal (100 Kg)", desc: "भूकंप रोधी ओरिजिनल गैलेंट सरिया। (8mm का रेट बेस से ₹200 अधिक)", selectedVariantIndex: 1, variants: [{ label: "8mm Gallant TMT (100 Kg)", price: 6400 }, { label: "10mm Gallant TMT (100 Kg)", price: 6200 }, { label: "12mm Gallant TMT (100 Kg)", price: 6200 }, { label: "16mm Gallant TMT (100 Kg)", price: 6200 }, { label: "20mm Gallant TMT (100 Kg)", price: 6200 }] },
      { id: "tmt-rings", category: "steel", name: "Ready-Made TMT Rings (रेडीमेड छल्ला / रिंग)", badge: "₹63 / Kg", unit: "Kg (किलो)", desc: "पिलर और बीम के लिए तैयार मजबूत सरिया के छल्ले।", selectedVariantIndex: 0, variants: [{ label: "7x7 Ring (प्रति किलो)", price: 63 }, { label: "7x9 Ring (प्रति किलो)", price: 63 }, { label: "9x9 Ring (प्रति किलो)", price: 63 }, { label: "9x12 Ring (प्रति किलो)", price: 63 }] },
      { id: "binding-wire", category: "steel", name: "TMT Binding Wire (सरिया बांधने वाला तार)", badge: "Soft Wire", unit: "Kg (किलो)", desc: "जाल और छल्ला बांधने के लिए नरम व मजबूत तार।", selectedVariantIndex: 0, variants: [{ label: "18 Gauge Binding Wire (1 Kg)", price: 95 }] },
      { id: "red-morang", category: "aggregates", name: "असली लाल मोरंग (Coarse Red Sand)", badge: "Tractor Trolley", unit: "Trolley / Cu.Ft", desc: "साफ, दानेदार लाल मोरंग — ट्रैक्टर ट्रॉली व पिकअप सप्लाई।", selectedVariantIndex: 0, variants: [{ label: "100 Cu.Ft (1 ट्रैक्टर ट्रॉली)", price: 6800 }, { label: "50 Cu.Ft (हाफ ट्रॉली / पिकअप)", price: 3500 }] },
      { id: "stone-gitti", category: "aggregates", name: "क्रशर गिट्टी (Stone Grit 10mm / 20mm)", badge: "RCC Grade", unit: "Trolley / Cu.Ft", desc: "छत की ढलाई के लिए साफ 20mm/10mm गिट्टी।", selectedVariantIndex: 0, variants: [{ label: "100 Cu.Ft (1 ट्रैक्टर ट्रॉली)", price: 6500 }, { label: "50 Cu.Ft (हाफ ट्रॉली / पिकअप)", price: 3300 }] }
    ];

    let products = JSON.parse(localStorage.getItem("gt_products_v4")) || JSON.parse(JSON.stringify(DEFAULT_PRODUCTS));
    let activeCategory = "all";
    let cart = [{ prodId: "prism-cement", varIndex: 0, qty: 50 }, { prodId: "gallant-tmt", varIndex: 2, qty: 10 }, { prodId: "tmt-rings", varIndex: 0, qty: 25 }];

    function renderLiveRateBoard() {
      const prism = products.find(p => p.id === "prism-cement");
      const gallant = products.find(p => p.id === "gallant-tmt");
      const rings = products.find(p => p.id === "tmt-rings");
      document.getElementById("liveRateBoard").innerHTML = `
        <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Prism Champion Plus (50Kg)</span><span class="font-bold text-amber-400">₹${prism.variants[0].price} / Bag</span></div>
        <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Prism Duratech (50Kg)</span><span class="font-bold text-amber-400">₹${prism.variants[1].price} / Bag</span></div>
        <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Gallant TMT (10mm–20mm)</span><span class="font-bold text-emerald-400">₹${gallant.variants[1].price} / क्विंटल</span></div>
        <div class="flex justify-between py-1 border-b border-slate-700/70"><span>Gallant TMT (8mm सरिया)</span><span class="font-bold text-emerald-400">₹${gallant.variants[0].price} / क्विंटल</span></div>
        <div class="flex justify-between py-1"><span>रेडीमेड छल्ला (TMT Rings)</span><span class="font-bold text-amber-400">₹${rings.variants[0].price} / Kg</span></div>`;
    }

    function renderProducts() {
      const filtered = activeCategory === "all" ? products : products.filter(p => p.category === activeCategory);
      document.getElementById("productGrid").innerHTML = filtered.map(prod => {
        const cv = prod.variants[prod.selectedVariantIndex] || prod.variants[0];
        return `
          <div class="bg-white rounded-2xl border border-slate-200 shadow-sm p-5 flex flex-col justify-between">
            <div>
              <div class="flex justify-between items-center"><span class="text-[11px] font-bold uppercase px-2 py-0.5 rounded bg-amber-100 text-amber-900">${prod.badge}</span><span class="text-xs text-slate-500 font-semibold">${prod.unit}</span></div>
              <h3 class="text-lg font-extrabold text-slate-900 mt-2">${prod.name}</h3>
              <p class="text-xs text-slate-600 mt-1">${prod.desc}</p>
              <div class="mt-3">
                <div class="text-[11px] font-bold text-slate-500 mb-1">ग्रेड / साइज चुनें (Tap):</div>
                <div class="flex flex-wrap gap-1.5">
                  ${prod.variants.map((v, i) => `<button onclick="selectVariant('${prod.id}',${i})" class="px-2.5 py-1 rounded-lg text-xs font-bold border ${i === prod.selectedVariantIndex ? 'bg-slate-900 text-amber-400 border-slate-900' : 'bg-slate-100 text-slate-700 border-slate-200'}">${v.label} — ₹${v.price}</button>`).join("")}
                </div>
              </div>
            </div>
            <div class="mt-4 pt-3 border-t border-slate-100 flex items-center justify-between">
              <div><div class="text-[11px] text-slate-500">${cv.label}</div><div class="text-2xl font-extrabold text-slate-900">₹${cv.price.toLocaleString('en-IN')}</div></div>
              <button onclick="addToCart('${prod.id}', ${prod.selectedVariantIndex})" class="bg-amber-500 hover:bg-amber-600 text-slate-950 font-bold text-xs px-4 py-2.5 rounded-xl shadow">+ पर्ची में जोड़ें</button>
            </div>
          </div>`;
      }).join("");
    }

    function selectVariant(id, idx) { const p = products.find(x => x.id === id); if (p) { p.selectedVariantIndex = idx; renderProducts(); } }
    function filterCategory(cat) { activeCategory = cat; renderProducts(); }
    function addToCart(prodId, varIndex) {
      const ex = cart.find(i => i.prodId === prodId && i.varIndex === varIndex);
      if (ex) ex.qty += 1; else cart.push({ prodId, varIndex, qty: 1 });
      renderCart();
    }
    function updateCartQty(idx, val) { const q = parseInt(val, 10); if (!q || q <= 0) cart.splice(idx, 1); else cart[idx].qty = q; renderCart(); }
    function removeCartItem(idx) { cart.splice(idx, 1); renderCart(); }

    function renderCart() {
      document.getElementById("cartCountBadge").textContent = cart.length;
      const box = document.getElementById("cartItemsContainer");
      if (cart.length === 0) { box.innerHTML = `<div class="py-4 text-center text-slate-500 text-sm">पर्ची खाली है। ऊपर सामान जोड़ें।</div>`; document.getElementById("grandTotalDisplay").textContent = "₹0"; return; }
      let total = 0;
      box.innerHTML = cart.map((item, idx) => {
        const p = products.find(x => x.id === item.prodId);
        const v = p.variants[item.varIndex] || p.variants[0];
        const sub = v.price * item.qty; total += sub;
        return `<div class="flex flex-wrap justify-between items-center gap-2 py-2.5 border-b border-slate-200">
          <div><div class="font-bold text-sm">${p.name}</div><div class="text-xs text-slate-500">${v.label} • ₹${v.price}</div></div>
          <div class="flex items-center gap-2">
            <input type="number" min="1" value="${item.qty}" onchange="updateCartQty(${idx}, this.value)" class="w-16 border rounded px-2 py-1 text-sm font-bold text-center" />
            <div class="font-extrabold text-sm w-24 text-right">₹${sub.toLocaleString('en-IN')}</div>
            <button onclick="removeCartItem(${idx})" class="text-red-500 font-bold px-1">✕</button>
          </div>
        </div>`;
      }).join("");
      document.getElementById("grandTotalDisplay").textContent = "₹" + total.toLocaleString("en-IN");
    }

    function runAreaCalculator() {
      const a = (parseFloat(document.getElementById("calcArea").value) || 0) * (parseInt(document.getElementById("calcFloors").value, 10) || 1);
      const s = document.getElementById("calcStage").value === "slab";
      document.getElementById("calcOutput").innerHTML = `
        <div class="bg-slate-50 border rounded-xl p-3"><div class="text-xs text-slate-500">सीमेंट</div><div class="text-lg font-extrabold">${Math.round(a * (s ? 0.085 : 0.4))} Bags</div></div>
        <div class="bg-slate-50 border rounded-xl p-3"><div class="text-xs text-slate-500">गैलेंट सरिया</div><div class="text-lg font-extrabold">${(a * (s ? 0.008 : 0.035)).toFixed(1)} क्विंटल</div></div>
        <div class="bg-slate-50 border rounded-xl p-3"><div class="text-xs text-slate-500">लाल मोरंग</div><div class="text-lg font-extrabold">${Math.round(a * (s ? 0.18 : 1.2))} Cu.Ft</div></div>
        <div class="bg-slate-50 border rounded-xl p-3"><div class="text-xs text-slate-500">गिट्टी (20mm)</div><div class="text-lg font-extrabold">${Math.round(a * (s ? 0.35 : 0.9))} Cu.Ft</div></div>`;
    }

    function sendOrderOnWhatsApp() {
      const name = document.getElementById("custName").value.trim() || "ग्राहक";
      const village = document.getElementById("custVillage").value.trim() || "फखरपुर / बहराइच";
      const vehicle = document.getElementById("custVehicle").value;
      let total = 0;
      const lines = cart.map((item, i) => {
        const p = products.find(x => x.id === item.prodId);
        const v = p.variants[item.varIndex] || p.variants[0];
        const sub = v.price * item.qty; total += sub;
        return `${i + 1}. *${v.label}* — ${item.qty} × ₹${v.price} = *₹${sub.toLocaleString('en-IN')}*`;
      }).join("%0A");
      const msg = `*नमस्ते गुप्ता ट्रेडर्स (फखरपुर)* 🙏%0A*नाम:* ${encodeURIComponent(name)}%0A*पता:* ${encodeURIComponent(village)}%0A*डिलीवरी:* ${encodeURIComponent(vehicle)}%0A%0A*🧾 एस्टीमेट:*%0A${lines}%0A%0A*💰 कुल योग: ₹${total.toLocaleString('en-IN')}*`;
      window.open(`https://wa.me/919919359116?text=${msg}`, "_blank");
    }

    function openAdminModal() { document.getElementById("adminModal").classList.replace("hidden", "flex"); }
    function closeAdminModal() { document.getElementById("adminModal").classList.replace("flex", "hidden"); }
    function verifyAdminPin() {
      if (document.getElementById("adminPinInput").value.trim() === OWNER_PIN) {
        document.getElementById("pinGateSection").classList.add("hidden");
        document.getElementById("rateEditorSection").classList.remove("hidden");
        document.getElementById("adminRateInputs").innerHTML = products.map((p, pi) => `<div class="border rounded p-2 bg-slate-50"><div class="font-bold text-xs mb-1">${p.name}</div>${p.variants.map((v, vi) => `<div class="flex justify-between items-center py-1"><span class="text-xs">${v.label}</span><input type="number" id="r_${pi}_${vi}" value="${v.price}" class="w-24 border rounded px-2 py-0.5 text-xs font-bold text-right"/></div>`).join("")}</div>`).join("");
      } else document.getElementById("pinErrorMsg").classList.remove("hidden");
    }
    function saveNewRates() {
      products.forEach((p, pi) => p.variants.forEach((v, vi) => { const val = parseFloat(document.getElementById(`r_${pi}_${vi}`).value); if (val > 0) v.price = val; }));
      localStorage.setItem("gt_products_v4", JSON.stringify(products));
      renderLiveRateBoard(); renderProducts(); renderCart(); closeAdminModal();
    }
    function resetDefaultRates() { localStorage.removeItem("gt_products_v4"); products = JSON.parse(JSON.stringify(DEFAULT_PRODUCTS)); renderLiveRateBoard(); renderProducts(); renderCart(); closeAdminModal(); }

    renderLiveRateBoard(); renderProducts(); runAreaCalculator(); renderCart();
  </script>
</body>
</html>
