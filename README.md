# ADB

 1. Отобразить подключённый девайс в консоли 
 ```adb devices```
 2. Вывести адрес приложения todolist в системе Android ```adb shell pm list packages -f todolist```
 3. Установить .apk файл приложениия todolist на телефон с компьютера через  ADB ```adb install C:\Users\User\Desktop\ADB\app-debug.apk```
 4. Сделать скриншот запущенного приложения todolist и сразу скопировать на компьютер в одной команде ```adb shell screencap /storage/emulated/0/DCIM/gr_28.png && adb pull /storage/emulated/0/DCIM/gr_28.png  C:\Users\User\Desktop\ADB\gr_28.png```
 5. Вывести в консоль логи приложения todolist
 6. Скопировать логи приложения todolist на компьютер.
 7. Удалить приложение todolist с телефона через ADB
