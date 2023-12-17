# otus_startsystem
<h1>Домашняя работа</h1>
<h3>Часть 1: попасть в систему без пароля</h3>
Способ 1: init=/bin/sh<br>
Прописываем в конце строки linux16: init=/bin/sh и нажимаем ctrl+x 
![Image alt]![startsystem](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/61536be5-d5a3-48ca-aceb-9b1f6a033601)
Система загрузилась
![startsystem2](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/d3ef7d0b-0a97-4880-8d1e-888ccb457a4b)
Способ 2: rd.break<br>
Прописываем в конце строки linux16: rd.break и нажимаем ctrl+x 
![startsystem3](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/a98b7346-70c2-471d-9178-01e066a8dfad)
Система загружена 
![startsystem4](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/144be26b-f68b-4ec8-9685-b68194b21afb)
Способ 3: init=/sysroot/bin/sh<br>
![startsystem5](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/657c407f-36fa-4d17-80ff-53502cb4cc70)
Система загружена 
![startsystem6](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/64e290a4-eea8-441d-88e0-3df3ded3b260)
<h3>Часть 2: переименование volume group в lvm</h3>
<a>Лог действий</a>
<h3>Часть 3: добавление модуля в initrd</h3>
<a>Лог действий</a>
![startsystem7](https://github.com/ViktorKonovalenko/otus_startsystem/assets/32430041/b4d5871b-c02b-4373-a88b-49db55bdd7a3)
