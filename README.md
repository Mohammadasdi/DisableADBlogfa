# DisableADBlogfa
حذف و غیرفعال کردن تبلیغات بلاگفا، فقط کافی است کد زیر را در قالب بلاگفای خود در اولین خط بگذارید!
```html
<script src="https://raw.githubusercontent.com/Mohammadasdi/DisableADBlogfa/refs/heads/main/BlogfaAD.js"></script>
```
و یا کد زیر را در تک اسکریپت قالب قرار دهید(اگر کد بالا کار نکرد):
```html
<script>document.addEventListener("DOMContentLoaded",function(){document.querySelectorAll("a[onclick*=\"style.display='none';\"]").forEach(function(e){e.style.display="none"}),document.querySelectorAll("img[title='تبلیغات']").forEach(function(e){e.style.display="none"}),document.querySelectorAll("img[src*='https://www.blogfa.com/b/']").forEach(function(e){e.style.display="none"});let e=document.querySelectorAll("script[src]");e.forEach(function(e){e.src.startsWith("https://www.blogfa.com/a/")&&e.parentNode.removeChild(e)})});</script>
```

از اونجایی که قالب بلاگفا قابلیت اد کردن اسکریپت نداره، میتونین از کد زیر استفاده کنین!
```html
<link rel="stylesheet" href="https://raw.githubusercontent.com/Mohammadasdi/DisableADBlogfa/refs/heads/main/BlogfaAD.css">
```
این کد همیشه بروزرسانی میشود!
