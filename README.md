# b0mb3r 💣
SMS бомбер с приятным веб-интерфейсом. Создан crinny, доработан (дорабатывается) мной :)

> Я не несу ответственности за ваши действия. Скачивая программное обеспечение из этого репозитория, вы соглашаетесь с [лицензией](https://github.com/MazZz3R/old_b0mb3r/blob/master/LICENSE).
# Установка
## На Linux
1. Откройте терминал и установите Python и git с помощью вашего пакетного менеджера:
    Arch/manjaro/antergos:
    ```bash
    pacman -S git python --needed
    ```
    Ubuntu/Debian/Deepin/any_apt_based:
    ```bash
     apt install git python
    ```
     Fedora:
    ```bash
     yum install git python
    ```
2. Клонируйте репозиторий при помощи git и перейдите в папку:
    ```bash
    git clone https://github.com/MazZz3R/old_b0mb3r
    cd old_b0mb3r
    ```
3. Разрешите зависимости:
    ```bash
    pip install -r requirements.txt
    ```
4. Запустите скрипт:
    ```bash
    python main.py
    ```
5. Если в вашем браузере не открылся веб-интерфейс, перейдите по ссылке в консоли.
    >номер вводить без кода страны (т.к. вы указываете его немного левее)
    
## На Windows
1. Установите Python версии не ниже 3.6, скачав установщик с [официального сайта](https://www.python.org/downloads/).
2. Установите git для Windows, скачав его [отсюда](https://git-scm.com/download/win).
3. Откройте командную строку и клонируйте репозиторий при помощи git и перейдите в папку:
    ```bash
    git clone https://github.com/MazZz3R/old_b0mb3r
    cd old_b0mb3r
    ```
4. Установите все необходимые библиотеки и запустите скрипт:
    ```bash
    pip install -r requirements.txt
    python main.py
    ```
5. Если в вашем браузере не открылся веб-интерфейс, перейдите по ссылке в консоли.
    >номер вводить без кода страны (т.к. вы указываете его немного левее)

## На Android
1. Установите [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=ru)
2. Введите следующие команды поочерёдно для установки необходимых компонентов:
    ```bash
    pkg install python
    pkg install git
    ```
3. Выполните действия, начиная с пункта 3 из инструкции по установке на Windows.

# Обновление
## На Windows
1. Введите следующую команду для удаления предыдущей версии:
   ```bash
   rmdir /S /Q b0mb3r
   ```
2. Выполните действия, начиная с пункта 3 из инструкции по установке на Windows.
## На Linux/Android
1. Выполните эту команду:
   ```bash
   cd old_b0mb3r
   git pull
   ```
