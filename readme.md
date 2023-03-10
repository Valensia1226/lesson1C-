# **Git instruction**

## **Команды git**
* *git init* - позволяет из папки сделать репозиторий (систему хранения версий в данной папке)
* *git add* - позволяет добавить файл для отслеживания

    * *git add file.txt* - добавит файл file с расширением txt
    * *git add .*- добавит все файлы из папки
    * *git add TAB* - при нажатии клавиши TAB предложит подряд файлы из папки

* *git commit* - позволяет сохранить текущее состояние файла (при этом файл вначале должен быть фактически сохранен ctrl+S)

    * *git commit -m "Текст комментария"* - позволяет сохранить текущее состояние файла с добавлением комментария о сохранении

* *git log* - позволяет посмотреть все сохраненные версии с комментариями к ним (передвижение между версиями с помощью стрелочек вверх/вниз на клавиатуре)

* *git diff* - позволяет посмотреть изменения по сравнению с последней сохраненной версией

* *git checkout ___* - позволяет перейти к определенному сохранению (необходимы первые 6 элементов номера коммита, их можно получить через git log или git graph)

* *git branch first* - позволяет создать новую ветвь с названием first, при этом содержимое файла будет идентично файлу в текущей ветви, однако при переходе в новую ветвь и внесении изменений, эти изменения не отобразятся в материнской ветви. Чтобы это произошло, необходимо провести слияние.

* *git branch* - показывает все существующие на данный момент ветви

* *git checkout first* - позволяет перейти к ветви first

* *git branch -d first* - позволяет удалить ветку first
 
* *git merge first* - позволяет перенести информацию из ветки first в текующую ветку

* *git log --graph* - показывает список коммитов с графическим отображением ветвей в терминале
