#  Product-Registration-System: Gestão de Inventário com Java Swing

Este projeto consiste em uma ferramenta de gerenciamento de produtos e categorias, desenvolvida para automatizar o controle de estoque de forma ágil e intuitiva. O sistema utiliza uma interface gráfica (GUI) para facilitar a interação do usuário final com as operações de backend.

## Objetivo
O objetivo foi construir uma aplicação desktop que seguisse os princípios do Java para gerenciar um fluxo completo de produtos. O sistema precisava validar dados críticos, como preços financeiros e tamanho de descrições além de organizar tudo em categorias dinâmicas para facilitar a busca e filtragem.

## Pipeline de Desenvolvimento
O projeto foi estruturado seguindo o padrão de separação de responsabilidades (View, Repository e Model):

* **Modelagem de Dados:** Criação de classes (`Produto` e `Categoria`) com encapsulamento rigoroso e métodos fluentes para construção de objetos.
* **Persistência em Memória (Repository):** Implementação de repositórios centrais utilizando `Vector` para garantir a integridade dos dados durante a execução do programa.
* **Interface Gráfica (View):** Desenvolvimento de uma UX simplificada utilizando `JOptionPane` para entrada de dados, seleção de listas e mensagens de feedback ao usuário.

## Tecnologias e Ferramentas Utilizadas

* **Linguagem Principal:** Utilizei Java para aproveitar recursos modernos da linguagem e garantir a robustez do sistema.
* **Interface do Usuário:** Utilizei a biblioteca **Swing** (`JOptionPane`) para criar uma interface desktop que não depende de terminal para a interação do usuário.
* **Arquitetura de Dados:** Apliquei o padrão **Repository**, separando a lógica de negócio do armazenamento de dados, o que torna o código muito mais fácil de manter e testar.
* **Manipulação de Objetos:** Utilizei a **Stream API** do Java para realizar filtragens rápidas e eficientes na busca de produtos e categorias.

---

## Estrutura do Sistema
> **Arquitetura: MVC (Model-View-Controller) simplificado**

## Como rodar este projeto

```bash
# Clone o repositório
git clone [https://github.com/isacbrs/Product-Registration-System.git](https://github.com/isacbrs/Product-Registration-System.git)

# Entre na pasta do projeto
cd Product-Registration-System

# Execute a classe principal (App.java) em sua IDE (VS Code, IntelliJ, etc)
