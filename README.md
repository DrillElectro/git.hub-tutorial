# Большой заголовок для репозитория
репозиторий для изучения Git и GitHub на канале Гоша Дударь (**YouTube**)

команды <br>
git 

init

add .

status

commit -m "*text*"

log

log --oneline               список коммитов

checkout *id commit*        перейти на версию файлов на момент этого коммита

checkout master

revert *id commit*              из редактора выйти :wq  - отмена коммита, файлы меняются

reset *id commit*               удалить коммиты до *id commit* файлы не меняются

reset *id commit* hard          удалить коммиты до *id commit*, файлы меняются

branch *название ветки*         создание ветки

checkout *название ветки*       перейти в ветку

branch -a                       информация веток

checkout -b *название ветки*    создание и переход в ветку

merge *название ветки*          объединение веток


remote                          проверка соединения с github

push -u origin *название ветки* обновление репозитория 

pull                            загрузка файлов с github


