# Java F1 POO

Projeto de estudo em Java que usa a Fórmula 1 como exemplo para praticar Programação Orientada a Objetos. Ele cadastra equipes e pilotos, associa cada piloto à sua equipe e exibe o grid no console.

Escolhi a F1 porque o domínio já tem as relações que eu queria treinar: uma equipe tem pilotos, um piloto pertence a uma equipe, e existe uma regra clara (no máximo 2 pilotos por equipe).

## O que pratiquei

Principalmente `enum`, encapsulamento (atributos privados, getters e setters), construtores e modificadores de acesso. Também a associação entre objetos, com um `ArrayList` de pilotos dentro de cada equipe, e o uso de laços e condicionais para montar e exibir o grid.

## Como funciona

Por enquanto são três equipes, cada uma com 2 pilotos:

* Ferrari: Lewis Hamilton e Charles Leclerc
* Mercedes: George Russell e Kimi Antonelli
* Red Bull Racing: Max Verstappen e Isack Hadjar

O `Main` chama a classe `FIA`, que configura as equipes e depois exibe cada uma com seus pilotos:

```text
Main
 └── FIA
      ├── configura as equipes
      └── exibe as equipes
           ├── Ferrari
           │    ├── Lewis Hamilton
           │    └── Charles Leclerc
           ├── Mercedes
           │    ├── George Russell
           │    └── Kimi Antonelli
           └── Red Bull Racing
                ├── Max Verstappen
                └── Isack Hadjar
```

## Estrutura

```text
java-f1-poo/
└── src/
    ├── EquipesF1.java
    ├── FIA.java
    ├── Main.java
    └── Piloto.java
```

O projeto tem também os arquivos da IDE (`.idea` e `JavaF.iml`), que não fazem parte do código.

## Tecnologias

Java, IntelliJ IDEA, Git e GitHub.

## Autor

Rogério Barbosa. Estudando Java, POO e desenvolvimento de software.
