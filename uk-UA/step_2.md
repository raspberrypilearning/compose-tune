## Зіграй свої перші ноти

Sonic Pi дозволяє тобі програмувати музику. Почнімо із гри простих музичних нот.

[[[sonic-pi-install]]]

+ Запусти програму Sonic Pi. Керівник гуртка допоможе тобі її знайти. Якщо ти використовуєш Raspberry Pi, тоді вона знаходитья в розділі меню Програмування.
    
    ![знімок екрана](images/tune-GUI.png)

+ Бачиш місце, де написано "#Welcome to Sonic Pi"? Нижче нього введи:
    
    ![знімок екрана](images/tune-play.png)

+ Натисни "Run". Ти почув (-ла) музичну ноту? Якщо ні, то перевір, чи не вимкнуто звук на твоєму комп’ютері, а також що гучність достатня. Якщо ж звук занадто гучний, тоді зменши його.
    
    Якщо ти використовуєш Raspberry Pi, тоді переконайся, що або ти використовуєш HDMI монітор із динаміками, або колонки чи навушники, підключені до аудіо виходу.
    
    Також ти можеш змінювати гучність звуку в розділі "Prefs".

+ Тепер додай іще один рядок під першим:
    
    ![знімок екрана](images/tune-play2.png)

+ Натисни "Run". Чи почув (-ла) ти те, що очікував (-ла)? В Sonic Pi `play` означає почати відтворення, тому він починає грати першу ноту, а потім зразу другу, тому ти чуєш обидві ноти одночасно.

+ Щоб друга нота зазвучала після першої, додай між ними `sleep 1`, щоб твій код виглядав ось так:
    
    ![знімок екрана](images/tune-sleep.png)

+ Тепер запусти свій код, він має звучати як дверний дзвінок.
    
    Вслухайся, ти маєш почути вищу ноту, а за нею — нижчу. Вищі ноти мають більші коди.
    
    <div id="audio-preview" class="pdf-hidden">
    <audio controls preload> 
      <source src="resources/doorbell-1.mp3" type="audio/mpeg"> 
      Твій браузер не підтримує елемент <code>audio</code>.
    </audio>
    </div> 
+ Збережи свою програму, натиснувши "Save", і назви свій файл "дзвінок.txt".
    
    ![знімок екрана](images/tune-save.png)
    
    Якщо ти не знаєш, де зберегти свій файл, порадься із керівником гуртка.
    
    Ти можеш завантажувати файли назад в Sonic Pi, натиснувши на "Load".