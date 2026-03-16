# Dinâmica de Grupo: Mapeando o Mundo Real
### Desafio prático: Formem grupos de 4 pessoas. Escolham um aplicativo como Uber ou Ifood e debatam:

#### 1 - Quem desempenha o papel de cliente(s)?
<b>Resposta:</b> 
 O papel de cliente é desempenhado por todos os participantes que solicitam algum 
serviço ou informação ao sistema.
* Usuário (cliente final): é quem utiliza o aplicativo para realizar o pedido de comida.
* Restaurante: atua como cliente quando solicita ao sistema informações sobre 
novos pedidos, status de pagamento ou chamada de entregador.
* Entregador: também atua como cliente ao solicitar corridas, enviar sua localização e 
receber atualizações sobre as entregas.

#### 2 - Quem é o Servidor?
<b>Resposta:</b>
  O servidor é o sistema central do iFood, ele é responsável por receber e analisar os 
pedidos feitos pelos clientes, enviar essas solicitações ao restaurante, chamar o 
entregador, processar os dados do pagamento e atualizar todas as informações do 
pedido até a entrega ser finalizada.  Ou seja, é o sistema que controla e organiza 
toda a comunicação entre cliente, restaurante e entregador.

#### 3 - Desenhem o fluxo da mensagem: Como é o pedido e como é a resposta?
<b>Resposta:</b>
* O cliente realiza um pedido pelo aplicativo.

*  O servidor recebe a solicitação e envia o pedido ao restaurante.

*  O restaurante confirma o pedido.

* O servidor notifica o cliente sobre a confirmação.

* Após o preparo, o restaurante informa ao servidor que o pedido está pronto.

* O servidor localiza e chama o entregador mais próximo.

* O entregador aceita a coleta do pedido.

* O servidor notifica o cliente sobre o andamento da entrega.

* O entregador envia suas coordenadas GPS ao servidor.

* O servidor atualiza o mapa em tempo real para o cliente acompanhar o trajeto.

* O entregador realiza a entrega e confirma a finalização.

* O servidor encerra o pedido e solicita uma avaliação.

* O cliente envia sua avaliação pelo aplicativo.

#### 4 - O que aconteceria se a internet do motorista/restaurante caísse no meio do processo?
<b>Resposta:</b>
Se a conexão com a internet do entregador ou do restaurante for interrompida, a 
comunicação com o servidor do sistema também será afetada.
Isso pode causar atraso nas atualizações do pedido, falhas na confirmação das 
etapas ou dificuldade para localizar o entregador em tempo real.
Dependendo do tempo sem conexão, o sistema pode até cancelar automaticamente 
a entrega ou gerar inconsistências nas informações mostradas ao cliente.
