# otus_startsystem
<h1>Домашняя работа</h1>
Для выполнения ДЗ использовался Centos 7<br>
<h3>Часть 1: попасть в систему без пароля</h3>
Способ 1: init=/bin/sh<br>
Прописываем в конце строки linux16: init=/bin/sh и нажимаем ctrl+x <br>
<p align="left">
 <img width="1000px" src="image/startsystem.png" alt="qr"/>
</p>
Система загрузилась<br>
<p align="left">
 <img width="1000px" src="image/startsystem2.png" alt="qr"/>
</p>
Способ 2: rd.break<br>
Прописываем в конце строки linux16: rd.break и нажимаем ctrl+x <br>
<p align="left">
 <img width="1000px" src="image/startsystem3.png" alt="qr"/>
</p>
Система загружена <br>
<p align="left">
 <img width="1000px" src="image/startsystem4.png" alt="qr"/>
</p>
Способ 3: init=/sysroot/bin/sh<br>
<p align="left">
 <img width="1000px" src="image/startsystem5.png" alt="qr"/>
</p>
Система загружена <br>
<p align="left">
 <img width="1000px" src="image/startsystem6.png" alt="qr"/>
</p>
<h3>Часть 2: переименование volume group в lvm</h3><br>
<a href=typescript>Лог действий</a><br>
<h3>Часть 3: добавление модуля в initrd</h3><br>
<a href=initrd>Лог действий</a><br>
<p align="left">
 <img width="1000px" src="image/startsystem7.png" alt="qr"/>
</p>
