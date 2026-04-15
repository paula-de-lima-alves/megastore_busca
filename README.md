# Sistema de Busca Otimizado para Catálogo de Produtos - MegaStore

##  Descrição do Projeto
Este projeto implementa um sistema de busca eficiente para um catálogo de produtos, utilizando estruturas de dados como tabela hash (HashMap) e grafos para recomendação de produtos relacionados.

O objetivo é melhorar a velocidade de busca e oferecer recomendações inteligentes para os usuários.

---

##  Tecnologias Utilizadas
- Rust
- HashMap (Tabela Hash)
- Grafos

---

##  Como Executar

1. Abra o terminal na pasta do projeto
2. Execute o comando:

cargo run

---

##  Como Executar os Testes

cargo test

---

##  Funcionalidades

- Busca rápida de produtos por nome
- Indexação eficiente com HashMap
- Recomendação de produtos relacionados usando Grafos

---

##  Estruturas de Dados Utilizadas

### Tabela Hash (HashMap)
Utilizada para armazenar os produtos e permitir buscas rápidas com complexidade O(1).

### Grafos
Utilizados para representar relações entre produtos e gerar recomendações.

---

##  Desempenho e Escalabilidade

O uso de HashMap garante alta performance nas buscas, enquanto os grafos permitem expandir o sistema de recomendação de forma eficiente, mesmo com grande volume de dados.

---

## Arquitetura do Sistema

- SistemaBusca: responsável pela indexação e busca de produtos
- Grafo: responsável pela recomendação de produtos relacionados

---

##  Exemplo de Uso

Buscar produto:
Notebook

Resultado:
Produto encontrado

Recomendações:
- Mouse
- Teclado

---

##  Licença

Projeto acadêmico para fins educacionais.
