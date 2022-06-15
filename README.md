# JSON

 4. Создать внешний репозиторий c названием JSON.

Repositories ==> New ==> Repos Name:JSON ==> Check "Add a README file" --> Press "Create repository"

 5. Клонировать репозиторий JSON на локальный компьютер.

git clone repository htts

 6. Внутри локального JSON создать файл “new.json”.

touch new.json

 7. Добавить файл под гит

git add new.json

 8. Закоммитить файл.

git commit -m "add file new.json"

 9. Отправить файл на внешний GitHub репозиторий.

git push

 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

cat > new.json

{

    "Full Name":"Trushin Nikita Andreevich",
    
    "Age":29,
    
    "Number of pets":0,
    
    "desired salary":"1000$"
    
}

 11. Отправить изменения на внешний репозиторий.

git commit -am "add name age and etc" && git push

 12. Создать файл preferences.json

touch preferences.json

 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

cat >preferences.json

{

	"favorite_movie": " Saw",
  
	"favorite_series": "Ozark",
  
	"favorite_food": "kebab",
  
	"favorite_time_of_the_year": "summer",
  
	"country_you_would_like_to_visit": "Japan"
}

 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
cat > skills.json

{

	"Skill1":"Testing Theory, SDLC, STLC",
  
	"Skill2":"Clien-server",
  
	"Skill3":"HTTP-methods",
  
	"Skill4":"HTTP status-codes",
  
	"Skill5":"HTTP resp, req stracture",
  
	"Skill6":"JSON, XML. Structure",
  
	"Skill7":"API Postman (JS, autotest API).",
  
	"Skill8":"Logs from servers",
  
	"Skill9":"Charles and Fiddler.",
  
	"Skill10":"Dev Tools(Google Chrome, FireFox).",
  
	"Skill11":"VPN.",
  
	"Skill12":"Mobile testing",
  
	"Skill13":"IOS, android guidelines",
  
	"Skill14":"XCode.",
  
	"Skill15":"Android Studio.",
  
	"Skill16":"ADB",
  
	"Skill17":"iOS Android proxy, vpn",
  
	"Skill18":"Mobile trafic sniffing. Charles and Fiddler iOS, Android.",
  
	"Skill19":"terminal Linux",
  
	"Skill20":"bash scripting",
  
	"Skill21":"Remote servers access",
  
	"Skill22":"SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).",
  
	"Skill23":"DB Postgres.",
  
	"Skill24":"Redis",
  
	"Skill25":"Load testing Jmeter.",
  
	"Skill26":"Scrum.",
  
	"Skill27":"Python."
  
}

 15. Отправить сразу 2 файла на внешний репозиторий.
git add .

git commit -m "add preferences.json and skill.json"

git push

#или в 1 строку  git add . && git commit -m "add preferences.json and skill.json" && git push

 16. На веб интерфейсе создать файл bug_report.json.

Add file ==> Create new file ==> Name: bug_report.json

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Press "Commit changes"

 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

 Choose bug_report.json ==> Edit this file

{

  "Environment":"Description of environment",
  
  "ID":"nubmer of bug report" ,
  
  "Summary":"What?Where?Why?",
  
  "Environment":"pc,mobile,browser,build",
  
  "STR":{
  
          "Step1":"step1 description",
          
          "Step2":"step2 description"          
        },
  "Version","Number of  version",
        
  "Severity":"s1,s2,s3,s4,s5",
  
  "Priority":"p1,p2,p3",
  
  "Expected Result":"Description of expected result",
  
  "Actual Result":"Description of actual result",
  
  "Attachments":"link,video,photo"
  
}

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Press "Commit changes"

 20. Синхронизировать внешний и локальный репозиторий JSON

git pull
