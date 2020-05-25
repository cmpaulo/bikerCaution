# bikerCaution
This project shows a different option for taking care of the child when they both ride their bikes together.

# ESP8266
 são duas peças ao menos, um fica com o pai ou responsável e outro com a criança. 
 
 ESPpai >> ESPfilho1
 ESPpai >> ESPfilho2
 ESPpai >> ESPfilho3
 
# ESPpai 

 Vai terá sua rede propria "wifi-pai", o adaptador wifi fica monitorando a potencia do sinal dos receptores,("wifi-filho1", "wifi-filho2", "wifi-filho3")  sincronizados, a pontencia do sinal mais fraca indica que a criança esta muito longe do pai. A distancia que o filho está do pai, cria uma interação do ESPpai com o pai, alertando que os filhos estão muito longe, este alerta é feito a partir de uma vibraçao do equipamento (ESPpai). Este equipamento pode ser sincronizado com o celular, ou ser usado de maneira que o pai/responsável note a vibração.

 * caso 1: ESPpai sincronizado com o Celular:
 O pai/responsável sincroniza (wifi ou bluethooth ) o ESPpai com o celular e os alertas e distância ( ESPpai >> ESPfilho ) aparecem na tela do celular utilizando o aplicativo (bikerCaution App). 
 
 * caso 2: ESPpai sozinho:
 O pai/responsável porta conigo o ESPpai que irá emitir vibrações caso os ESPfilho estejam muito longe do ESPpai, alertando o pai/reponsável que os filhos estão muito longe.
 
 * inicialmente o projeto bikerCaution terá um ESPpai sincronizado com ESPfilho recebe o sinal do ESPfilho e mede a potencia do sinal wifi e emite vibraçoes alertando o pai/responsável.
 
# How to works ?

ESPpai sincronizado com ESPfilho mede a potencia do sinal do ESPfilho e se estiver abaixo de -40db, o ESPpai emite uma vibração que avisa o pai/responsável.
 
 

