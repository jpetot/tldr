# git add

> Додає змінені файли до індексу.
> Більше інформації: <https://git-scm.com/docs/git-add>.

- Додає змінені файли до індексу:

`git add {{шлях/до/файлу}}`

- Додає усі файли (контрольовані та неконтрольовані):

`git add -A`

- Додає тільки ті файли, що вже контрольовані:

`git add -u`

- Додає й ті файли, що ігноруються:

`git add -f`

- Інтерактивно індексує частини файлів:

`git add -p`

- Інтерактивно індексує частини вказаного файлу:

`git add -p {{шлях/до/файлу}}`

- Інтерактивно індексує файл:

`git add -i`