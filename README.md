<!DOCTYPE html>
<html>
<head>
  <title>Pães de Queijo Quentinhos</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css">
  <script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
  <script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>
<div data-role="page" id="home">
  <div data-role="header" data-position="fixed">

    <h1>Pães de Queijo Quentinhos</h1>

    <div data-role="navbar">
      <ul>
        <li><a href="#page1" data-icon="home">Página Inicial</a></li>
        <li><a href="#page2" data-icon="grid">Catalogo de Produtos</a></li>
        <li><a href="#page3" data-icon="star">Promoções Especiais</a></li>
        <li><a href="#page4" data-icon="info">Sobre Nós</a></li>
        <li><a href="#page5" data-icon="phone">Contato</a></li>
        <li><a href="#page6" data-icon="gear">Termos e Condições</a></li>
        <li><a href="#page7" data-icon="info">Perguntas Frequentes</a></li>
        <li><a href="#page8" data-icon="user">Formulário de Cadastro</a></li>
        <li><a href="#page9" data-icon="shop">Seja um Revendedor</a></li>
        <li><a href="#page10" data-icon="alert">Reclamações</a></li>
      </ul>
    </div>
  </div>
   
  <div data-role="main" class="ui-content">
    <h2>Bem-vindo à Pães de Queijo Quentinhos</h2>

    <p>Vendemos Pães de Queijo e Oferecemos aos nossos clientes a oportunidade de serem revendedores.</p>
   
    <!-- Tabela com texto e imagens -->
    <table data-role="table" id="products-table" data-mode="reflow" class="ui-responsive">
      <thead>
        <tr>

          <th>Produto</th>
          <th>Descrição</th>
          <th>Imagem</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Pão de Queijo</td>
          <td>Pão de queijo Tradicional Ou com Requeijão</td>
          <td><img src="https://www.tudoemdia.com/wp-content/uploads/2019/02/Muito-al%C3%A9m-do-p%C3%A3o-de-queijo-e1551210643220.jpg" alt="Imagem 1"></td>
        </tr>
        <tr>
          <td>Pão de Queijo com Goiabada</td>
          <td>Pão de Queijo Recheado com Goiabada</td>
          <td><img src="https://receitatodahora.com.br/wp-content/uploads/2018/09/pao-de-queijo-recheado-com-goiabada-2.jpg" alt="Imagem 2"></td>
        </tr>
        <tr>
          <td>Pão de Queijo com Frango</td>
          <td>Pão de Queijo Recheado com Frango</td>
          <td><img src="https://receitasturbinadas.com.br/wp-content/uploads/2019/09/69350506_439994443321968_507328585044852736_n.jpg" alt="Imagem 3"></td>
        </tr>
       <tr>
          <td>Pão de Queijo com Doce de Leite </td>
          <td>Pão de Queijo Recheado com Doce de Leite </td>
          <td><img src="https://www.guiadaculinaria.com/wp-content/uploads/2019/07/receitas-de-pao-de-queijo-recheado-2-750x430.jpg" alt="Imagem 4"></td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
  
  <!-- Página 1 -->
  <div data-role="page" id="page1">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Página Inicial</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p>O pão de queijo é uma ótima opção para quem tem intolerância ao glúten, já que pode ser feito com polvilho doce. A receita tradicional leva polvilho azedo, queijo, ovos, leite e óleo e existem diversas variações da receita, como a inclusão de ingredientes como batata-doce, mandioca e até mesmo chocolate.</p>
      <img src="imag 1.jpg" alt="Imagem 1">
    </div>
  </div>
  
  <!-- Página 2 -->
  <div data-role="page" id="page2">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Catálogo de Produtos</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p>Variedades dos produtos nas fotos.</p>
      <img src="https://paodequeijoecia.com.br/wp-content/uploads/2020/01/paodequeijorecheado-01.png" alt="Imagem 2">
    </div>
   <table border="1">
    <tr>
        <td>Produtos</td>
        <td>Quantidade</td>
        <td>Valor</td>
    </tr>
    <tr>
        <td>Pão de Queijo Tradicional Ou Com Requeijão</td>
        <td>2kg</td>
        <td>R$40,00/R$45,00</td>
    </tr>
    <tr>
        <td>Pão de Queijo Com Recheio de Goiabada</td>
        <td>2kg</td>
        <td>R$45,00</td>
    </tr>
    <tr>
        <td>Pão de Queijo Com Recheio de Frango</td>
        <td>2kg</td>
        <td>R$45,00</td>
      </tr>
     <tr>
        <td>Pão de Queijo Com Recheio de Doce de Leite</td>
        <td>2kg</td>
        <td>R$45,00</td>
      </tr>
