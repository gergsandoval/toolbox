## Documentacion de los casos de prueba
| ID        | Nombre           | Pasos a ejecutar  | Resultado Esperado |
| ------------- |:-----------------------------------------------:| -----:| -----:|
| 1     | Ping | 1. Realizar una GET Request al siguiente recurso <br> https://echo-serv.tbxnet.com/v1/system/ping | La respuesta obtenida debe contener <br>  "ok": true   |
| 2     | Echo | 1. Realizar una GET Request al siguiente recurso <br> https://echo-serv.tbxnet.com/v1/echo?text=test | La respuesta obtenida debe contener <br> "text": "test"   |

## Prerequisitos
1. Instalar Docker

## Como se ejecutan las pruebas  
1. Clonar este repositorio
2. Ejecutar el archivo run.bat
