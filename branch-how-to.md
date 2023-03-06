создаем

Переходим в репозиторий кента:
    cd /home/b04-206/Repositories/Vasilev/
Создаем свою ветку (тред /b/):
    b04-206@raspberrypi:~/Repositories/Vasilev $ git branch Golenskikh

перекулючаемся

Переключаемся на свою ветку и пишем пасту про инженерку:
    b04-206@raspberrypi:~/Repositories/Vasilev $ git checkout Golenskikh
    (вывод при успешном перекулючении: Switched to branch 'Golenskikh')

отправляем на сервер

git add branch-how-to.md
git status
git commit -m "branch intstructions"
git push
