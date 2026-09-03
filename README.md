# Django

Este es un trabajo para la materia Lab. Algoritmos y basicamente cuenta con dos partes:

1. /djangotutorial/ - el tutorial realizado de parte 1 a 8 de django

2. cuestionario.txt - cuestionario con las 8 preguntas resueltas. (7)

## que hay en /djangotutorial?

Es la app web de encuestas que pide hacer el tutorial

modelos choice y question
views que muestran preguntas, resultados, etc.
formulario para votar en cada pregunta
se instalo django debug toolbar
otras cosas

## como correrlo

entras en un cmd al directorio djangotutorial:

python manage.py runservers

Y despues desde un navegador ingresas al localhost en los siguientes puertos:

`http://127.0.0.1:8000/polls/` → app de encuestas
http://127.0.0.1:8000/admin/` → panel de admin (usuario admin`, contraseña contra123)

y para testear la web:

python manage.py test polls