</table>
   </div>
  

  
  <!-- Página 3 -->
  <div data-role="page" id="page3">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Promoções Especiais</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p>Na compra de dois produtos, leve outro grátis.</p>
      <img src="https://www.falamart.com.br/wp-content/uploads/2017/12/pack-promocional-3-e1533325138740.png" alt="Imagem 3">
    </div>
  </div>



  <!-- Página 4 -->
  <div data-role="page" id="page4">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Sobre Nós</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p>Somos especializados em entregar aos clientes saborosos e deliciosos sonhos quentinhos em formato de pão de queijo, nosso objetivo e sempre entregar o melhor ao cliente.</p>
      <img src="https://i0.wp.com/guiadocorpo.com/wp-content/uploads/2018/07/P%C3%A3o-de-Queijo-Low-carb-receita-fit-deliciosa-03.jpg" alt="Imagem 4">
    </div>
  </div>

  
  <!-- Página 5 -->
  <div data-role="page" id="page5">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Contatos</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p> Endereço:Rua Betel, 02 , Nova Holanda - Macaé - RJ</p>
      <p> Telefones:(22) 32351612 / (22) 999971204</p>
      <p> Site:contato@paesqueijoquentinho.com.br</p>
      <p>Instagram:@paesqueijoquentinhos</p>
      <p>Horário de Funcionamento: Seg - Sex: 09:00 - 18:00</p>
    <img src=" http://3.bp.blogspot.com/-6N9lJIUq7SE/UVBCGmC5BOI/AAAAAAAAAO0/iUTMC32QaQU/s1600/lanche.jpg " alt="Imagem 5">
    </div>
  </div>

  
  <!-- Página 6 -->
  <div data-role="page" id="page6">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Termos e Condições</h1>
    </div>
    <div data-role="main" class="ui-content">
      <p> 1. Termos Ao acessar ao site PaesdeQueijoQuentinhos, concorda em cumprir estes termos de serviço, todas as leis e regulamentos aplicáveis ​​e concorda que é responsável pelo cumprimento de todas as leis locais aplicáveis. Se você não concordar com algum desses termos, está proibido de usar ou acessar este site. Os materiais contidos neste site são protegidos pelas leis de direitos autorais e marcas comerciais aplicáveis.
<p>2. Uso de LicençaÉ concedida permissão para baixar temporariamente uma cópia dos materiais (informações ou software) no site PaesdeQueijoQuentinhos , apenas para visualização transitória pessoal e não comercial. Esta é a concessão de uma licença, não uma transferência de título e, sob esta licença, você não pode: modificar ou copiar os materiais; usar os materiais para qualquer finalidade comercial ou para exibição pública (comercial ou não comercial); tentar descompilar ou fazer engenharia reversa de qualquer software contido no site PaesdeQueijoQuentinhos; remover quaisquer direitos autorais ou outras notações de propriedade dos materiais; ou transferir os materiais para outra pessoa ou 'espelhe' os materiais em qualquer outro servidor.Esta licença será automaticamente rescindida se você violar alguma dessas restrições e poderá ser rescindida por PaesdeQueijoQuentinhos a qualquer momento. Ao encerrar a visualização desses materiais ou após o término desta licença, você deve apagar todos os materiais baixados em sua posse, seja em formato eletrónico ou impresso.</p>
<p>3. Isenção de responsabilidadeOs materiais no site da PaesdeQueijoQuentinhos são fornecidos 'como estão'. PaesdeQueijoQuentinhos não oferece garantias, expressas ou implícitas, e, por este meio, isenta e nega todas as outras garantias, incluindo, sem limitação, garantias implícitas ou condições de comercialização, adequação a um fim específico ou não violação de propriedade intelectual ou outra violação de direitos.Além disso, o PaesdeQueijoQuentinhos não garante ou faz qualquer representação relativa à precisão, aos resultados prováveis ​​ou à confiabilidade do uso dos materiais em seu site ou de outra forma relacionado a esses materiais ou em sites vinculados a este site.</p>
<p>4. LimitaçõesEm nenhum caso o PaesdeQueijoQuentinhos ou seus fornecedores serão responsáveis ​​por quaisquer danos (incluindo, sem limitação, danos por perda de dados ou lucro ou devido a interrupção dos negócios) decorrentes do uso ou da incapacidade de usar os materiais em PaesdeQueijoQuentinhos, mesmo que PaesdeQueijoQuentinhos ou um representante autorizado da PaesdeQueijoQuentinhos tenha sido notificado oralmente ou por escrito da possibilidade de tais danos. Como algumas jurisdições não permitem limitações em garantias implícitas, ou limitações de responsabilidade por danos conseqüentes ou incidentais, essas limitações podem não se aplicar a você.</p>
<p>5. Precisão dos materiaisOs materiais exibidos no site da PaesdeQueijoQuentinhos podem incluir erros técnicos, tipográficos ou fotográficos. PaesdeQueijoQuentinhos não garante que qualquer material em seu site seja preciso, completo ou atual. PaesdeQueijoQuentinhos pode fazer alterações nos materiais contidos em seu site a qualquer momento, sem aviso prévio. No entanto, PaesdeQueijoQuentinhos não se compromete a atualizar os materiais.</p>
    </div>
  </div>

  
  <!-- Página 7 -->
  <div data-role="page" id="page7">
    <div data-role="header" data-position="fixed">
      <a href="#home" data-icon="back" data-rel="back">Voltar</a>
      <h1>Perguntas Frequentes</h1>
    </div>
    <div data-role="main" class="ui-content">
      <h2>Dúvidas</h2>
      <p>Pode ser considerado um alimento saudável?
