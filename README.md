# Quran Easy Search Engine

**Quran easy search engine** is an advanced search and reading application designed for exploring Quranic text and Islamic resources. It offers powerful regex-based search capabilities and a beautiful Quran reading experience, optimized for both English and Urdu users. The app leverages `localforage` for offline data storage, ensuring fast and seamless access to content.

---

## Features and Functionalities

### English

1. **Advanced Regex Search**:
   - Perform complex searches using regular expressions to find specific words, phrases, or patterns in Quranic text and other Islamic resources.
   - Supports synonyms, diacritic-insensitive search, and OR searches (e.g., `کل/آج` converts to `کل||آج` for matching either term).
2. **Quran Navigation**:
   - Navigate through the entire Quran using **Next** (`»`) and **Previous** (`«`) buttons, moving sequentially (e.g., from ayah 23 to 24).
   - Jump to the full Quran reading mode from any ayah using the **Read from Here** (`📖`) button, displaying 20 ayahs per page.
3. **Full Quran Reading Mode**:
   - Access a dedicated Quran reader (`📚`) with 20 ayahs per page, featuring pagination and progress tracking.
   - Remembers the last reading position using `localStorage`, ensuring users can resume daily reading seamlessly.
   - Beautiful UI with centered text, shadows, and rounded borders for an enhanced reading experience.
4. **Font Customization**:
   - Quranic text uses the **Amiri** font (Google Fonts) for an authentic, traditional Arabic appearance.
   - Translations (tarjuma) use **Noto Nastaliq Urdu** for clear, elegant Urdu rendering.
5. **Offline Data Storage**:
   - Stores Quranic data (`quran.AM`) and other resources (`data.AM`) in `localforage` for offline access.
   - Displays a progress bar during initial data loading, with caching to prevent repeated downloads.
6. **Search History and Filters**:
   - Saves recent searches in `localStorage` for quick reuse.
   - Offers filters like synonym support, diacritic removal, and English search toggling for precise results.
7. **Responsive Design**:
   - Optimized for mobile and desktop browsers, with smooth scrolling and intuitive controls.
   - Supports right-to-left (RTL) text for Arabic and Urdu, with centered alignment for readability.
8. **Additional Features**:
   - Context menu for clearing search history or reloading data.
   - Pop-up windows for external links (e.g., YouTube videos) with customizable dimensions.
   - Random content display (`theRand`) for exploring resources when idle.

### Urdu

1. **جدید ریجیکس سرچ**:
   - قرآنی متن اور دیگر اسلامی وسائل میں مخصوص الفاظ، جملے یا پیٹرن تلاش کرنے کے لیے ریگولر ایکسپریشنز کا استعمال۔
   - مترادفات، ڈائکریٹک سے آزاد سرچ، اور OR سرچز کی حمایت (مثال کے طور پر، `کل/آج` کو `کل||آج` میں تبدیل کرتا ہے تاکہ دونوں میں سے کوئی ایک مل سکے)۔
2. **قرآن نیویگیشن**:
   - پورے قرآن میں **اگلا** (`»`) اور **پچھلا** (`«`) بٹنوں کے ذریعے ترتیب سے نیویگیشن (مثال کے طور پر، آیت 23 سے 24 تک)۔
   - کسی بھی آیت سے **یہاں سے پڑھیں** (`📖`) بٹن کے ذریعے مکمل قرآن ریڈنگ موڈ میں جائیں، جو فی صفحہ 20 آیات دکھاتا ہے۔
3. **مکمل قرآن ریڈنگ موڈ**:
   - وقف شدہ قرآن ریڈر (`📚`) فی صفحہ 20 آیات کے ساتھ، پیجینیشن اور پیشرفت ٹریکنگ کے ساتھ۔
   - `localStorage` کا استعمال کرتے ہوئے آخری پڑھائی کی پوزیشن یاد رکھتا ہے، تاکہ صارف روزانہ پڑھائی بغیر کسی رکاوٹ کے دوبارہ شروع کر سکیں۔
   - خوبصورت UI سینٹرڈ ٹیکسٹ، شیڈوز، اور گول بارڈرز کے ساتھ بہتر پڑھائی کے تجربے کے لیے۔
4. **فونٹ حسب ضرورت**:
   - قرآنی متن کے لیے **Amiri** فونٹ (گوگل فونٹس) جو روایتی عربی شکل دیتا ہے۔
   - ترجمہ (ترجمہ) کے لیے **Noto Nastaliq Urdu** فونٹ، جو واضح اور خوبصورت اردو رینڈرنگ کے لیے ہے۔
