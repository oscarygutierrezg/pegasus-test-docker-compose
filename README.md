# pegasus-test-docker-compose
```
- Debe tener instalado docker y corriendo
- Verificar que en maquina local no este corriendo nada en puertos 8080, 8081, 8082 y 3306
- Verificar que en docker no este corriendo nada en puertos 8080, 8081, 8082
- Verificar que en docker no este corriendo nada en puertos 3306
```



Para levantar todo el stack 
```sh
$ docker-compose up
```
Importar la coleccion de postman Test Pegasus.postman_collection

Para ver los swagger de entrar en los siguientes links:

- Person API http://localhost:8080/person/swagger-ui/index.html
- Pet API http://localhost:8081/pet/swagger-ui/index.html
- Veterinary API http://localhost:8082/veterinary/swagger-ui/index.html


Notas:

Credenciales por api
- person:
    username: testPersonUser
    password: xCMbk5081
- pet:
    username: testPetUser
    password: xCMbk5082
- veterinary:
    username: testVeterinaryUser
    password: xCMbk5083