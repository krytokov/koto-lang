# Koto Lang

> Uma linguagem simples e declarativa para uso pessoal.

--- 

## Proposito
Uma linguagem criada para declarar e configurar projetos **Rust** de forma rápida, seguindo uma arquitetura simples e modular.

<!-- Exemplo -->
<details>
  <summary>Exemplo simples</summary>

  <br>

  ```koto
  mod server::init <- {
      port - "8080";
  }
  ```
  
  > Aqui enviamos a informação `port` para o módulo `server` e sua funcão `init`.

</details>

<!-- Sintaxe básica -->
<details>
  <summary>Sintaxe básica</summary>

  <br>

  ### Declaração de módulos
  <pre>mod caminho::nome <- {...}</pre>

</details>
