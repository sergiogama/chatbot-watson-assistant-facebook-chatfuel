Neste tutorial será criado um ChatBot com Watson Assistant e utilizará o Node-red e ChatFuel como orquestrador:
1) Crie um aconta na IBM Cloud: https://cloud.ibm.com/registration;
2) Crie uma instância do Watson Assitant e import o skill no json no link abaixo, conforme o vídeo abaixo (https://www.youtube.com/watch?v=vPAJMZJ8804):

[![Integrando Watson Assistant ao Facebook](https://img.youtube.com/vi/vPAJMZJ8804/0.jpg)](https://www.youtube.com/watch?v=vPAJMZJ8804 "Criando o serviço Watson Assistant e importando um skill")

3) Volte para a aba do browser onde criou o serviço do Watson Assistant ou bara outra e abre o link https://cloud.ibm.com/console. 
   Crie uma instancia de Node-red e o configure para conectar em seu WA, criado no conforme o vídeo anterior, bem como crie a página do Facebook, o serviço de ChatFuel.
   Tudo isso está no vídeo abaixo https://www.youtube.com/watch?v=Oni7g2uK9PM.
   
[![Integrando Watson Assistant ao Facebook](https://img.youtube.com/vi/Oni7g2uK9PM/0.jpg)](https://www.youtube.com/watch?v=Oni7g2uK9PM "Integrando Watson Assistant ao Facebook")

7) É necessário fazer uma pré-configuração neste novo ambiente, basta clicar em "Visitar URL", ou apontar em um novo tab em seu browser para http:// + o host que criou + .mybluemix.net. Assim que abrir a tela, clique em "Next", crie um usuário e senha para esta instância, são credenciais exclusivas para esta instância (Não esqueça delas), então clique "Next", "Next" e "Finish".
8) Uma vez que esta na tela principal do Node-red, crie uma API para ser usado no ChatFuel, o qual vai enviar para você as mensagens dos usuários no Messenger. Copie o flow pronto no link abaixo para sua área de transferência, e através do menu amburguer que fila do lado diretito acima, em Import / From Clipboard, cole o conteúdo da área da transferênia e clique em "Import". Arraste o conteúdo para posicioná-lo n atela e dê um clique:


