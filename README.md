# Enviar_arquivos_conexao_TCP
Projeto da cadeira Infraestrutura de Comunicação da UFPE

Esse programa cliente-servidor utiliza a porta TCP 60200 no servidor e funciona da seguinte forma: após conexão do cliente e o recebimento da mensagem/comando “comece”, o servidor encaminha ao cliente um arquivo zipado de pelo menos 2 Mbytes e no máximo  10 Mbytes.  O servidor deverá enviar imediatamente ao cliente, após o envio do último byte do arquivo, a mensagem/comando “terminei”. O cliente ao receber essa mensagem, deve remontar o arquivo e salvando-o em disco.

Para rodar primeiro inicie o Servidor e em seguida o Cliente.
