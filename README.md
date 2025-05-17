# html-tags

| توضیح | کد HTML |
|-------|---------|
| تگ `<div>` برای دسته‌بندی یا قالب‌بندی بخش‌هایی از محتوا استفاده می‌شود. | `<div>محتوا</div>` |
| تگ `<p>` برای ساخت پاراگراف‌های متنی در صفحه کاربرد دارد. | `<p>این یک پاراگراف نمونه است.</p>` |
| تگ `<h1>` برای نمایش تیتر اصلی یا بزرگ‌ترین عنوان در صفحه استفاده می‌شود. | `<h1>عنوان اصلی</h1>` |
| تگ‌های `<h2>` تا `<h6>` برای عناوین با سطح اهمیت پایین‌تر هستند. | `<h2>عنوان دوم</h2><br><h3>عنوان سوم</h3><br><h4>عنوان چهارم</h4><br><h5>عنوان پنجم</h5><br><h6>عنوان ششم</h6>` |
| برای ساخت لیست مرتب و نامرتب | `<ol start="5" type="I"><li>آیتم 1</li><li>آیتم 2</li></ol><br><ul type="square"><li>آیتم 1</li><li>آیتم 2</li></ul>` |
| تگ `<a>` برای ایجاد لینک کاربرد دارد. | `<a href="https://example.com">لینک به سایت</a>` |
| تگ `<img>` برای نمایش تصویر استفاده می‌شود. | `<img src="image.jpg" alt="توضیح تصویر" width="500" height="300">` |
| تگ `<video>` برای افزودن ویدیو همراه ویژگی‌هایی مانند controls و autoplay | `<video controls width="600"><source src="movie.mp4" type="video/mp4"><track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English"></video>` |
| تگ `<audio>` برای پخش فایل صوتی | `<audio controls src="audio.mp3">صدای شما پخش نشد</audio>` |
| تگ `<input>` برای دریافت داده از کاربر | `<input type="text" placeholder="متن ورودی">` |
| تگ `<textarea>` برای دریافت متن چندخطی از کاربر | `<textarea rows="4" cols="50">متن اولیه</textarea>` |
| تگ `<button>` برای ایجاد دکمه | `<button type="submit">ارسال</button>` |
| `<select>` و `<option>` برای ساخت منو کشویی | `<select><option value="1">گزینه ۱</option></select>` |
| `<fieldset>` و `<legend>` برای گروه‌بندی ورودی‌ها | `<fieldset><legend>عنوان گروه</legend><input type="text"></fieldset>` |
| تگ `<label>` برای برچسب‌گذاری ورودی‌ها | `<label for="id1">نام:</label><input id="id1" type="text">` |
| تگ `<datalist>` همراه با input برای پیشنهاد خودکار | `<input list="browsers"><datalist id="browsers"><option value="Chrome"></datalist>` |
| تگ `<form>` برای ارسال داده‌ها | `<form action="submit.php" method="post"><input type="text"><button type="submit">ارسال</button></form>` |
| تگ‌های جدول: `<table>`, `<tr>`, `<th>`, `<td>` | `<table><tr><th>عنوان</th></tr><tr><td>داده</td></tr></table>` |
| ویژگی‌های `colspan` و `rowspan` برای ادغام سلول‌ها | `<table border="1"><tr><td rowspan="2">سلول rowspan</td><td>سلول معمولی</td></tr><tr><td colspan="2">سلول colspan</td></tr></table>` |
| تگ‌های ساختاردهی جدول: `<caption>`, `<thead>`, `<tbody>`, `<tfoot>` | `<table><caption>عنوان جدول</caption><thead><tr><th>عنوان</th></tr></thead><tbody><tr><td>داده</td></tr></tbody><tfoot><tr><td>پاورقی</td></tr></tfoot></table>` |
| تگ‌های `<hr>` و `<br>` برای خط افقی و رفتن به خط بعد | `متن اول<br>متن دوم<br><hr>` |
| تگ `<dl>` برای لیست‌های توضیحی | `<dl><dt>HTML</dt><dd>زبان نشانه‌گذاری صفحات وب</dd></dl>` |
