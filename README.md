# TelaSMTP
 
 O TelaSMTP é um a interface gráfica desenvolvida em JAVA, que possibilita apenas o envio de emails. Ademais, isso fora possível pois seu código fonte faz uso do  protocolo SMTP em uma de suas portas (465).
```Java
        email.setHostName("smtp.gmail.com");
        email.setSmtpPort(465);
``` 
## Instalação de recursos

 O programa precisará, previamente, do plug-in JRE (Java Runtime Evironment) instalado em seu computador. Outrossim, o JRE (para diversos sistemas operacioanis) poderá ser encontrado no próprio site da Oracle, só que com um novo nome (Java SE Runtime Environment), afinal, dispõe de novas tecnologias. Todavia, o prórpio site da Oracle possui tutoriais intuitivos para o uso do JRE nos "diversos sistemas operacionais" citados outrora. 

[Oracle](https://www.oracle.com/technetwork/pt/java/javase/downloads/jre8-downloads-2133155.html)

## Uso

A execução apresentará uma interface gráfica desenvolvida na IDE NetBeans da Oracle, que irá conter os campos: "para quem: " (relativo ao remetente da mensagem, podendo ser qualquer email cadastrado em um serviço de mail (gmail, hotmail, etc); "Assunto: "(Relativo ao assunto da mensagem a ser enviada); "Mensagem: " (Área textual relacionada ao texto que será enviado); e também contará com os botões: "Enviar" (que envia a mensagem para o remetente); e "Limpar texto" (responsável pela limpeza do campo de texto relacionado à mensagem). Outrossim, o email será enviado da Conta Google referenciada à seguir (que está passível a alterações):
```Java
        String mail = "roboticaaula123@gmail.com";
        String pass = "nzzcjxslgcxnnpys";
 ```
 
 Contudo, como o servidor host SMTP ("smtp.gmai.com") desse código é conectado ao gmail, apenas contas google estão aptas ao envio de mensagens.

## Contribuindo 

Puxar pedidos são bem-vindos. Para mudanças importantes, por favor, abra um problema primeiro para discutir o que você gostaria de mudar.

Por favor, certifique-se de atualizar os testes conforme apropriado.



