# Python haqida

Python - ham _oddiy_, ham _qudratli_ bo'lgan noyob dasturlash tillari sirasiga kiradi.  Siz dasturlash tilining sintaksisi va tuzilishini emas, balki muammoni yechimini qanchalik osonlik bilan topilishini ko'rib ajablanasiz.

Pythonga rasmiy kirish:

> Python - o'rganish uchun oson, qudratli dasturlash tilidir. U samarali yuqori pog'onali ma'lumotlar tuzilmasiga  va  ob'ektga yo'naltirilgan dasturlashga oddiy, lekin samarador yondashuvga ega. Pythonning oqilona sintaksisi va dinamik kod yozish imkoniyati, uning interpretatsiyalash xususiyati bilan birgalikda,  ko'pgina platformalardagi bir qancha sohalarda uni skriptlash va ilovalarni tezkor yaratish\(RAD\) uchun ideal tilga aylantiradi.

Bu imkoniyatlarning ko'pchiligini men keyingi bo'limlarda batafsil sharxlayman.

## Ism ortidagi hikoya

Python tilining yaratuvchisi Guido van Rossum bu tilni BBC kanalidagi "Monty Python'ning uchuvchi sirki" ko'rsatuvidan keyin nomlagan. U ovqatlanish uchun hayvonlarni o'zining uzun tanasi bilan o'rab, ularni bo'g'ib o'ldiradigan ilonlarni umuman yoqtirmaydi.

## Python'ning imkoniyatlari

### Oddiylik

Python - bu oddiy va minimalistik tildir. Pythoda yozilgan yaxshi dasturni o'qish deyarli ingliz tilini o'qishga o'xshaydi, xatto eng qat'iy ingliz tilini.  Python'ning bu psevdokod xususiyati uning eng katta kuchlaridan biridir. Bu sizga tilni o'zidan ko'ra masalani yechimini hal qilishga imkon beradi.

### O'rganish uchun oson

Python boshlash uchun juda oson ekanligiga o'zingiz guvoh bo'lasiz. Avval takidlaganimzdek,  Python juda ham oddiy sintaksga ega.

### Erkin va ochiq kodli

Python tili  _FLOSS_ \(Free/Libré and Open Source Software ya'ni Erkin va ochiq kodli dasturiy ta'minot\)ga misol bo'ladi. Oddiyroq aytganda siz dasturiy maxsulot nusxasini erkin tarqatishingiz, uning kodlarini o'qishingiz, unga o'zgartirish kiritishingiz, uning qismlaridan boshqa dasturiy maxsulot yaratishda foydalanishingiz mumkin.  FLOSS - bilimlarni ulashish jamiyati konseptsiyasiga asoslanadi.  Bu Pythonʻning kuchli tomonlaridan biridir, ya'ni   - u Python'ni yaxshilashga harakat qiladigan jamiyat tomonidan yaratilgan va doimiy rivojlantirib borilmoqda.

### Yuqori pogʻonadagi til

Siz Python tilida dastur yozayotganingizda, xotirani bshqarish va boshqa quyi pogʻona tafsilotlari haqida tashvishlanmasangiz ham boʻladi.

### Portativ

Oʻzining ochiq kod xususiyati sababli, Python juda koʻp platformalardan joy oldi. Agar tizimga bog'liq bo'lgan imkoniyatlar bo'lmasa sizning barcha python dasturlaringiz bu platformalarning barchasida hech qanday qo'shimcha o'zgartirishlarsiz  ishlashi mumkin.

SIz Python'dan GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE va PocketPC'larda foydalanishingiz mumkin!

