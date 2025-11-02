# usingcicd
Шо имеем:
1. Нам нужен докер. dccker ce и docker compose (написано на go с 20-21 годов) - официальные пакеты, часть однйо инфры. docker-compose и docker.io - старые пакеты. docker-compose - отдельная хуйня, написанная на Python без полной поддержки docker cli. Docker.io - неофициальная хуйня.
  - sudo apt remove docker docker-engine docker.io containerd runc docker-compose
