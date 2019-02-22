# CleverSwarm
Програмное обеспечение для запуска шоу дронов под управлением Raspberry Pi с пакетом COEX Clever.
### Пакет включает в себя:
* Аддон для трехмерного редактора Blender, позволяющий экспортировать в формат CSV созданную анимацию движения для одного или нескольких дронов
* Набор ПО для дрона, включащее в себя библиотеку для автономного полёта, модуль для воспроизведения анимаций и клиентское приложение для удаленного синхронизированного управления
* Серверное приложение для удаленного синхронизированного управления дронами и удобной передачи анимации

## Установка
Скачайте или склонируйте этот репозиторий на компьютер и дроны:
```bash
git clone --recurse-submodules https://github.com/artem30801/CleverSwarm.git
```
Обновите включенные в пакет подмодули:
```bash
cd CleverSwarm
git submodule foreach git pull origin master
```
Для дальнейших интрукций перейдите на Wiki
