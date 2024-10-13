#Informacion Personal

##1

##2

##3

##**Que hago por las Manñanas**

```pandoc
st=>start:Me despierto;
des=>operation: Desalluno;
bañ=>operation: Voy al baño;
cond=>condition:Tengo ganas de ir al baño?;
e=>end: Voy al cuarto;
st->des->cond;
cond(yes)->bañ;
cond(no)->e;
```
