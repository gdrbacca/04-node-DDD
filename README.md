# 04-node-DDD
## Desafio 1 sobre DDD - entidades e casos de uso tiradas de um diálogo
<br />

Dev: Olá, obrigado por participar da entrevista. Para começar, quais são as principais funcionalidades que você gostaria de ver nesse sistema de gerenciamento de estoque?

Domain Expert: Precisamos de uma solução que nos permita rastrear cada produto individualmente, definir quantidades mínimas de estoque e receber alertas quando estivermos ficando sem um determinado produto. Também seria útil se pudéssemos visualizar o histórico de vendas e estoque para ajudar a tomarmos decisões futuras de compra.

Dev: Entendi. Você poderia me dar um exemplo de como você gostaria que a funcionalidade de rastreamento individual de produto funcionasse?

Domain Expert: Gostaríamos de poder atribuir um número de identificação único a cada produto, para podermos rastrear facilmente suas movimentações em nosso estoque. Também seria útil se pudéssemos adicionar informações extras, como tamanho e cor, para tornar o rastreamento ainda mais preciso.

Dev:  E quanto a funcionalidade de definição de quantidades mínimas de estoque, como você imaginaria isso funcionando?

Domain Expert: Gostaríamos de poder definir um limite mínimo para cada produto, de forma que pudéssemos receber um alerta quando o estoque estiver chegando próximo ao fim. Isso nos ajudaria a garantir que nunca fiquemos sem um produto popular e também nos permitiria fazer pedidos mais eficientes.

Dev: E como você gostaria de receber esses alertas? Por e-mail, SMS ou algum outro método?

Domain Expert: Seria ótimo se pudéssemos receber alertas por e-mail e também por meio de uma notificação em nosso sistema de gerenciamento de estoque.

Dev: Entendi. E quanto a funcionalidade de visualização de histórico de vendas e estoque, que tipo de informações você gostaria de ver?

Domain Expert: Gostaríamos de poder ver quantos produtos vendemos em um determinado período, qual foi o lucro gerado por produto e quais produtos estão vendendo melhor em cada período. Também seria útil se pudéssemos observar as tendências de estoque ao longo do tempo, para nos ajudar a tomar decisões de compra mais adequadas.

Dev:  Ok, e você tem alguma outra funcionalidade que gostaria de ver no sistema?

Domain Expert: Seria muito útil se o sistema pudesse nos permitir criar e gerenciar ordens de compra automaticamente, com base nas quantidades mínimas de estoque definidas e nas tendências de vendas. Também seria ótimo se pudéssemos integrar o sistema com nossos fornecedores, para que pudéssemos receber atualizações automáticas sobre os prazos de entrega de novas remessas.

------

## Entidades:
  •Produto; <br />
  •Registro de histórico de venda ou entrada de estoque; <br />
  •Ordem de compras; <br />

## Casos de uso:
  •Permitir rastrear produtos individualmente, através de suas características; <br />
	•Permitir definir quantidades mínimas de cada produto; <br />
	•O sistema deve emitir alerta por email e pelo próprio sistema quando um determinado produto chega a quantidade mínima; <br />
	•Manter e permitir visualizar o histórico de vendas e entradas de estoque, mostrando também algumas métricas, como quais produtos vendem mais, qual o lucro deles, quanto cada um vende, etc; <br />
	•Permitir integração com os fornecedores, para receber informações sobre novas remessas e prazos; <br />
