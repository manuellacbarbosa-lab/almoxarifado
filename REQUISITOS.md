# Requsitos Funcinais
· [RF01] Cadastro de Itens: O sistema deve permitir registrar o nome e a marca de um produto novo.
· [RF02] Controle de Entrada e Saída: O usuário deve conseguir registrar quantas unidades de um produto
estao entrando ou saindo do almoxarifado.
. [RF03] Consulta de Estoque: O sistema deve exibir uma lista clara com todos os produtos e a quantidade
que temos disponível de cada um no momento.
. [RF04] Historico: O usuario deve conseguir ver o historico do que aconteceu com cada produto (ex: "hoje
entraram 10 peças").

# Requisitos N Funcionais
. [RNF01] Responsividade: O sistema deve funcionar bem tanto em telas de computador quanto em
celulares. Os botoes de "Entrada" e "Saida" devem ser faceis de clicar mesmo em telas pequenas (telas
sensíveis ao toque).
· [RNF02] Simplicidade: A interface deve ser direta, evitando menus complicados para que o funcionário do
almoxarifado consiqa reqistrar uma movimentacao em poucos sequndos.
. [RNF03] Seguranca: Garantir que apenas usuarios autorizados possam alterar o estoque e cadastrar
produtos.

# Regras de Negócio

· [RN01] Consistência: O saldo do produto na tabela de "Produtos" deve ser sempre o resultado da soma de
todas as entradas menos a soma de todas as saidas registradas na tabela de "Movimentaçoes".
. [RN02] Não permitir saldo negativo: O sistema não deve permitir que uma "Saída" seja registrada se não
houver estoque suficiente, para evitar errosho almoxarifado.
· [RN03] Rastreabilidade: Toda movimentação deve registrar a data e o motivo (entrada ou saida) para
podermos conferir o inventário futuramente.