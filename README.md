<!DOCTYPE html>
<html>
<body>
<img width="1913" height="1026" alt="Captura de tela 2026-03-20 101154" src="https://github.com/user-attachments/assets/bc2c3078-2064-4a18-8aa7-8535f172c99c" />


  <h1>Explicação do Projeto: Servidor HTTP em Python</h1>

  <p>A imagem demonstra a interação entre um código backend e uma ferramenta de testes de API (Postman/Hoppscotch).</p>

  <hr>

  <h2>1. O Código (Lado Esquerdo - VS Code)</h2>
  <ul>
    <li><b>Método GET:</b> O servidor responde com uma mensagem confirmando que está online.</li>
    <li><b>Método POST:</b> O servidor está configurado para <u>receber dados</u>. Ele lê o tamanho da mensagem (Content-Length) e imprime o que foi recebido no terminal.</li>
  </ul>

  <h2>2. O Teste (Lado Direito - Ferramenta de API)</h2>
  <p>
    O usuário enviou uma requisição do tipo <b>POST</b> para o endereço IP do servidor. 
    O status retornado foi <b>200 OK</b>, o que significa que a comunicação teve sucesso.
  </p>

  <h2>3. O Terminal (Parte Inferior)</h2>
  <blockquote>
    No terminal, podemos ver o histórico de acessos (logs). A última linha mostra que o IP 
    <code>10.87.38.10</code> realizou um POST com sucesso às 10:11:16.
  </blockquote>

  <hr>
 <li>O vs code/Server é quem está com o código e ele não realiza nenhuma ação até receber o pedido  o clinte/Post man, após isso o server começa a trabalhar e se tudo estiver correto(ipconfig e códigos) aparecerá uma mensagem no postman "post recebido"<li>
  <h3>Resumo do Fluxo</h3>
  <ol>
    <li>O Servidor Python é ligado.</li>
    <li>A ferramenta de teste envia uma mensagem.</li>
    <li>O Python recebe, processa e responde "POST recebido"</li>


</body>
</html>
