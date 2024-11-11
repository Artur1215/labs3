# Лабараторная работа 3
__Задача:__ _В рамках ЛР 1 необходимо было сверстать страницу сборника средствами LaTeX.

__Вариант 105-107:__ _Создать скомпилируемый файл из 3 страниц
# Выполнение задачи 
## Пример:

![Снимок экрана 2024-11-11 225710](https://github.com/user-attachments/assets/f8a3555b-5948-47ec-9d8e-e052260ffb5b)
## Результат:

![Снимок экрана 2024-11-11 225038](https://github.com/user-attachments/assets/c9bc3655-03ea-449a-bec3-4684fa9781fd)

Выполнять ЛР 1 можно на сайте overleaf. В результате выполнения лабораторной необходимо добавить скомпилированный pdf-файл в выданную вам ветку. ссылка на мой проект:https://www.overleaf.com/project/66f5bfce95dde42d267dc656

1.git init — Создать локальный репозиторий в текущей папке:

![Снимок экрана 2024-11-12 001505](https://github.com/user-attachments/assets/d395f3d2-8ef7-4d40-a544-6091e010c725)

2.git status — Посмотреть статус текущего репозитория:

![Снимок экрана 2024-11-12 001640](https://github.com/user-attachments/assets/fa3b7942-718c-4bfc-9238-287166d5633f)

## 3.Ветка (branch) — это указатель на коммит. Ветки позволяют работать над разными версиями проекта параллельно.Основная ветка называется main или же master.

4.git add <имя_файла> — Добавить файл в контекст, который будет коммититься:

![Снимок экрана 2024-11-12 002640](https://github.com/user-attachments/assets/dd12f8cf-f1f3-4dc3-9545-f3a5f8ccd8c8)

5.git commit -m "Комментарий к коммиту" — Создать коммит на основе текущего контекста и указать для него комментарий:

![Снимок экрана 2024-11-12 003223](https://github.com/user-attachments/assets/209708fd-3bde-418f-86b3-7c7ab38b080f)

6.git commit -a -m "Комментарий к коммиту" — Создать коммит, включающий изменения всех наблюдаемых файлов и указать для него комментарий

7.git log—Посмотреть протокол (лог) коммитов

8.git config --list—Посмотреть информацию о текущих настройках:

9.git reset <имя_файла>—Убрать файл из контекста

10.git diff <имя_файла>—Посмотреть изменения в файле по сравнению с последним коммитом

11.git checkout -- <имя_файла>—Убрать изменения относительно последнего коммита из файла

12.git add . —Добавить в контекст коммита все измененные и созданные файлы:

![Снимок экрана 2024-11-12 004538](https://github.com/user-attachments/assets/6fa2a798-cfe6-47a3-a593-c73b5ba4bff9)


13.git config --global <параметр> <значение> — Изменить глобальные/локальные настройки: git config --local <параметр> <значение>

14.git config --global user.name "Новое имя"—Переписать имя ползователя

15.git branch —Просмотреть существующие ветки

16.git branch <имя_ветки> —Создать новую ветку

17.git checkout <имя_ветки>—Переключиться на другую ветку:

18.git checkout -b <имя_ветки>— Создать новую ветку и сразу же переключиться на неё.

19.git branch -d <имя_ветки>— Удалить ветку. Удалить ветку, даже если она не примержена; git branch -D <имя_ветки>— Удалить ветку, даже если она не примержена.

20.git merge <имя_ветки>— Примержить изменения из указанной ветки в текущую.

21.В каком случае могут появиться конфликты? Сделать конфликт: Конфликты могут появиться, если изменения в разных ветках затрагивают одни и те же строки в файлах. Для создания конфликта можно изменить одну и ту же строку в одном файле в двух разных ветках и попытаться их слить.

22.git status — Посмотреть в каких файлах конфликты.

![Снимок экрана 2024-11-12 004306](https://github.com/user-attachments/assets/c31f3c18-88b9-429c-a80f-420b2219cfec)


23.git add <имя_файла>(git commit)— Устранить конфликты.

24.git checkout <хеш_коммита> — Переключиться на указанный коммит.

25.git rebase <ветка>— Сделать ребазирование текущей ветки.

26.git rebase --continue— Устранить конфликты во время ребазирования.

27.git rebase --abort— Отменить ребазирование во время конфликтов.

28.git rebase --skip— Пропустить текущий конфликтный коммит и перейти к следующему.

29.git push origin <имя_ветки>— Отправить изменения из локального репозитория для указанной ветки в удалённый репозиторий.

30.git fetch— Забрать изменения из репозитория, для которого были созданы удалённые ветки по умолчанию.

![Снимок экрана 2024-11-12 004703](https://github.com/user-attachments/assets/ccc29e88-2f51-403c-bc70-f48677215ab7)


31.git pull origin main— Забрать изменения удалённой ветки из репозитория по умолчанию, основной ветки.

32.git clone <URL_репозитория>— Создание копии репозитория.

33.git commit --amend -m "Новое сообщение коммита"— Переименовать последний коммит.

34.git rebase -i <хеш_коммита>— Переименовать не последний коммит.

35.git stash— Скрыть изменения по сравнению с последним коммитом.

