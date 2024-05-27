---
# POO - Desafio
---
```mermaid
classDiagram
    class iPhone
           
    class ReprodutorMusical{
        +tocar()
        +pausar()
        +selecionaMusica(String musica)
    }
    class AparelhoTelefonico{
        +ligar(String numero)
        +atender()
        +inicialCorreioVoz()
    }
    class NavegadorNaInternet{
        +exibirPagina(String URL)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorNaInternet

