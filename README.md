# programa_acelera

O BR Bank é uma fintech que tem a missão de conceder crédito e educar seus clientes para o consumo consciente.

A empresa teve aporte de seus investidores por determinado tempo e, atualmente, busca o caminho para monetização de sua operação para garantir sua sustentabilidade.

Para tanto, tem, para o ano de **2023**, a **meta** de **R$30 milhões** e conta com um **orçamento de marketing** de **R$4 milhões**, os quais as equipes de aquisição, relacionamento e monetização devem alocar de modo a atingir a meta.

Seu portifólio de produtos conta com uma conta digital gratuita e uma linha de empréstimo pessoal.

Para realizar a análise da situação atual e propor medidas a serem tomadas, a equipe de engenharia de dados disponibilizou cinco bases de dados.

## Bases de dados

Foram disponibilizadas as seguintes bases de dados para a realização da análise compreendendo o período de **09/22** a **02/23**, considerando a data do lead (basta clicar no nome da base para acessar o detalhamento de cada uma delas):

- Base de cadastro da conta digital
    
    A base conta com 512 registros.
    
    | Variável | Descrição |
    | --- | --- |
    | Data do
      Cadastro na Conta Digital | Data em que o lead virou cliente do produto de Conta Digital |
    | ID_Lead | Identificação do cliente no sistema de CRM. |
    | DDD do Celular | DDD do celular do cliente |
    | Qual a sua área de atuação? | Área de atuação do cliente (pergunta feita no processo de cadastro) |
    | Qual o seu cargo atual? | Cargo atual do cliente (pergunta feita no processo de cadastro) |
    | Quais seus objetivos com a conta digital da BR Bank? | Respostas para a pergunta de "objetivos" com a conta digital. |
    | Como você conheceu o BR Bank? | Respostas para a pergunta sobre "como conheceu" a fintech. |
- Base CRM
    
    
    | Variável | Descrição |
    | --- | --- |
    | ID_Lead | Identificação do cliente no sistema de CRM. |
    | Vendedor que atendeu | Vendedor que tentou realizar a venda para o cliente. |
    | Data do Lead | Data em que a solicitação de empréstimo foi realizada pelo lead. |
    | Data da Conversão | Data em que a contratação do empréstimo foi finalziada. |
    | Conversão | 1 se lead se converteu em cliente (ou seja, teve um empréstimo contratado) e 0 caso contrário. |
    | Receita | A receita trazida pelo empréstimo. Lembrando que a receita é líquida de perdas oriundas de inadimplência. Exemplo: Se o cliente pediu 1000 reais de empréstimo e o banco vai receber 100 de juros (caso o cliente pague o empréstimo totalmente), então a receita desta operação é 100 reais. |
    | Data da Perda | Data em que o negócio foi perdido. Ou seja, o lead optou por não contratar o empréstimo. |
    | Motivo da Perda | Motivo da perda do negócio informada pelo vendedor. |
- Google Ads
    
    
    | Dia | Descrição |
    | --- | --- |
    | Dia | Data em que os anúncios foram
      gerados. |
    | Tipo de Campanha | Tipo de campanha, sendo:
         - "Conversão" para anúncios focados na venda de produtos para o "público frio", sendo que o anúncio aparece na busca como Link Patrocinado;
        
        - "Conversão Youtube" para anúncios focados na venda de produtos para o "público frio" sendo que o anúncio aparece antes do início de vídeo do Youtube;
        
        - "Remarketing" para venda de produtos para o "público quente";
        
        - "Institucional" para venda de produtos para clientes que digital o novo "Br Bank" no Google. |
    | Produto/Anúncio | Produto em que o anúncio tenta
      vender. |
    | Impressões
      do anúncio | Quantidade de vezes em que o anúncio apareceu na busca do Google ou no Youtube. |
    | Cliques | Quantidade de cliques no anúncio. |
    | Custo | Custo diário para este anúncio ser veiculado na plataforma do Google. |
    | Conversões | Qte de Empréstimos Contratados
      para um dado dia e anúncio. |
    | Receita | Receita gerada pelos empréstimos
      contratados para um dado dia e anúncio. |
- Google Analytics
    
    
    | Variável | Descrição |
    | --- | --- |
    | Data de Acesso | Data do acesso do lead ao site da empresa |
    | Acessos ao Site | Quantidade de acessos de leads na data informada |

- Meta Ads
    
    
    | Variável | Descrição |
    | --- | --- |
    | Dia | Data em que os anúncios foram gerados. |
    | Tipo de Campanha | Tipo de campanha, sendo "Conversão" para anúncios focados na venda de produtos para o "público frio" e anúncios de "Remarketing" para venda de produtos para o "público quente". |
    | Produto/Anúncio | Produto em que o anúncio tenta vender. |
    | Público | Cold: Público frio, ou seja, pessoas que nunca tiveram contato com a empresa em suas redes sociais ou página de vendas.
        
    Hot: Público quente, ou seja, pessoas que já tiveram contato com a empresa em suas redes sociais ou página de vendas. |
    | Impressões do anúncio | Quantidade de vezes em que o anúncio apareceu no feed, stories ou reels nas plataformas da Meta. |
    | Cliques | Quantidade de cliques no anúncio. |
    | Custo | Custo diário para este anúncio ser veiculado na plataforma da Meta. |
    | Cadastros de Conta Corrente | Quantidade de Cadastros de Conta Corrente concluídos para um dado dia e anúncio. |
    | Conversões | Quantidade de Empréstimos Contratados para um dado dia e anúncio. |
    | Receita | Receita gerada pelos empréstimos contratados para um dado dia e anúncio. |

