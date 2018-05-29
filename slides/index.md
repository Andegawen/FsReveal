- title : Mob programming
- author : Krzysztof Kroczak
- theme : night
- transition : default

***

# Decouple parser from recovery system

***

# Agenda
1. Mob programming (2')
1. Why are we doing this?
1. Share knowledge with recovery system (15')
1. Let's do it

***

# Mob programming

---

# Whats' that?

> Mob Programming is a software development approach where the whole team works on the same thing, at the same time, in the same space, and at the same computer. This is similar to pair programming [PAIR],where two people sit at the same computer and collaborate on the same code at the same time. With Mob Programming we extend the collaboration to everyone on the team, while still using  a single computer for writing the code.

---

### Rules of mob programming

1. At any given time one person is the ‘Driver’. The driver is the person with the keyboard and mouse, the driver is the only person allowed to modify the code.
1. Everyone else takes the role of the ‘Navigator’. Whilst the driver spends a lot of their time occupied with the physical task of typing, the Navigator has all the time they need to think, review, discuss, describe. And that’s exactly what the navigator should do.
1. Everybody swaps roles — often. No, this isn’t some ‘everybody gets to play’ stuff you heard in primary school. If people stay in one role for too long they can become fatigued. if they have a favourite role then when they’re not in it they can become bored.

***

### Why are we doing this?

1. Better understanding the core idea of system.
1. There shouldn't exists such thing as ‘my corner’ of the code.
1. Leave world better - create understandable and readable code

*** 

### Recovery system
[Confulence about parser](https://info.red-gate.com/display/SP/SQL+Parser)

*** 

### Let's start :)

