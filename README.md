<h2>Desafio Modelagem Conceitual Digital Innovation One </h2>

<p>https://web.dio.me/</p>


<h3>Descrição do Desafio</h3>

<p>O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para 
  fornecer o contexto sobre seu esquema.</P>

<h3>Objetivo:<h3>
<p>Refine o modelo apresentado acrescentando os seguintes pontos:</p>
<p> <strong>•	Cliente PJ e PF –</strong> Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;</p>
<p><i>Solução: Foi desmembrado o atributo identificação em (TipoCliente, CnpjCpf). Pode ser feita uma validação via programação no banco de dados ou no backend da aplicação.</i></p>
<p>•	Pagamento – Pode ter cadastrado mais de uma forma de pagamento;</p>
<p><i>Solução: Foi criada a tabela “FormaPagamento”, com os atributos (idFormaPagamento, descrição). 
O relacionamento é 1:1, onde o cliente escolha a forma de pagamento que ele quer utilizar no e-commerce, podendo ser alterada.</i></p>
<p>•	Entrega – Possui status e código de rastreio;</p>
<p><i>Solução: Foi criada a tabela “Entrega”, com os atributos (idEntrega, enderecoEntrega, statusEntrega, codigoRastreio). Também foi criada a tabela “Transportadoras” com os atributos (idTransportadora, razaoSocial, CNPJ, endereco).</p>
<p>Os relacionamentos foram 1:1 para Pedido/Entrega e N:N para Entrega/Transportadoras. Cada pedido tem uma entrega. Várias entregas podem ser entregues por várias transportadoras.</i></p>

