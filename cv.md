# Marina Golovanova

*contacts:*
- +7-968-515-30-43
- gma18@list.ru

### Summary
---

>I am a beginner IT developer. I am a hardworking and ambitious individual with a great passion for the both front-end and back-end development. I have excellent interpersonal skills, enabling me to interact with a team. I want to grow and further improve my IT skills. I am seeing a position in the industry in which I can put into practice my knowledge and experience, ultimately benefiting the operations of the organisation that I work for.


## Skills
---

- **Programming languages:** JavaScript, Python, R
- **Markup language:** HTML, HTML5, CSS, Markdown
- **Framework:** Flask
- **Version Management:** Git, Github, GitKraken
- **OS:** Ubuntu Linux

## Code
---
```python
from time import sleep

def count_down(time):
  '''Обратный отсчет секунд'''
  for sec in range(time, 0, -1):
    print(sec, end='\r')
    sleep(1)


class TrafficLight():
  __color = ['red', 'yellow', 'green']

  def running(self):
    while True:
      i = 0
      while(i < 3):
        print(f'TrafficLight is {TrafficLight.__color[i]}')
        if i == 0:
          count_down(7)
        elif i == 1:
          count_down(5)
        elif i == 2:
          count_down(7)
        i += 1

trafficLight = TrafficLight()
print(trafficLight.running())
```

## Experience:
---

**10/2020 - 11/2020**
- as part of the [Programming Basics course](https://geekbrains.ru/courses/754), I made a website that contains personal information, two games and a password generator (which I created earlier) through HTML, PHP and JavaScript (the site was hosted on a temporary platform, so there is no way to attach a link)

## Education
---

**2021** 
- [Linux](https://geekbrains.ru/lessons/50390)

**2020** 
- [Programming Basics course](https://geekbrains.ru/courses/754)
- [Fundamentals of Python](https://geekbrains.ru/lessons/95218)

**2020** 
- HSE University: *faculty of social sciences, sociology*


**2018** 
- English First

## Language skills
---

| Language | Level |
| -------- | ------------ |
| Russian | *native* |
| English | *intermediate* |


