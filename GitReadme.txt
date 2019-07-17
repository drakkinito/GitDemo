11111
cd - перехід по папкам
ls - показує файли в папці
ls -a - показує скриті файли в папці
 
git init - створює локальний храніліще(репозеторій) .git
git status - показує які зміни відбулися і показує які файли ми можемо добавити в коміт
git add Name - добавляє файл по імені 
git add . - добавляє всі змінені файли
git commit -m "Initial commit" - зберігаємо наші файли в репозиторій(має імя чи опис)

git log - перегляд всіх комітів 
git branch - показує гілки які існують
git branch Name - створення нової гілки(Name назва)
git checkout Name - перехід на іншу гілку
git checkout -b Name - перехід і створення на іншу гілку
git branch -d Name (git branch --delete Name) - видаляє гілку по назві
git merge Name - зєднання гілок

git remote add origin https://github.com/drakkinito/GitDemo.git - звязуємо наш локальний репозеторій з удальнним
git push -u origin master - преносить всі зміни з локального репозиторія в удальонний(на github); push - це відправляємо дані; -u синхронизуємо дані з віткою master
22222
