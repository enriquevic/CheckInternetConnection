# Classe CheckInternet

A classe `CheckInternet` oferece um método para verificar a conexão com a internet. Esta funcionalidade é útil em situações em que uma aplicação precisa garantir uma conexão online para executar determinadas operações.

## Método

### `checkInternetConnection`

- **Descrição:** Este método tenta estabelecer uma conexão com o Google e verifica se a resposta do servidor é bem-sucedida (código 2xx), indicando uma conexão ativa.

- **Retorna:** `true` se a conexão com a internet estiver ativa, `false` caso contrário.

- **Exemplo de Uso:**
  ```java
  if (CheckInternet.checkInternetConnection()) {
      System.out.println("Conectado à internet.");
  } else {
      System.out.println("Sem conexão com a internet.");
  }
  ```

## Mensagens de Saída

O método `checkInternetConnection` fornece mensagens informativas para cada passo do processo. Aqui estão as mensagens possíveis:

- "Verificando conexão com a internet..." - Indica que o método está tentando verificar a conexão com a internet.
- "Conectado à internet" - Indica que a conexão com a internet está ativa.
- "Sem conexão com a internet" - Indica que não há uma conexão ativa com a internet.
- "Erro ao verificar a conexão com a internet" - Indica que ocorreu um erro ao tentar verificar a conexão com a internet.

Este código pode ser incorporado a sistemas ou aplicativos para garantir que haja conectividade antes de realizar operações dependentes da internet. É especialmente útil para fornecer feedback aos usuários sobre a disponibilidade da conexão.
