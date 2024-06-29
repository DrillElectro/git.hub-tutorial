# Большой заголовок для репозитория
репозиторий для изучения Git и GitHub на канале Гоша Дударь (**YouTube**)
--------------------------------------------------------------------------

## команды консоли для git 

<table>
<tr><td>init</td>                       <td>инициализация git в папке проекта</td></tr>

<tr><td>add .</td>                      <td>добавление файлов в ожидание записи git версиии проекта</td></tr>

<tr><td>status</td>                     <td>файлы в режиме ожидания для записи версии проекта git</td></tr>

<tr><td>commit -m *текст комментария en*</td>         <td>запись версии проекта</td></tr>

<tr><td>log</td>                        <td>список коммитов, расширенный</td></tr>

<tr><td>log --oneline </td>              <td>список коммитов</td></tr>

<tr><td>checkout *id commit*</td>        <td>перейти на версию файлов на момент этого коммита</td></tr>

<tr><td>checkout master</td>             <td>вернуться к самой поздней версии master</td></tr> 

<tr><td>revert *id commit*</td>          <td>из редактора выйти :wq  - отмена коммита, файлы меняются</td></tr>

<tr><td>reset *id commit* </td>              <td>удалить коммиты до *id commit* файлы не меняются</td></tr>

<tr><td>reset *id commit* hard  </td>        <td>удалить коммиты до *id commit*, файлы меняются</td></tr>

<tr><td>branch *название ветки* </td>        <td>создание ветки</td></tr>

<tr><td>checkout *название ветки* </td>      <td>перейти в ветку</td></tr>

<tr><td>branch -a</td>                       <td>информация веток</td></tr>

<tr><td>checkout -b *название ветки* </td>   <td>создание и переход в ветку</td></tr>

<tr><td>merge *название ветки*</td>          <td>объединение веток</td></tr>

<tr><td>push -u origin *название ветки*</td><td>загрузка файлов с github</td></tr>

<tr><td>remote add origin *ссылка на репозиторий*</td><td>подключение к репозиторию github</td></tr>

<tr><td>remote</td>                          <td>проверка соединения с github</td></tr>

<tr><td>push -u origin *название ветки*</td>  <td>обновление (загрука) репозитория</td></tr>

<tr><td>pull</td>                            <td>выгрузка файлов с github</tr>

<tr><td>clone</td>                            <td>копирование репозитория с github</tr>

</table>
