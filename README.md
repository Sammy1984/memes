# memes

[21.02, 18:07] Andrey ZobovНастройка сервера для отдела разработки
    Парни, привет.
Ну что, хотите потренироваться в настройке сервера?
У нас есть следующие задачи (пока опишу в общем, детали по запросу smile):


	
Настроить web-сервер (gunicorn) для мемасницы (django+postgres+redis) в docker. Работающее без root привилегий в докере. Сделать production и dev сборки. Предусмотреть перезапуск после падений приложения или перезагрузки сервера. 
	
Настроить отдельный субдомен для статики, типа cdn.meme... 
	
Настроить отдельный субдомен для REST API, типа api.meme...

Nginx уже стоит, надо только донастроить недостающие виртуальные хосты и маршрутизацию запросов. Интересно?
(понравилось: 1)<https://teams.microsoft.com/l/message/19:rc0_V0-fzAJiiplRYDi8hRr5V4H2LHO2qmJ50ZAeR_Y1@thread.tacv2/1645448877399?tenantId=fc8b6b47-53ef-4529-aea4-8c6c20a851cf&amp;groupId=f5fb071b-2f88-47e4-bdfe-a3391ebcec5e&amp;parentMessageId=1645448877399&amp;teamName=QAC DEVOPS&amp;channelName=Общий&amp;createdTime=1645448877399>
