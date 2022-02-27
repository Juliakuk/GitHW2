# GitHW2
## Homework 2 fot Git  
Работу необходимо выполнять в существующем репозитории, в к котором есть созданные закомиченные ранее файлы (не возможно создавать ветки в пустом репозитории, т.к ветка создается для изменения исходного кода).  
#### 1. На локальном репозитории сделать ветки для: (имена веток должны быть без пробелов , можно использовать символ _)
- Postman  
- Jmeter  
- CheckLists  
- Bag Reports  
- SQL  
- Charles  
- Mobile testing  

с использованием команды 'git branch' либо в одну строку, через символы ; или &&
 
> git branch Bag_Reporting

> git branch Mobile_testing

> git branch Jmeter

> git branch CheckLists

> git branch SQL

> git branch Charles

> git branch Postman  

#### 2. Запушить все ветки на внешний репозиторий:  
> git push origin --all (или 'git push -u origin --all')

#### 3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта git checkout Bag_Reports:
> git checkout Bag_Reporting перейти в ветку vim bag.txt
> внести необходимую информацию
> i (insert)
> esc :wq
 
#### 4. Запушить структуру багрепорта на внешний репозиторий:
> git add . (добавить в отслеживание в репозиторий)  
> git commit -m "add bug.txt" (сохранить изменения (закомитить))  
> git push -u origin Bag_Reporting  
> либо можно серию команд в одну строку, через символы ; или &&
  
#### 5. Вмержить ветку Bag Reports в Main:  
> чтобы вмерджить ветку в main, нужно сначала перейти в main ветку  
> git checkout main  
> git merge Bag_Reporting (выполнить слияние веток)  
  
#### 6. Запушить main на внешний репозиторий:
> git push origin main
  
#### 7. В ветке CheckLists набросать структуру чек листа:  
> git checkout CheckLists (перейти в ветку)  
> vim checklist.txt  
> внести необходимую информацию  
> i (insert)  
> esc :wq

#### 8. Запушить структуру на внешний репозиторий:  
> git add . (добавить в отслеживание в репозиторий)  
> git commit -m "add checklist.txt" (сохранить изменения (закомитить))   
> git push -u origin CheckLists  

#### 9. На внешнем репозитории сделать Pull Request ветки CheckLists в main:  
> перейти на веб версию github в нужный репозиторий  
> изменить ветку на Checklists  
> нажать Pull Request  
> в окне сравнения клеток нажать кнопку Create pull request  
> после нажатия кнопки появится окно ввода сообщений Pull Request  
> нажимаем Create pull request  
> в окне сравнения веток нажать кнопку Merge pull request

#### 10. Синхронизировать Внешнюю и Локальную ветки Main:  
> git checkout main  
> git pull origin main



