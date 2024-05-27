# SI_2024_lab2_226039
SUEJLA AMETI 226039


2. Сликата на CFG e прикачена на овој репо, со име CFGLAB2.2024.png


3.Цикломатската комплексност на дадениот код е 10. Ја добив со формулата E-N+2, и со колку региони има.


5.Тест случај 1: item.getPrice() > 300, item.getDiscount() > 0, item.getBarcode().charAt(0) == '0', ги исполнува сите услови се евалуираат сите.

Тест случај 2: item.getPrice() < 300, item.getDiscount() < 0, item.getBarcode().charAt(0) == '0', не, првиот услов не е исполнет не се евалуираат другите два.

Тест случај 3: item.getPrice() > 300, item.getDiscount() > 0, item.getBarcode().charAt(0) == '0', не, вториот услов не е исполнет не се евалуира третиот.

Тест случај 4: item.getPrice() > 300, item.getDiscount() < 0, item.getBarcode().charAt(0) != '0', првиот услов е исполнет се евалуираат другите но третиот услов не е исполнет.
