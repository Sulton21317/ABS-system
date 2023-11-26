# AI-Assisted SmartBrake: Automatic Braking System using YOLOv5 and OpenCV

AI-Assisted SmartBrake innovatsion ABS boʻlib, obʼyektlarni ilgʻor aniqlash va
toʻqnashuvning oldini olish imkoniyatlarini taʼminlash uchun YOLOv5 va 
OpenCV quvvatidan foydalanadi. Ushbu zamonaviy tizim robotlar uchun maxsus ishlab chiqilgan va 
hatto real vaqt rejimida yuzaga kelishi mumkin bo'lgan to'siqlar, piyodalar va transport 
vositalarini aniqlash orqali yo'l harakati xavfsizligini oshiradi va baxtsiz hodisalarning oldini oladi.

<img src="result.gif" width="1000"/> 

<br/>
**YOLOv5 ob'ektni aniqlash:** ob'ektni mustahkam va aniq aniqlash uchun eng zamonaviy YOLOv5 modelidan foydalanadi. Haqiqiy vaqtda to'qnashuvning oldini olish: potentsial to'qnashuvlar aniqlanganda avtomobilning tormoz tizimini darhol faollashtiradi. 
<br/>
**Yuqori unumdor OpenCV (High-Performance OpenCV):** tasvirni samarali qayta ishlash va tahlil qilish uchun OpenCVdan foydalanadi. Moslashtirilgan chegaralar: Shaxsiylashtirilgan xavfsizlik imtiyozlari uchun sozlanishi sezgirlik darajalarini taklif qiladi. Uzluksiz integratsiya: avtonom transport vositalari va robot ilovalariga osongina birlashtiriladi.


### Bu qanday ishlaydi?
- YOLOv5 modeli: Tizim avtomobil yoʻlidagi obyektlarni aniqlash uchun chuqur oʻrganishga asoslangan obʼyektlarni aniqlash modeli boʻlgan YOLOv5dan foydalanadi.
-	Haqiqiy vaqtda aniqlash: Kameralardan jonli video tasmasidan foydalanib, tizim o'z vaqtida qaror qabul qilish uchun real vaqtda ob'ektni aniqlashni amalga oshiradi.
-	To'qnashuvning oldini olish: mumkin bo'lgan to'siqlarni aniqlagandan so'ng, SmartBrake to'qnashuvlarning oldini olish uchun avtomatik ravishda tormozlarni ishga tushiradi.
-	Sozlanishi mumkin bo'lgan xavfsizlik: Foydalanuvchilar turli xil haydash sharoitlariga mos ravishda tizimning sezgirligini sozlashi mumkin

### Kerak bo’ladigan texnologiya va kutubxonalar.

- Python 3.x
- OpenCV
- PyTorch
- NumPy
- 


### O'rnatish jarayoni:

1. Repositoriyani yuklab olish.
2. Kerakli kutubxonalar o'rnatish

```bash
pip3 install torch opencv numpy
```



### Terminaldan ishga tushurish

```bash
python3 yoloV5_abs.py
```

