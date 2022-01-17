## Documentacion de los casos de prueba
| ID        | Nombre           | Pasos a ejecutar  | Resultado Esperado |
| ------------- |:-----------------------------------------------:| -----:| -----:|
| 1     | Ping | 1. Realizar una GET Request al siguiente recurso <br> https://echo-serv.tbxnet.com/v1/system/ping | La respuesta obtenida debe contener <br>  "ok": true   |
| 2     | Echo | 1. Realizar una GET Request al siguiente recurso <br> https://echo-serv.tbxnet.com/v1/echo?text=test | La respuesta obtenida debe contener <br> "text": "test"   |

## Como se ejecutan las pruebas  
1. Descargar Docker Desktop
2. Clonar este repositorio
3. Ejecutar el archivo run.bat
