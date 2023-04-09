# Задание 1
![](https://github.com/OlgaLesnykh/screenshots/blob/main/SVIRT_041.png)    
Docker Compose используется для одновременного управления несколькими контейнерами, входящими в состав приложения. 
Этот инструмент предполагает те же возможности, что и Docker, но позволяет работать с более сложными приложениями. Docker Compose может существенно облегчить развертывание 
приложений со сложной архитектурой - с его использованием не придется настраивать все сервисы отдельно по-одному (не без риска что-то забыть). Например, перенос проекта 
на новый сервер при использовании Docker Compose можно осуществить с помощью нескольких команд, без использования Docker Compose этот процесс длительный и трудоемкий.
# Задание 2
```
version: "3"
services:


networks:
  LesnykhOA-my-netology-hw:
    driver: bridge
    ipam:
      config:
      - subnet: 172.22.0.0/24

# Задание 3

# Задание 4
# Задание 5
# Задание 6
# Задание 7
# Задание 8