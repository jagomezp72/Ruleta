# Ruleta
coding as candidate got new job.

api builded in vs2019

please change webconfig setting in order to modify your pc configuration to get database access 
database User:
ID=sa
Password=ruleta

available endpoints
item 1. get http://localhost:8911/Service1.svc/CreaNuevaRuleta/
item 2. get http://localhost:8911/Service1.svc/AbrirNuevaRuleta/1
item 4. get http://localhost:8911/Service1.svc/CierreRuleta/1
item 5. get http://localhost:8911/Service1.svc/ConsultaEstadoRuletas/
item 3. post http://localhost:8911/Service1.svc/HacerApuesta/

HEADER
key: TOKEN
value (in order to make HacerApuesta, please choose one of them)
ABC ,
DEF ,
GHI ,
JKL 

BODY
{
    "idruleta": 3,
    "elcolor": "rojo",
    "elvalor": 5000
}
{
    "idruleta": 3,
    "elnumero": 3,
    "elvalor": 5000
}


