# Maria Kuzmicheva
## Python Backend Developer && Junior Frontend Developer

## Contacts
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Email**: kuzmichovamary@gmail.com<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;**Telegram**: @maryshca

## About Me
I'm a first year student at MSU. I love programming, maths and learning new stuff. I want to develop cool projects with a good team.

## Skills
### Frontend
[![My Frontend Skills](https://skills.thijs.gg/icons?i=html,js,css,git&theme=light)](https://skills.thijs.gg)
### Backend
[![My Backend Skills](https://skills.thijs.gg/icons?i=py,postgres,docker,linux,stackoverflow,git&theme=dark)](https://skills.thijs.gg)

## Education
- MSU faculty of mathematics
    - First year student
- Yandex School of Backend Development
    - Currently studying
- Yandex Academy Liceum
    - Sertificate with honors

## My Code
Thats some magic. You need to run it to know the output.
```python
code = """2081427472 269515776 0 0 1721336130 605552640 0 0 2017739896 1615875072 1010974780 37895168 0 0 1010974780 37895168 1010974784 1078082560 1145324668 1145324544 1010975298 1111636992 1010975298 1111636992 1077952576 1078099456"""

code = list(map(int, code.split()))


BITS_IN_BYTE = 8
SIZE_OF_INT_IN_BYTES = 4
max_pow = 1 << (SIZE_OF_INT_IN_BYTES * BITS_IN_BYTE - 1)
for k in range(4):
    for i in range(0, len(code), 2):
        number = code[i]
        for j in range(k * BITS_IN_BYTE, (k + 1) * BITS_IN_BYTE):
            print("#" if number & max_pow else " ", end="")
            number = number << 1
        code[i] = number
        print("  ", end="")
    print()

for k in range(4):
    for i in range(1, len(code), 2):
        number = code[i]
        for j in range(k * BITS_IN_BYTE, (k + 1) * BITS_IN_BYTE):
            print("#" if number & max_pow else " ", end="")
            number = number << 1
        code[i] = number
        print("  ", end="")
    print()
```

## My Projects
- [clone of google dino](https://github.com/KuzmichovaMary/runner-game) stack: python
- [my resume](https://kuzmichovamary.github.io/) stack: html, css, bulma
- [multiplayer life game](https://github.com/KuzmichovaMary/multiplayer-life-game) stack: python

## Languages
- English: Intermediate
- Russian: Native speaker

