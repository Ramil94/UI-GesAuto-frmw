# UI-GesAuto-frmw
Репозиторий прошивок для GesAuto

# О прошивке
Прошивка была собрана специально для компании USSAT Inzener что-бы обеспечить стабильную работы сети для устройств GESPASA как внутри сети (роутер подключается по wifi к сети GesAuto) так и удаленно по 3G (подключается на сервер компании openconnect)!
Стоковая прошивка была выпилена так ка занимала много дискового пространства и содержала в себе много лишнего
За основу прошивки был взят снэпшот openwrt версии 19
Прошивка собирается для каждого GESPASA устройства отдельно, и имеет индивидуальные настройки которые не збрасываются при жестком сбрасывании устройства !
Ни в коем случае не ставить прошивку для домашнего пользования, так как в ней по умолчанию идет корпаративный пароль доступ к которому имеют только специалисты технического отдела компании !

Версия прошивки именовывались рандомно (от балды) сейчас все переношу на Github</br>
После версии 1.6.260722 начнется логическое наименование версий

пример:</br></br>
</br>1.6.0001_260722_1
</br>1.x.xxxx_xxxxxx_x - первая точка - глобальное изменение: возможно смена протокола подключение vpn например с openconnect на softether, или изменение логики в подключение, например отказ от wifi и полный переход на 3G или наоборот !</br>
</br>x.6.xxxx_xxxxxx_x - вторая точка - изменения связанные с важными изменениями, критическими ошибками</br>
</br>x.x.0001_xxxxxx_x - третья точка - мелкие изменения, добавление мелких фич, редактирование интерфейса, и т.п.</br>
</br>x.x.xxxx_260722_x - третья точка 1-ое нижнее подчеркивание - дата создание прошивки</br>
</br>x.x.xxxx_xxxxxx_1 - третья точка 2-ое нижнее подчеркивание - в какой половине дня была создана прошивка</br>

