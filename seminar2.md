# Git branches

## Branch creating

* *git branch branch_name* -создание ветки *branch_name*
* *git checkout branch_name* - переход на ветку *branch_name*
* *git branch -d branch_name* -удаляет ветку *branch_name*

## Branch merging

* *git merge branch_name* -команда слияния текущей ветки с веткой соединения


После слияния в командной строке первые несколько символов это хэш master ветки, а последние это хэш последнего коммита слитой ветки

## Conflicts

* Конфликты при слиянии возникают, когда изменения произошли на одни и те же области сливаемых веток
