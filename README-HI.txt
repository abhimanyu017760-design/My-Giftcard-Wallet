MY GIFT WALLET — शुरुआत करने का तरीका

यह एक शुरुआती Android-friendly web app (PWA) है। डेटा फोन के ब्राउज़र में IndexedDB में सेव होता है।
फीचर: Gift Card रिकॉर्ड, purchase/store/order/date/status, notes, image/video/PDF proof, search/filter, export/import backup, optional PIN screen.

फोन में चलाने / इंस्टॉल करने के लिए:
1. ZIP को extract करें।
2. ऐप को HTTPS वेबसाइट पर होस्ट करना होगा ताकि Android Chrome इसे installable app की तरह जोड़ सके।
3. मुफ्त तरीका: GitHub पर नया public repository बनाएं, इस ZIP की सभी files upload करें।
4. Repository Settings > Pages > Deploy from a branch > main / root चुनें।
5. GitHub Pages URL Android Chrome में खोलें > browser menu > Add to Home screen / Install app.

जरूरी बातें:
- यह ऐप अभी Play Store पर प्रकाशित नहीं है; GitHub Pages से निजी तौर पर इस्तेमाल किया जा सकता है।
- डेटा इसी ब्राउज़र/फोन में रहता है। फोन बदलने या browser data साफ करने से पहले Export Backup करें।
- Export Backup में Gift Card code और सभी attachments शामिल हो सकते हैं। JSON backup को सुरक्षित रखें और किसी से साझा न करें।
- PIN एक साधारण app-opening lock है, मजबूत encryption नहीं। Gift Card PIN/code को संवेदनशील जानकारी मानें।
- वीडियो/फोटो के लिए 50 MB प्रति file सीमा रखी गई है। फोन की storage सीमा के अनुसार बड़ी files न जोड़ें।
- यह पहला version है; biometric lock, encrypted vault, cloud sync और advanced history बाद में जोड़े जा सकते हैं।
