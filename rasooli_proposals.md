	  به نام خدا
# پیشنهادهای مرتبط با  پردازش زبان طبیعی و یادگیری خودکار

## برچسب‌زنی اجزای سخن با مدل پنهان مارکوف و پرسپترون ساخت‌یافته
 &#x202b;  پیاده‌سازی کامل مقالهٔ کالینز ۲۰۰۲ بر روی پیکرهٔ دادگان.
 
 [پیوند مقاله](http://www.aclweb.org/anthology/W02-1001)
 
* موارد زیر باید گزارش شود* 

 	*   &#x202b; دقت پرسپترون معمولی بر روی بخش validation یا توسعهٔ پیکره
	*   &#x202b; عملکرد averaged perceptron  بر روی بخش توسعهٔ‌ پیکره
	*  &#x202b; عملکرد averaged perceptron  روی بخش آزمون یا test پیکره
	*  &#x202b; تکرار گردش تکرار هر کدام از دو روش تا همگرا شدن

پیش‌نیاز برای پیاده‌سازی

*‌ &#x202b; تسلط بر مفهوم یادگیری برخط و الگوریتم پرسپترون

*‌ &#x202b; تسلط بر مفهوم برنامه‌سازی پویا (Dyanamic programming))

* &#x202b; تسلط بر HMM
	
## برچسب‌زنی بی‌ناظر اجزای سخن با استفاده از الگوریتم ای.ام.
این کار را بر روی پیکرهٔ فارسی دادگان امتحان کنید.
  &#x202b; 
  برای این کار می‌توانید از الگوی مرتبهٔ ۲ یا bigram استفاده کنید
و از الگوریتم Forward-Backward برای تخمین مقادیر احتمالی استفاده نمایید.  مقادیر ممکن برای هر کلمه را به صورت واژه‌نامه‌ای روی از دادهٔ یادگیری تهیه  کنید و  با استفاده از همگرایی درست‌نمایی (likelihood)   بر روی دادهٔ‌ توسعه تکرار یادگیری را متوقف کنید. نتیجه نهایی از روی مقداردهی اولیه با توزیع یکنواخت  بر روی دادهٔ  آزمون پیکره‌ٔ دادگان گزارش شود. نتیجهٔ‌ نهایی با حالتی که هر کلمه تنها یک برچسب اجزای سخن می‌گیرد و آن هم پرتکرارترین اجزای سخن آن کلمه است مقایسه شود.


پیش‌نیاز برای پیاده‌سازی

*‌ &#x202b; تسلط بر مفهوم یادگیری بی‌ناظر و الگوریتم EM

*‌ &#x202b; تسلط بر مفهوم برنامه‌سازی پویا (Dynamic programming))

* &#x202b; تسلط بر HMM
* &#x202b; تسلط بر الگوریتم Forward-Backward

مقالات مرتبط در این زمینه را می‌توانید از این [مقاله](http://www.aclweb.org/anthology/D10-1056.pdf)
بیابید


برای یادگیری الگوریتم فوروارد بک‌وارد
http://www.cs.columbia.edu/~mcollins/fb.pdf


## برچسب‌زنی بی‌ناظر اجزای سخن با الگوریتم نمونه‌بردای گیبز
  &#x202b; 
  برای این کار می‌توانید از الگوی مرتبهٔ ۲ یا bigram استفاده کنید
و برای تخمین پارامترها از نمونه‌گیری نقطه‌ای (pointwise).
تعداد پارامترها را مساوی با تعداد برچسب‌ها در پیکرهٔ یادگیری قرار داده،‌  مقادیر ممکن برای هر کلمه را به صورت واژه‌نامه‌ای روی از دادهٔ یادگیری تهیه  کنید و  با استفاده از همگرایی درست‌نمایی (likelihood)   بر روی دادهٔ‌ توسعه تکرار یادگیری را متوقف کنید. نتیجه نهایی از روی مقداردهی اولیه با توزیع یکنواخت  بر روی دادهٔ  آزمون پیکره‌ٔ دادگان گزارش شود. نتیجهٔ‌ نهایی با حالتی که هر کلمه تنها یک برچسب اجزای سخن می‌گیرد و آن هم پرتکرارترین اجزای سخن آن کلمه است مقایسه شود.

برای مطالعه و یادگیری در مورد نمونه‌برداری گیبز:
[مقاله ۱](http://www.isi.edu/natural-language/people/bayes-with-tears.pdf)
[مقاله ۲](http://www.aclweb.org/anthology/D/D08/D08-1036.pdf)
[مقاله ۳](http://www.umiacs.umd.edu/~resnik/pubs/gibbs.v0.3.pdf)