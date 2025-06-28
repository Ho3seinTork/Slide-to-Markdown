---

### pptx2md.py

This script extracts all text content from a PowerPoint (`.pptx`) file and saves it into a Markdown (`.md`) file. It is useful for converting presentation slides into a readable text format for documentation, note-taking, or further editing.

#### How it works

- The script loads a PowerPoint file named `test.pptx`.
- It iterates through all slides and shapes in the presentation.
- If a shape contains text, it extracts the text and writes it to `output.md`, separating each text block with two newlines.

#### Usage

1. Place your PowerPoint file as `test.pptx` in the same directory as `pptx2md.py`.
2. Run the script:
   ```sh
   python pptx2md.py
   ```
3. The extracted text will be saved in `output.md`.

---

### pptx2md.py

این اسکریپت تمام محتوای متنی یک فایل پاورپوینت (`.pptx`) را استخراج کرده و در یک فایل مارک‌داون (`.md`) ذخیره می‌کند. این ابزار برای تبدیل اسلایدهای ارائه به فرمت متنی قابل خواندن جهت مستندسازی، یادداشت‌برداری یا ویرایش بیشتر کاربرد دارد.

#### نحوه کار

- اسکریپت فایل پاورپوینت با نام `test.pptx` را بارگذاری می‌کند.
- تمام اسلایدها و اشکال موجود در ارائه را بررسی می‌کند.
- اگر شکلی دارای متن باشد، متن آن را استخراج کرده و در فایل `output.md` ذخیره می‌کند و هر بخش متن را با دو خط جدید جدا می‌کند.

#### روش استفاده

1. فایل پاورپوینت خود را با نام `test.pptx` در همان پوشه‌ای که `pptx2md.py` قرار دارد، بگذارید.
2. اسکریپت را اجرا کنید:
   ```sh
   python pptx2md.py
   ```
3. متن استخراج‌شده در فایل `output.md` ذخیره خواهد شد.
