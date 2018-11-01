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

### Portable

Oʻzining ochiq kod xususiyati sababli, Python juda koʻp platformalardan joy oldi. Sizning Pythonʻda All your Python programs can work on any of these platforms without requiring any changes at all if you are careful enough to avoid any system-dependent features.

You can use Python on GNU/Linux, Windows, FreeBSD, Macintosh, Solaris, OS/2, Amiga, AROS, AS/400, BeOS, OS/390, z/OS, Palm OS, QNX, VMS, Psion, Acorn RISC OS, VxWorks, PlayStation, Sharp Zaurus, Windows CE and PocketPC!

You can even use a platform like [Kivy](http://kivy.org) to create games for your computer _and_ for iPhone, iPad, and Android.

### Interpreted

This requires a bit of explanation.

A program written in a compiled language like C or C++ is converted from the source language i.e. C or C++ into a language that is spoken by your computer \(binary code i.e. 0s and 1s\) using a compiler with various flags and options. When you run the program, the linker/loader software copies the program from hard disk to memory and starts running it.

Python, on the other hand, does not need compilation to binary. You just _run_ the program directly from the source code. Internally, Python converts the source code into an intermediate form called bytecodes and then translates this into the native language of your computer and then runs it. All this, actually, makes using Python much easier since you don't have to worry about compiling the program, making sure that the proper libraries are linked and loaded, etc. This also makes your Python programs much more portable, since you can just copy your Python program onto another computer and it just works!

### Object Oriented

Python supports procedure-oriented programming as well as object-oriented programming. In _procedure-oriented_ languages, the program is built around procedures or functions which are nothing but reusable pieces of programs. In _object-oriented_ languages, the program is built around objects which combine data and functionality. Python has a very powerful but simplistic way of doing OOP, especially when compared to big languages like C++ or Java.

### Extensible

If you need a critical piece of code to run very fast or want to have some piece of algorithm not to be open, you can code that part of your program in C or C++ and then use it from your Python program.

### Embeddable

You can embed Python within your C/C++ programs to give _scripting_ capabilities for your program's users.

### Extensive Libraries

The Python Standard Library is huge indeed. It can help you do various things involving regular expressions,documentation generation, unit testing, threading, databases, web browsers, CGI, FTP, email, XML, XML-RPC, HTML, WAV files, cryptography, GUI \(graphical user interfaces\), and other system-dependent stuff. Remember, all this is always available wherever Python is installed. This is called the _Batteries Included_ philosophy of Python.

Besides the standard library, there are various other high-quality libraries which you can find at the [Python Package Index](http://pypi.python.org/pypi).

### Summary

Python is indeed an exciting and powerful language. It has the right combination of performance and features that make writing programs in Python both fun and easy.

## Python 3 versus 2

You can ignore this section if you're not interested in the difference between "Python version 2" and "Python version 3". But please do be aware of which version you are using. This book is written for Python version 3.

Remember that once you have properly understood and learn to use one version, you can easily learn the differences and use the other one. The hard part is learning programming and understanding the basics of Python language itself. That is our goal in this book, and once you have achieved that goal, you can easily use Python 2 or Python 3 depending on your situation.

For details on differences between Python 2 and Python 3, see:

* [The future of Python 2](http://lwn.net/Articles/547191/)
* [Porting Python 2 Code to Python 3](https://docs.python.org/3/howto/pyporting.html)
* [Writing code that runs under both Python2 and 3](https://wiki.python.org/moin/PortingToPy3k/BilingualQuickRef)
* [Supporting Python 3: An in-depth guide](http://python3porting.com)

## What Programmers Say

You may find it interesting to read what great hackers like ESR have to say about Python:

* _Eric S. Raymond_ is the author of "The Cathedral and the Bazaar" and is also the person who coined the term _Open Source_. He says that [Python has become his favorite programming language](http://www.python.org/about/success/esr/). This article was the real inspiration for my first brush with Python.
* _Bruce Eckel_ is the author of the famous 'Thinking in Java' and 'Thinking in C++' books. He says that no language has made him more productive than Python. He says that Python is perhaps the only language that focuses on making things easier for the programmer. Read the [complete interview](http://www.artima.com/intv/aboutme.html) for more details.
* _Peter Norvig_ is a well-known Lisp author and Director of Search Quality at Google \(thanks to Guido van Rossum for pointing that out\). He says that [writing Python is like writing in pseudocode](https://news.ycombinator.com/item?id=1803815). He says that Python has always been an integral part of Google. You can actually verify this statement by looking at the [Google Jobs](http://www.google.com/jobs/index.html) page which lists Python knowledge as a requirement for software engineers.