A quantidade diária ideal e equilibrada de pão de queijo é de 100 gramas, sendo assim, se for consumido sem excessos, pode ser um alimento muito presente na sua refeição,isso porque ele possui lipídios, sais minerais, carboidratos, proteínas e vitaminas.</p>
<p>O produto possui glúten?
Não possui justamente por ser feito de polvilho.</p>
<p>Quem faz dieta pode comer sem problemas?
Então se estiver em uma dieta um pouco restrita,pode optar pelo integral.</p>
<p>Onde posso assar meu pão de queijo?
Fica a seu critério fazer no forno, ou pode ser feito na airfryer em 10 a 15 minutos a 180ºC.</p>
<p>Quantas calorias possui o pão de queijo?
Pão de queijo pequeno (unidade de 50g): 111 kcal;
Pão de queijo médio (unidade de 80g): 233 kcal;
Pão de queijo grande (120g): 178 kcal;
100g o tradicional: 222 kcal.
  Já o recheado pode variar de 232 kcal para mais dependendo do recheio por 100g.</p>
    </div>
  </div>
  
<div data-role="page" id="page8">
  <div data-role="header" data-position="fixed">
    <a href="#home" data-icon="back" data-rel="back">Voltar</a>
    <h1>Formulário de Cadastro</h1>
  </div>
  <div data-role="main" class="ui-content">
    <h2>Formulário de Cadastro</h2>
    <form action="caminho/para/processar_cadastro.php" method="post" id="formCadastro">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <label for="senha">Senha:</label>
      <input type="password" id="senha" name="senha">
      <input type="submit" value="Cadastrar">
    </form>
  </div>
</div>
  
  <div data-role="page" id="page9">
  <div data-role="header" data-position="fixed">
    <a href="#home" data-icon="back" data-rel="back">Voltar</a>
    <h1>Seja um Revendedor</h1>
  </div>
  <div data-role="main" class="ui-content">
    <h2>Formulário de Revendedor</h2>
    <form action="caminho/para/processar_revendedor.php" method="post" id="formRevendedor">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <label for="endereco">Endereço:</label>
      <input type="text" id="endereco" name="endereco">
      <label for="cidade">Cidade:</label>
      <input type="text" id="cidade" name="cidade">
      <label for="estado">Estado:</label>
      <input type="text" id="estado" name="estado">
      <label for="cep">CEP:</label>
      <input type="text" id="cep" name="cep">
      <input type="submit" value="Tornar-se Revendedor">
    </form>
  </div>
</div>
<div data-role="page" id="page10">
  <div data-role="header" data-position="fixed">
    <a href="#home" data-icon="back" data-rel="back">Voltar</a>
    <h1>Formulário de Reclamação</h1>
  </div>
  <div data-role="main" class="ui-content">
    <h2>Formulário de Reclamação</h2>
    <form action="caminho/para/processar_reclamacao.php" method="post" id="formReclamacao">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email">
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem"></textarea>
      <input type="submit" value="Enviar Reclamação">
    </form>
  </div>
</div>
<script>
  // Espera o documento estar pronto
  $(document).ready(function() {
    // Manipula o envio do formulário de cadastro
    $('#formCadastro').submit(function(event) {
      event.preventDefault();
      // Exibe a mensagem de sucesso
      $.mobile.changePage("#paginaSucesso", { transition: "slide" });
    });

    // Manipula o envio do formulário de revendedor
    $('#formRevendedor').submit(function(event) {
      event.preventDefault();
      // Exibe a mensagem de sucesso
      $.mobile.changePage("#paginaSucesso", { transition: "slide" });
    });

    // Manipula o envio do formulário de reclamação
    $('#formReclamacao').submit(function(event) {
      event.preventDefault();
      // Exibe a mensagem de sucesso
      $.mobile.changePage("#paginaSucesso", { transition: "slide" });
    });
  });
</script>

  
    </div>
  </div>
</body>
</html>
