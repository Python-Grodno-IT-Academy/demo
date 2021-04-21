<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#pip">PIP</a>
      <ul>
        <li><a href="#requirements">requirements</a></li>
      </ul>
    </li>
    <li><a href="#venv">Virtual Environment</a></li>
    <li><a href="#pipenv">Pip Virtual Environment</a></li>
  </ol>
</details>

<!-- PIP -->
## pip

https://www.youtube.com/watch?v=BXaBQ0PcNTk

Видео работает со старой верисей питон но обьясняет суть `pip`

Управляет питон пакетами на компьютере или сервере.  Похож на `npm` для NodeJS.
Доступ к `pip` производиться исключительно через коммандную линию!
Мы уже пользовались `pip` для установки `pytest`.
Комманды `pip`:
```sh
pip -V
pip --version
```
Показывает версию `pip`
```sh
pip list
```
Показывает все установленные пакеты и имеет опции:
- `-o,--outdated` Показывает устаревшие пакеты
- `-u,--uptodate` Показывает не устаревшие пакеты
- `-e,--editable` Показывает пакеты которые можно изменить
- `-l,--local` Показывает `venv` пакеты когда мы находимся в исткуственной среде
```sh
pip show PKG
```
Показывает информацию пакета
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
```sh
pip 
```
### requirements
# venv
Позволяет иметь несколько виртуальных сред на одном компьютере. 
К примеру у вас один проект в python 2.7 & Django 1.5 и другой проект в python 3.9 & Django 2.1.

# pipenv
