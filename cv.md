## Tatsiana Sauko

***
### Contact information:
* **Location:** Minsk, Belarus
* **Phone:** +375291716142
* **E-mail:** tatsianasavko5@gmail.com
* [LinkedIn](https://www.linkedin.com/in/tatsiana-savko-278104230)

***
### About Me:
I'd describe myself as a goal-oriented and hardworking person with good organizational skills and strategic thinking.

I am said to be realiable, extemely dedicated and able to perform well using my initiative.

I always do my best to achieve professional goals.

***
### Skills:
* Programming language: Python
* Framework: Django
* IDE:  PyCharm
* Front-end technologies: HTML, CSS(basic)
* Code version technologies: Git (GitHub)
* English Proficiency: A2 - > B1

***
### Code example:
```
def solution(args):
    list_res = []
    list_prom = [args[0]]
    for i in range(len(args) - 1):
        if args[i] + 1 == args[i + 1]:
            list_prom.append(args[i + 1])
        else:
            list_res.append(list_prom)
            list_prom = [args[i + 1]]
    list_res.append(list_prom)
    list_output = []
    for i in range(len(list_res)):
        if len(list_res[i]) == 2:
            list_output.append(str(list_res[i][0]))
            list_output.append(str(list_res[i][1]))
        elif len(list_res[i]) == 1:
            list_output.append(str(list_res[i][0]))
        else:
            list_output.append(f'{list_res[i][0]}-{list_res[i][-1]}')
    return ','.join(list_output)
```

***
### Work experience:
**Education Center for Programming and High Tech**/ Trainee Python Developer
* Django online bookstore project: selecting a section, viewing a product, placing an order, applying a discount, registering, authorizing, recovering a password and logging in with Google
* Tech stack: Django, Git, HTML, CSS, PostgreSQL
* [link](https://github.com/TatsianaSauko/DjangoProject) to the GitHub

***
### Education:
#### Courses:
* **Education Center for Programming and High Tech**/ A comprehensive course on developing web applications in Python
  + Studying programm: [link](https://www.it-academy.by/course/python-developer/pt-python-developer/?set_city=84)
  + Electronic certificate: [link](https://disk.yandex.ru/i/_9Cnl6tSXR3CKA)

* **Education Center for Programming and High Tech**/ Fundamentals of web thechnologies
  * Studying programm: [link](https://www.it-academy.by/course/asp-net-developer/proektirovanie-veb-stranits-dlya-programmistov-/)
#### University:
* **Mogilev University A. A. Kuleshova**/ Faculty of Physics and Mathematics, speciality: Teacher of mathematics and computer science

***
### Languages:
* Russian, Belarusian - Native
* English - A2
