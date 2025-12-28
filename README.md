# Koto Lang

> Uma linguagem simples e declarativa para uso pessoal.

--- 

## Proposito
Uma linguagem criada para declarar e configurar projetos **Rust** de forma rápida, seguindo uma arquitetura simples e modular.

<!-- Exemplo -->
## Exemplo simples

  <br>

  ```koto
  mod server::init <- {
      port - "8080";
  }
  ```

> Aqui enviamos a informação `port` para o módulo `server` e sua funcão `init`.

<!-- Sintaxe básica -->
## Sintaxe básica

<br>

> Declaração de módulos
<pre>mod caminho::nome <- {...}</pre>
<br>

> Atribuição de valor
<pre>chave - valor;</pre>
