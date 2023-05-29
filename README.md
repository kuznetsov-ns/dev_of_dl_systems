# dev_of_dl_systems

Основано на **[pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)**<br>

## Требования для запуска проекта:
* git
* docker
## Запуск проекта:
1. Скачиваем репозиторий:
```
git clone https://github.com/kuznetsov-ns/dev_of_dl_systems.git
```
2. Переходим в папку репозитория:
```
cd dev_of_dl_systems
```
3. Собираем:
```
docker build -t test .
```
4. Запускаем:
```
docker run test
```
## Примечание
Если хотим сохранить получившиеся изображения на хосте, то при запуске используем:
```
docker run -v <your_path>:/results/ test
```
где \<your_path> - полный путь к папке на хосте в которую хотим сохранить.