Siz hatto [Kivy](https://kivy.org/) kabi platformalardan ham kompyuterlar, iPhone, iPad va Androidlar uchun o'yinlar yaratishda foydalnishingiz mumkin.

### Interpretatsiyalanadigan

Buni ozroq tushuntirishga to'g'ri keladi.

C va C++ kabi kompilatsiyalanadigan dastur C yoki C++ tilidan kompyuter tushunadigan til \(binary kod ya'ni 0 va 1 \)ga komplyator yordamida turli xil bayroqlar va optsiyalar bilan konvertlanadi. Siz dasturni ishga tushirganingizda yuklovchi dastur dasturingizning nusxasini qattiq diskdan xotiraga ko'chiradi va ishga tushiradi.

Boshqa tomondan, Python ikkilikka kompilyatsiya qilishni talab qilmaydi. Siz to'g'ridan-to'g'ri dasturni manba kodidan ishga tushirishingiz mumkin. Ichkarida esa Python  manba kodini baytkod deb nomlanadigan vositachi shaklga konvertlaydi va undan keyin uni kompyuter tushunadigan ikkilik kodga o'girib, ishga tushiradi. Aslida bularning barchasi Python yordamida ancha oson bajariladi, shuning uchun siz dasturni komplyatsiya qilinishini, to'g'ri kutubxona bog'lanib, yuklanganmi va boshqa narsalar haqida tashvishlanmasangiz ham bo'ladi. Bundan tashqari bu sizning Python dasturingizni ancha portativ \(ixcham\) qiladi, ya'ni siz dastuni shunchaki ko'chirib boshqa kompyuterda ishlatishingiz mumkin.

### Ob'yektga yo'naltirilgan

Python prosenduraga yo'naltirilgan dasturlashni ham ob'yektga yo'naltirilgan dasturlashni ham qo'llab-quvvatlaydi. Proseduraga yo'naltirilgan dasturlash tillarida dastur qayta foydalanish mumkin boʻlgan dastur boʻlaklari boʻlgan prosedura va funksiyalardan tashkil topadi.  Obʻyektga yoʻnaltirilgan dasturlash tillarida dasturlar maʻlumotlar va funksiyonallikni oʻzida mujassamlashtirgan obʻyektlardan tashkil topadi. Python tili OOPni qoʻllashda C++ yoki Java kabi katta tillar bilan solishtirganda juda qudratli va soddalashtirilgan uslubga ega.

### Kengayuvchan

Agar sizning dasturingizga juda tez ishga tushuvchi qism kerak bo'lsa yoki dastur algoritmning biror qismini birov ochishini xohlamasangiz dasturning o'sha qismini C yoki C++ dasturlash tilida yozib, so'ng uni Python dasturingizda foydalanishingiz mumkin.

### O'rnatiladigan

Siz dastur foydalanuvchilariga skiptlash imkoniyatini berish uchun Pythonni  C/C++ dastur ichiga o'rnatishingiz mumkin.

### Kengaytirilgan kutubxonalar

Pythonning Standard kutubxonasi chindan ham ulkan.U sizga  doimiy ifodalar, dukumentatsiya generatorlari, qismiy testlash, oqimlar, ma'lumotlar bazalari, web brauzerlar, CGI, FTP, email, XML, XML-RPC, HTML, WAV fayllar, shifrlash, GUI \(graphical user interfaces - ya'ni foydalanuvchining grafik interfeysi\) va tizimga bog'liq boshqa narsalar ishtirokida turli xil ishlarni qilishga yordam beradi.  Unutmangki, bularning barchasi python o'rnatilgan joyga allaqachon o'rnatilgan bo'ladi.  Bu Pythonning _"Batteykalari qo'shib beriladi"_ nomli falsafasidir.

Standart kutubxonadan tashqari, [Python Paket indeksidan](http://pypi.python.org/pypi) topishingiz mumkin bo'lgan boshqa yuqori sifatli kutubxonalar ham mavjud.

### Xulosa

Python, albatta, qiziqarli va kuchli tildir. Unda Python tilida dastularni ham qiziqarli ham oson yaratish uchun kerak bo'lgan bajarish va xususiyatlarning ajoyib kompinatsiyasiga ega.

## Python 3 versiyasi 2 versiyaga qarshi

Agar sizga "Python 3 versiyasi" va "Python 2 versiyasi" o'rtasidagi  farqlar qiziq bo'lmasa, bu bo'limni o'tkazib yuborishingiz mumkin. Lekin iltimos, qaysi versiyadan foydalanayotganingizda xabardor bo'ling. Bu kitob Pythonning 3 versiyasi uchun yozilgan.

2 va Python 3 o'rtasidagi farqlarni batafsil bilish uchun quyidagilarni qarab chiqing:

* [The future of Python 2](http://lwn.net/Articles/547191/)
* [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
* [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
* [Supporting Python 3: An in-depth guide](http://python3porting.com)

## Dasturchilar nima deyishadi

Siz bu yerda ESR kabi buyuk hakkerlar Pyhon haqidan nima deganligi haqida o'qishingiz mumkin:

* Erik S. Raymond \(_Eric S. Raymond\)_  "The Cathedral and the Bazaar"\("Ibodatxona va bozor"\) ning muallifi va _Ochiq manba_ tushunchasini yaratgan inson. [Python uning sevimli dasturlash tiliga aylanganini](http://www.python.org/about/success/esr/) aytadi u.   Bu maqola men uchun Pythonga kirishda haqiqiy ilhom manbai bo'ldi. 
* Bryus Ekkel \(_Bruce Eckel\) \_mashxur_ \_ 'Thinking in Java' \("Javada fikrlash"\) va 'Thinking in C++' \("C++ da fikrlash"\) kitoblarining muallifi. Hech bir tili meni Python'chalik samarador qilmagan deydi u.  U yana ta'kidlaydiki, ehtimol faqat Python tili dasturchi uchun narsalarni oson bajarishga mo'ljallangan tildir. Batafsil ma'lumotlar olish uchun [to'liq intervyu](http://www.artima.com/intv/aboutme.html)ni o'qib chiqing.  
* _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google \(thanks to Guido van Rossum for pointing that out\). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers.



