# ValidadordeEAN
Validador de EAN Multi Banco de Dados  [Firebird]

Aplicativo validara os códigos de barras em uma base de dados firebird, cabendo o operador realizar algumas configurações iniciais:

Selecionar a base de dados;
Selecionar a tabela dos produtos;
Selecionar os campos da tabela 'produtos' relacionadas ao 'codigo', 'descricao',codigo de barras' e 'um campo qualquer', sendo que o campo qualquer, deverá está vazio e possível edição para receber o status da validação.

O campo vazio, deverá ter a estrutura 'Varchar' para receber o resultado da validação.

Além do procesos, poderá realizar o filtro por código invalido, código válido, código não processado, e realizar impressão dos mesmos para posteriormente corrigir os códigos manualmente;
