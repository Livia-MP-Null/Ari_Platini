<!DOCTYPE html>
<html>
<body>
  <h1> </b>Trabalho de ARI server ✍(◔◡◔) <h1>
<img width="1913" height="1026" alt="Captura de tela 2026-03-20 101154" src="https://github.com/user-attachments/assets/bc2c3078-2064-4a18-8aa7-8535f172c99c" />


  <h1>Explicação do Projeto: Servidor HTTP em Python (>‿◠)✌</h1>

  <p>A imagem demonstra a interação entre um código backend e uma ferramenta de testes de API (Postman/Hoppscotch).</p>

  <hr>

  <h2>1. O Código (ɔ◔‿◔)ɔ ♥ (Lado Esquerdo - VS Code)</h2>
  <ul>
    <li><b>Método GET:</b> O servidor responde com uma mensagem confirmando que está online.</li>
    <li><b>Método POST:</b> O servidor está configurado para <u>receber dados</u>. Ele lê o tamanho da mensagem (Content-Length) e imprime o que foi recebido no terminal.</li>
  </ul>

  <h2>2. O Teste (ง︡'-'︠)ง (Lado Direito - Ferramenta de API)</h2>
  <p>
    O usuário enviou uma requisição do tipo <b>POST</b> para o endereço IP do servidor. 
    O status retornado foi <b>200 OK</b>, o que significa que a comunicação teve sucesso.
  </p>

  <h2>3. O Terminal (ㆆ_ㆆ) (Parte Inferior)</h2>
  <blockquote>
    No terminal, podemos ver o histórico de acessos (logs). A última linha mostra que o IP 
    <code>10.87.38.10</code> realizou um POST com sucesso às 10:11:16.
  </blockquote>

  <hr>
 <li>O vs code/Server é quem está com o código e ele não realiza nenhuma ação até receber o pedido  o clinte/Post man, após isso o server começa a trabalhar e se tudo estiver correto(ipconfig e códigos) aparecerá uma mensagem no postman "post recebido"<li>
  <h3>Resumo do Fluxo☜(ˆ▿ˆc)</h3>
  <ol>
    <li>O Servidor Python é ligado.</li>
    <br>
    <li>A ferramenta de teste envia uma mensagem.</li>
      <br>
    <li>O Python recebe, processa e responde "POST recebido"</li>
    <!DOCTYPE html>
<html>
<body>

  <h1 style="color: #2ecc71;">🌐 Entendendo Redesᕙ(`▿´)ᕗ</h1>

  <p>Para o servidor Python funcionar, ele precisa de um <b>Endereço (IP)</b> e de uma <b>Porta</b>.</p>

  <hr>

  <h2>1. O que é o 0.0.0.0?( ≖.≖) (O Endereço "Ouvinte")</h2>
  <p>Quando você configura seu servidor para <code>0.0.0.0</code>, você está dizendo:</p>
  
  <blockquote style="background: #f9f9f9; border-left: 5px solid #3498db; padding: 10px;">
    " (•◡•) /Ei Python, aceite conexões de <b>QUALQUER</b> lugar: do meu próprio PC 모, do Wi-Fi da sala ou de qualquer outro computador 모 na mesma rede."
  </blockquote>

  <ul>
    <li><b>localhost (127.0.0.1):</b> ٩(˘◡˘)۶ Só meu PC 모 fala com o servidor.</li>
    <li><b>0.0.0.0:</b> (👍≖‿‿≖)👍 👍(≖‿‿≖👍) Todo mundo na rede pode tentar falar com o servidor.</li>
  </ul>

  

  <hr>

  <h2>2. O que é o 8000?(͠◉_◉᷅ ) (A Porta de Entrada)</h2>
  <p>Imagine que o IP é o endereço de um prédio🏢. A <b>Porta (Port)</b> é o número do apartamento específico onde o seu código Python está morando.</p>

  <table border="1" style="width:100%; border-collapse: collapse; text-align: center;">
    <tr style="background-color: #ecf0f1;">
      <th>Porta</th>
      <th>Uso Comum</th>
    </tr>
    <tr>
      <td>80</td>
      <td>Sites padrão (HTTP)</td>
    </tr>
    <tr>
      <td>443</td>
      <td>Sites seguros (HTTPS)</td>
    </tr>
    <tr>
      <td style="color: red;"><b>8000 / 8080</b></td>
      <td><b>Desenvolvimento (Seu Servidor Python)</b></td>
    </tr>
  </table>

  

  <hr>

  <h2>3. Por que isso é importante no  projeto (⊙.⊙(◉̃_᷅◉)⊙.⊙) ?</h2>
  <p>Na imagem, o servidor estava em <code>10.87.38.10:8000</code>. Isso significa:</p>
  <ol>
    <li><b>IP:</b> 10.87.38.10 (Onde o PC está na rede).</li>
    <li><b>Porta:</b> 8000 (Onde o script <code>Server.py</code> está ouvindo).</li>
  </ol>

  <p style="font-size: 18px; color: #e67e22;"><b>Resumo:</b> O IP te leva até a máquina, a Porta te leva até o programa!(͠≖ ͜ʖ͠≖)👌</p>

</body>
</html>




</body>
</html>






