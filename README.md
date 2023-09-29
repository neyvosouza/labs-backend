
TESTE PRÁTICO - BACKEND - INSTIVO

Desafio: Criação de uma API REST de Pagamento

Requisitos:

    Utilize o Spring Boot para criar a aplicação.
    Crie uma entidade chamada "Pagamento" com os seguintes campos: ID, produto, tipo de pagamento, preço.
    Implemente uma operação de pagamento aplicando uma taxa para cada tipo de pagamento.
    Tipo de pagamento:
        PIX (Desconto de 10%).
        Cartão de Débito (Mantem o valor).
        Cartão de Crédito (Acrescimo de 5%).        
    Implemente validações para garantir que os campos obrigatórios (produto, tipo de pagamento e preço) sejam preenchidos corretamente.
    Após o envio dos dados com sucesso, retorne uma  mensagem informando todos os dados enviados junto com a taxa aplicada e o valor calculado
    Documente a API 
    Utilize um banco para persistir os dados
    Enviar um merge-request no final para o Github

Critérios de Avaliação:

    Funcionalidade: A API deve ser capaz de realizar operações de POST para pagamento.
    Qualidade do Código: O código deve seguir boas práticas de desenvolvimento e estar bem organizado.
    Utilização do Spring Boot: Deve-se utilizar o Spring Boot para configurar a aplicação.
    Validações: O código deve implementar validações adequadas para os campos obrigatórios.
    Testes: O codigo deve possuir testes unitários
    Documentação: O código deve estar documentado de forma simples.

