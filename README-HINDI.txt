BABA ASTRO MANTRA — FINAL V15 WEBSITE PACK
==========================================

V15 में क्या बदला
- 92 श्रेणियाँ और 822 कैटलॉग प्रविष्टियाँ वेबसाइट के डिफ़ॉल्ट डेटा में शामिल हैं।
- सभी 822 प्रविष्टियों में पाठ/विषय-विवरण, हिंदी अर्थ/व्याख्या और स्रोत-नोट भरे हुए हैं; खाली placeholder टोकन शेष नहीं हैं।
- प्रचलित/पहचाने गए मंत्रों में देवनागरी पाठ और सरल हिंदी भावार्थ दिया गया है।
- जहाँ प्रविष्टि पूजा-विधि, अध्ययन-सामग्री, संपादकीय प्रार्थना या लंबे स्तोत्र/चालीसा का परिचय/अंश है, वहाँ उसका प्रकार स्पष्ट किया गया है। ऐसी प्रविष्टियों को बिना स्रोत-जाँच के मूल वैदिक मंत्र या पूर्ण स्तोत्र न मानें।
- ऊपर की चलती पट्टी की अवधि 240 से 1200 सेकंड के बीच रखी गई है ताकि बड़ी सूची धीरे चले।
- लोकल storage key V15 है, जिससे पुराने V13/V14 browser data से नई default सामग्री छिपने का जोखिम कम होता है।

फोल्डर में मुख्य फाइलें
- index.html: वेबसाइट का पेज और नेविगेशन
- style.css: मोबाइल/डेस्कटॉप डिज़ाइन और marquee animation
- script.js: 92 श्रेणियाँ, 822 प्रविष्टियाँ, खोज, पसंदीदा, दैनिक मंत्र और Admin editor
- data/categories-92.json: 92 श्रेणियों का संरचित डेटा
- data/mantras-library-v8.json: 822 प्रविष्टियों की पाठ/अर्थ/स्रोत फ़ील्ड वाली reference library
- V15-CONTENT-QUALITY-REPORT.json: डेटा-जाँच का सार
- assets/images/UPLOAD-IMAGES-HERE.txt: अपनी तस्वीरें जोड़ने के निर्देश

चलाने का तरीका
1. ZIP को डाउनलोड कर Extract करें।
2. पूरे BABA_ASTRO_MANTRA_FINAL_V15 फोल्डर को SPCK Editor में Import करें, या कंप्यूटर पर उसी फोल्डर की index.html खोलें।
3. फाइलों को अलग-अलग जगह न ले जाएँ; index.html, script.js, style.css, data और assets साथ रहें।
4. पुराना फोल्डर या पुरानी index.html न खोलें। V15 अलग फोल्डर से चलाएँ।
5. अपनी सामग्री संपादित करने से पहले Admin > Backup/Export से बैकअप बना लें।

Admin और सुरक्षा
- लोकल प्रोटोटाइप का पासवर्ड: Tata@2004
- Admin gate browser-side है; इसे public production website की सुरक्षित authentication न मानें।
- browser localStorage में सामग्री उसी browser/device पर रहती है, users/devices में अपने-आप sync नहीं होती। Production के लिए server-side login, database, secure backup और proper permissions आवश्यक हैं।

सामग्री-गुणवत्ता नोट
- पुराने curated रिकॉर्ड की स्थिति भी source-review-needed हो सकती है।
- 298 प्रविष्टियाँ सामान्य/प्रचलित मंत्र-पाठ से भरी गई हैं और स्रोत-समीक्षा की सलाह दी जाती है।
- 367 प्रविष्टियाँ संपादकीय शुरुआती सामग्री, पूजा-विधि, अध्ययन-नोट या सरल हिंदी प्रार्थना हैं। ये उपयोगी starter content हैं, पर इन्हें मूल शास्त्रीय मंत्र का दावा करके न दिखाएँ।
- 157 पहले से भरे रिकॉर्ड भी परंपरा/संस्करण के अनुसार स्रोत-जाँच के लिए चिह्नित हैं।
- धार्मिक पाठों के अर्थ और पाठांतर परंपरा के अनुसार बदल सकते हैं। स्वास्थ्य, धन या किसी परिणाम की गारंटी न दें।

चित्र अपलोड
- Logo: assets/logo.png (512×512 अनुशंसित)
- Hero: assets/hero.png (1600×900 अनुशंसित)
- Category images: assets/images/category-01.png आदि (900×600 अनुशंसित)

संपर्क/ब्रांड सेटिंग
BABA ASTRO MANTRA; फोन: 95196 08505; social handle: @infobabaastro. Public launch से पहले contact/social links सत्यापित करें।


V16 — IMAGE PATHS
सभी image locations के सही नाम और relative path के लिए IMAGE-PATH-MAP-HINDI.txt देखें। PNG तस्वीरें आपको स्वयं assets/images में अपलोड करनी हैं; इस पैकेज में कोई नई तस्वीर नहीं बनाई गई।


V19 — स्क्वेयर इमेज
- Logo, hero banner, categories, mantra cards, article/page images और daily image स्लॉट 1:1 अनुपात के हिसाब से हैं।
- अपनी सभी PNG इमेज वर्गाकार (1:1) आकार में रखें। CSS `object-fit: cover` इमेज को बॉक्स के भीतर फिट करता है।