5. **آف لائن ڈیٹا سٹوریج**:
   - قرآنی ڈیٹا (`quran.AM`) اور دیگر وسائل (`data.AM`) کو `localforage` میں آف لائن رسائی کے لیے ذخیرہ کرتا ہے۔
   - ابتدائی ڈیٹا لوڈنگ کے دوران پروگریس بار دکھاتا ہے، کیچنگ کے ساتھ تاکہ بار بار ڈاؤن لوڈ نہ ہو۔
6. **سرچ ہسٹری اور فلٹرز**:
   - حالیہ سرچز کو `localStorage` میں محفوظ کرتا ہے تاکہ دوبارہ استعمال آسان ہو۔
   - مترادفات کی حمایت، ڈائکریٹک ہٹانے، اور انگریزی سرچ ٹوگلنگ جیسے فلٹرز درست نتائج کے لیے۔
7. **ریسپانسیو ڈیزائن**:
   - موبائل اور ڈیسک ٹاپ براؤزرز کے لیے بہتر بنایا گیا، ہموار اسکرولنگ اور بدیہی کنٹرولز کے ساتھ۔
   - عربی اور اردو کے لیے دائیں سے بائیں (RTL) ٹیکسٹ کی حمایت، پڑھنے کی آسانی کے لیے سینٹرڈ ایلائنمنٹ کے ساتھ۔
8. **اضافی خصوصیات**:
   - سرچ ہسٹری صاف کرنے یا ڈیٹا دوبارہ لوڈ کرنے کے لیے سیاق و سباق مینو۔
   - بیرونی لنکس (مثلاً یوٹیوب ویڈیوز) کے لیے حسب ضرورت طول و عرض کے ساتھ پاپ اپ ونڈوز۔
   - غیر فعال ہونے پر وسائل دریافت کرنے کے لیے بے ترتیب مواد ڈسپلے (`theRand`)۔

---

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yasinULLAH/easy-quran-search
   ```
2. **Set Up a Local Server**:
   - Use a local server (e.g., `Live Server` in VS Code or `python -m http.server`) to serve the app, as it relies on AJAX for data loading.
3. **Dependencies**:
   - Ensure an internet connection for initial data loading (`data.AM`, `quran.AM`) and font imports (Amiri, Noto Nastaliq Urdu).
   - The app includes jQuery, `localforage`, and other scripts (`eng_ur_db.js`, `fatawa.js`) in the repository.
4. **Run the App**:
   - Open `Index.html` in a browser. The app will load data (`data.AM`) and cache it using `localforage` for offline use.

---

## Usage

### English

1. **Search**:
   - Enter a query in the search bar (e.g., `اللہ&محمد` for AND, `کل/آج` for OR, or regex like `.*نماز.*`).
   - Use checkboxes for filters (synonyms, diacritics, English search).
   - View results with highlighted matches, navigable via **Next** (`»`) and **Previous** (`«`).
   - Click **Read from Here** (`📖`) to start Quran reading from the selected ayah.
2. **Quran Reading**:
   - Click the **Quran Reader** (`📚`) button in the top-right corner to enter full Quran mode.
   - Navigate pages using **Previous Page** and **Next Page** buttons.
   - The app remembers your last page for daily reading.
3. **Explore**:
   - Right-click search history items to clear them.
   - Click links in results to open pop-up windows for external content (e.g., YouTube).

### Urdu

1. **سرچ**:
   - سرچ بار میں استفسار درج کریں (مثلاً، `اللہ&محمد` کے لیے AND، `کل/آج` کے لیے OR، یا ریجیکس جیسے `.*نماز.*`)۔
   - فلٹرز کے لیے چیک باکسز استعمال کریں (مترادفات، ڈائکریٹکس، انگریزی سرچ)۔
   - نتائج ہائی لائٹ شدہ میچز کے ساتھ دیکھیں، جو **اگلا** (`»`) اور **پچھلا** (`«`) سے نیویگیٹ کیے جا سکتے ہیں۔
   - منتخب آیت سے قرآن پڑھنے کے لیے **یہاں سے پڑھیں** (`📖`) پر کلک کریں۔
2. **قرآن پڑھائی**:
   - مکمل قرآن موڈ میں داخل ہونے کے لیے اوپر دائیں کونے میں **قرآن ریڈر** (`📚`) بٹن پر کلک کریں۔
   - **پچھلا صفحہ** اور **اگلا صفحہ** بٹنوں سے صفحات نیویگیٹ کریں۔
   - ایپ آپ کے آخری صفحہ کو روزانہ پڑھائی کے لیے یاد رکھتی ہے۔
3. **دریافت**:
   - سرچ ہسٹری آئٹمز پر دائیں کلک کریں تاکہ انہیں صاف کیا جا سکے۔
   - نتائج میں لنکس پر کلک کریں تاکہ بیرونی مواد (مثلاً یوٹیوب) کے لیے پاپ اپ ونڈوز کھولیں۔

---

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contact

For questions or support, please contact \[yasincomps@gmail.com\] or open an issue on GitHub.
