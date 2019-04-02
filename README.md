Neste tutorial será criado um ChatBot com Watson Assistant e utilizará o Node-red e ChatFuel como orquestrador:
1) Crie um aconta na IBM Cloud: https://cloud.ibm.com/registration;
2) Crie uma instância do Watson Assitant e import o skill no json <a href="https://github.com/sergiogama/chatbot-watson-assistant-facebook-chatfuel/blob/master/WA-Skill-Reservar-mesa.json">aqui</a>, conforme o vídeo abaixo (https://www.youtube.com/watch?v=vPAJMZJ8804):

[![Integrando Watson Assistant ao Facebook](https://img.youtube.com/vi/vPAJMZJ8804/0.jpg)](https://www.youtube.com/watch?v=vPAJMZJ8804 "Criando o serviço Watson Assistant e importando um skill")

3) Volte para a aba do browser onde criou o serviço do Watson Assistant ou abra outra e abra o link https://cloud.ibm.com/console. 
   Crie uma instancia de Node-red e o configure para conectar em seu WA, criado no conforme o vídeo anterior, bem como crie a página do Facebook, o serviço de ChatFuel.
   Tudo isso está no vídeo abaixo https://www.youtube.com/watch?v=Oni7g2uK9PM.
   
[![Integrando Watson Assistant ao Facebook](https://img.youtube.com/vi/Oni7g2uK9PM/0.jpg)](https://www.youtube.com/watch?v=Oni7g2uK9PM "Integrando Watson Assistant ao Facebook")

Obs: Utilize <a href="https://github.com/sergiogama/chatbot-watson-assistant-facebook-chatfuel/blob/master/Node-red-flow-WA-Facebook-Chatfuel.json">aqui</a> flow mais aualizado.

4) Altere o seu fluxo no Node-red para a integração com Watson STT e TTS, para que o seu chatbot receba e envie aúdio. Será necessário instanciar os dois services na IBM Cloud Também. 
Utilize o flow anexo aqui e veja em detalhes no vídeo à seguir:

https://www.youtube.com/watch?v=d-O4UKYYLo0

[![Integrando Watson STT e TTS](https://img.youtube.com/vi/d-O4UKYYLo0/0.jpg)](https://www.youtube.com/watch?v=d-O4UKYYLo0 "Integrando Watson STT e TTS")

