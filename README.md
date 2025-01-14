# Kutegram (aka QTgram)
## Как построить
### Symbian^1 (и Symbian^3)
* Копируй этот репозиторий вместе с подмодулями.
```
git clone --recursive https://github.com/kutegram/client.git
cd client
```
* Go to `library` folder, rename `apivalues.default.h` file to `apivalues.h`, and fill needed fields.
* Запусти скрипт сборки.
```
buildSymbian.bat
```
