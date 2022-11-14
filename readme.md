# پروژه امید

ما در پروژه امید خواهان فراهم آوردن اینترنت آزاد برای همه ایران هستیم. اینجا محفلی است برای به اشتراک گذاری تکنولوژی‌هایی که برای عبور از فیلترینگ حاکمیت ایران موثر هستند. هویت ما هیچگاه مشخص نخواهد شد و تا روز آزادی تلاش‌مان را برای گسترش اینترنت آزاد در ایران ادامه خواهیم داد. 

# دیواره آتش فیلترینگ
سامانه فیلترینگی که در ایران استفاده می‌شود، در واقع یک سیستم چینی است موسوم به [Great Firewall یا GFW](https://en.wikipedia.org/wiki/Great_Firewall). نام این هیولا، اشاره به دیوار باستانی چین دارد که بر دور کشور کشیده شد تا از دشمنانش مصون بماند. این سامانه در سال ۱۹۹۸ کلید ‌می‌خورد و ساخت فاز اولیه تا سال ۲۰۰۶ به طول می‌انجامد. به لطف سرمایه‌گذاری عظیم حزب کمونیست چین، سامانه GFW هر سال به روش‌های پیچیده‌تری برای فیلترینگ هوشمند تجهیز می‌شود و می‌تواند با جزییات بسیار بالا ترافیک عظیم جمعیت چند میلیادری چین را در لحظه مانیتور کرده، ترافیک مشکوک را ببندد و یا به مقامات به صورت خودکار گزارش ارسال کند. این دیواره آتش در واقع اژدهای هفت‌سری است که در دروازه‌های اینرنت ما هم ایستاده و از چرخش آزاد داده‌ها جلوگیری می‌کند. 

اما هر جا سیاهی باشد، جنگجویان روشنایی هم خواهند بود. داستان الهام‌بخش و البته کمترشنیده برای ما ایرانی‌ها این هست که متخصصان امنیت در تمام این سال‌ها در حال نبردی پیدا و پنهان با حزب کمونیست چین بوده‌اند. آن ها با ابداع روش‌های نوین در دور زدن GFW همواره توانسته‌اند دروازه‌های جهان آزاد را به روی مردم چین باز نگه دارند. هر بار حزب کمونیست سعی می‌کند با تقویت الگوریتم‌های GFW روش‌های ابداعی گروه مقاومت را بی‌اثر کند اما هر بار گروه مقاومت با روشی جدیدتر باز‌ می‌گردد. دانستن این نکات برای شهروند ایرانی از آن جهت حائز اهمیت هست که ما می‌توانیم از تمام این گنجینه‌ای که توسط متخصصان چینی و غربی برای فریب GFW فراهم شده استفاده کنیم تا دسترسی به اینترنت آزاد را برای مردم ایران به ارمغان بیاوریم.

شاید گفتن این نکته خالی از لطف نباشد که فیلترشکن‌هایی که در سال‌های گذشته در ایران رواج داشتند، مثل Freegate، Lantern، Ultrasurf و Psiphon همگی برنامه‌هایی بودند که توسط متخصصان برای عبور از دیواره آتش چینی طراحی شده بودند و برای همین هم در دور زدن سامانه فیلترینگ جمهوری اسلامی موثر عمل می‌کردند. حتی خیلی از این نرم‌افزار‌ها به طور پیشفرض از الفبای چینی استفاده می‌کردند، چون اساسا برای مخاطب چینی پیاده‌سازی شده بودند. اما به هر روی، همین نرم‌افزار‌ها در سال ۸۸ و پس از آن از ابزارهای اصلی مردم ایران برای دور زدن فیلترینگ جمهوری اسلامی بوده اند.

نحوه کارکرد GFW به طور دقیق مشخص نیست. مقاله‌های آکادمیک متعددی سعی کرده‌اند تا با آزمایش‌های متعدد از درون شبکه داخلی چین بتوانند از روی بروز رفتار بیرونی GFW به جزییات درونی سیستم آگاهی پیدا بکنند. از خلال این آزمایش‌ها، درک عظیمی نسبت به کارکرد این هیولا به دست آمده و منجر به تولد روش‌های موثر عبور از فیلترینگ هم شده. اما در این بازی موش و گربه، همواره GFW هم تلاش کرده تا با پیچیده‌تر کردن مکانیزم‌های فیلترینگ روش‌های دور زدن را یکی بعد از دیگری ابطال کند. برای همین، روشی که سال‌ها پیش موثر بوده، دیگر کارا نیست. روشی هم که امروز موثر هست، احتمالا فردا بسته خواهد شد. چیزی که به ما امید می‌دهد این هست که با همه دشواری‌ها در این تعقیب و گریز، بهترین و فداکارترین متخصصان هر بار راهی پیدا خواهند کرد تا یک قدم جلوتر از سرکوب‌گران آزادی قرار بگیرند و مجراهای اطلاعاتی هیچ‌گاه به طور کامل بسته نخواهد بود. مقالات زیر درک دقیق‌تری از نحوه کارکرد GFW به ما می‌دهند.

## مکانیزم فیلترینگ در GFW

مهم‌ترین ابزارهای فیلترینگ در سامانه GFW به شرح زیر هستند.

* حمله DNS Spoofing
* بستن IP
* ‌بررسی حضور کلیدواژه‌های حساس
* تکنیک Deep Packet Inspection


# مکانیزم‌های دور زدن GFW
در این قسمت روش‌هایی را که برای عبور از دیواره آتش GFW وجود دارد به طور خلاصه مرور می ‌کنیم. 

## پروتکل Shadowsocks
این پروژه در سال ۲۰۱۲ شروع به کار کرد و یکی از اولین پروتکل‌هایی بود که در چین برای بالا پریدن از دیوار GFW طراحی شد. علی‌رغم موفقیت بالا، برنامه‌نویس ناشناس این پروژه با شناسه clowwindy به دلایل نامعلومی مجبور شد که این پروژه را متوقف کند. امروز استفاده از Shadaowsocks ها به هیچ عنوان توصیه نمی‌شود، چون GFW به حدی توانمند شده که ترافیک این پروکسی دیگر از چشم‌هایش پنهان نیست. این امر می‌تواند خطر امنیتی برای مصرف‌کننده به همراه داشته باشد. نسل دوم این پروژه به نام ShadowsocksR تعدادی از مشکلات امنیتی نسل اول را برطرف کرده ولی حتی با این حال استفاده از آن توصیه نمی‌شود. از مزایای مهم Shadowsocks این می‌باشد که می‌تواند بر روی هر دو بستر انتقال TCP و UDP کار کند.


## پلتفرم V2Ray
در سال ۲۰۱۵ این [پروژه‌](https://github.com/v2fly/v2ray-core) نو توسط گروه ناشناس Project V معرفی می‌شود تا جایگزینی برای Shadowsocks باشد. برخلاف Shadowsocks، این پروژه صرفا یک پروتکل برای دور زدن GFW نیست بلکه یک پلتفرم است. پلتفرم بودن به این معنا است که این پروژه محدود به یک پروتکل مشخص نیست بلکه این امکان را فراهم می‌آورد که پروتکل‌های مختلف به صورت plug and play به سیستم اضافه بشوند. در واقع، این پروژه با این ذهنیت متولد شد که دیر یا زود GFW در شکار هر پروتکلی موفق خواهد شد، پس ما باید پلتفرمی طراحی کنیم که در این بازی تعقیب و گریز این امکان را فراهم کند تا متخصصین به آسانی بتوانند پروتکل‌هایی را که طراحی می‌کنند به  پلتفرم V2Ray اضافه کنند تا به سرعت در اختیار همگان قرار بگیرد.

با استفاده از این پلتفرم می‌توانیم پروتکل‌هایی نظیر SOCKS4، SOCKS5، ShadowSocks، پروکسی تلگرام MTProto و VMESS را برای کاربران بسازیم.


### پروتکل VMESS
این پروتکل در سال ۲۰۱۵ توسط گروه Project V طراحی شد تا به عنوان جایگزین Shadowsocks در پلتفرم V2Ray مورد استفاده قرار بگیرد. گاهی V2Ray و VMESS به جای یکدگیر در متون استفاده می‌شوند اما لازم است تاکید کنیم یکی پلتفرم هست و دیگری یک پروتکل. در زمان تولد، VMESS قادر بود تا با تغییر محتویات بسته‌های داده از اسکن Deep Packet Inspection که توسط GFW انجام می‌گرفت فرار کند. اما پیش از هر توضیحی باید بدانیم که این پروتکل از سال ۲۰۲۰ به این سو دیگر [امن در نظر گرفته نمی‌شود](https://github.com/net4people/bbs/issues/36#issuecomment-644929739) و ترافیک آن توسط GFW قابل شناسایی است. به هر روی، ویژگی‌های جالب این پروتکل به شرح زیر می‌باشد.

۱. رمزنگاری یا Encryption: پروتکل VMESS داده را به صورت پیش‌فرض رمزنگاری نمی‌کند. این بدین معنی است که کاربر موظف هست تا هنگام ساخت یک کانکشن VMESS حتما نوع رمزنگاری را نیز مشخص نماید. مثلا می‌توان از TLS استفاده کرد تا ترافیک قابل شناسایی نباشد. در غیر این صورت، استفاده کنندگان ممکن هست مورد شنود قرار بگیرند.

۲. در این پروتکل، کاربران نیازی به استفاده از پسورد ندارند تا بتوانند به server‌ متصل شوند. در VMESS به هر کاربر یک شناسه کاربری داده می‌شود که همان و فقط همان برای اتصال به server کافی است.

۳. پروتکل VMESS به زمان سیستم کاربر و server حساس هست و یا به عبارت Time Bound می‌باشد. در واقع، اگر اختلاف زمانی ساعت کاربر و سرور بیشتر از ۹۰ ثانیه باشد، پروتکل تمام درخواست‌های کاربر را قطع خواهد کرد. این پروتکل، از زمان برای رمزنگاری مطمئن داده‌ها استفاده می‌کند.

۴. پروتکل VMESS برای نقل و انتقال داده از لایه TCP استفاده می‌کند. ترافیکی که به UDP نیاز داشته باشد با تکنیک UDP over TCP منتقل خواهد شد. این موضوع یکی از تفاوت‌ها با Shadowsocks می‌باشد که قادر هست بر روی دو بستر TCP و UDP داده‌ها را منتقل کند. 

## پلتفرم Xray
در نوامبر ۲۰۲۰، گروهی ناشناس به نام Project X پروژه V2Ray را fork می‌کنند تا با رفع یک سری کاستی‌ها نسخه‌ خودشان به نام Xray را عرضه کنند. در واقع، پلتفرم Xray superset پلتفرم V2Ray می‌باشد که با داشتن همه خوبی‌های آن و رفع نواقصش تبدیل به پلتفرم غالب شده است. از نقاط قوت این پلتفرم جدید می توان گفت که Xray تا ۳۰ درصد کارایی بهتری نسبت به V2Ray دارد. همچنین، با ابداع پروتکلی جایگزین برای TLS‌ به نام XTLS این اجازه را می‌دهد تا داده‌های کاربران در شبکه داخلی کشور از امنیت بالاتری برخوردار باشند.

### پروتکل VLESS
در همان نوامبر ۲۰۲۰، گروه ناشناس Project X، پروتکل VLESS را به عنوان جایگزینی برای پروتکل VMESS طراحی کرد. این پروتکل هیچ کدام از معایت امنیتی VMESS را ندارد و هنوز GFW قادر به شناسایی بسته‌های داده رمزنگاری شده با VLESS‌ نیست. بعلاوه، VLESS به گونه‌ای بسیار کاراتر طراحی شده و به server اجازه می‌دهد تا به نسبت VMESS تعداد کاربران بیشتری را میزبانی کند. دقت کنید که به عنوان یه اشتباه مصطلح گاهی در متون Xray و VLESS به جای یکدیگر استفاده می‌شوند بااینکه یکی پلتفرم هست و دیگری پروتکل. در این لحظه پروتکل VLESS به همراه XTLS و بر روی TCP یکی از روش‌های کارا برای دور زدن GFW در ایران می‌باشد.
در این پروتکل، بر خلاف VMESS، مرحله‌ای برای رمزنگاری تعبیه نشده 

### پروتکل Trojan
در آگوست ۲۰۲۰، این پروتکل در سال ۲۰۱۷ توسعه داده شد و تا امروز هم در کنار VLESS روش بسیار موثر دیگری در دور زدن GFW می‌باشد. پروتکل Trojan ترافیک داده عبوری را به شکل ترافیک HTTPS ایی درمیاورد که GFW به عنوان ترافیک مجاز در نظر می‌گیرد. مطابق بر این پروتکل، در آغاز TLS Handshake به صورت کامل انجام می‌گیرد تا GFW تصور کند که این ترافیک عادی HTTPS‌ می‌باشد. تمام این ویژگی‌ها باعث می‌شود که عملکرد یک Trojan Server از نظر ناظر بیرونی کاملا شبیه به یک Web Server عادی به نظر برسد و همین کمک می‌کند که GFW به Server شما مشکوک نشود. مزیت بسیار مهم Trojan‌این هست که یک مرحله رمزنگاری کمتری به نسبت VLESS نیاز دارد و همین امر موجب می‌شود که فشار کمتری به منابع پردازشی Server و گوشی کاربر وارد شود. این پروتکل هر دو لایه انتقال TCP و UDP رو پشتیبانی می‌کند. 
لازم به ذکر هست که پروژه‌ دیگری به نام Trojan-Go بر پایه پروژه Trojan و با زبان GO نوشته شده است.

