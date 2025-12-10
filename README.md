# 💰 Sistema Financeiro Condomínio (v1.4)

## Descrição do Projeto

O **Sistema Financeiro Condomínio** é uma aplicação web de página única (Single Page Application - SPA) desenvolvida em HTML, CSS e JavaScript puro, projetada para auxiliar síndicos e administradores na gestão financeira simplificada de condomínios.

A ferramenta permite o registro de receitas e despesas, o acompanhamento do balanço mensal, a gestão de contas em atraso e a visualização de dados através de gráficos interativos. Por ser um único arquivo HTML, é extremamente portátil e fácil de usar, sem a necessidade de um servidor ou banco de dados complexo.

## Funcionalidades Principais

O sistema é dividido em abas de navegação para organizar as seguintes funcionalidades:

| Seção | Objetivo |
| :--- | :--- |
| **Resumo Mensal** | Visualização do balanço financeiro (Receita Total, Despesa Total e Saldo) e gráficos de acompanhamento. |
| **Receitas** | Cadastro, listagem e exclusão de todas as entradas financeiras do condomínio (Cotas, Multas, etc.). |
| **Despesas** | Cadastro, listagem e exclusão de todos os gastos do condomínio (Água, Energia, Manutenção, etc.). |
| **Contas Bancárias** | Registro e acompanhamento dos saldos de Poupança, Aplicação e Fundo de Reserva. |
| **Contas em Atraso** | Gestão dos moradores com cotas em atraso, incluindo valor e dias de atraso. |
| **Configurações** | Cadastro das informações básicas do condomínio (Nome, Endereço, Contato). |

### Recursos Adicionais

*   **Gráficos Interativos:** Utiliza Chart.js para exibir a evolução diária do fluxo de caixa, a composição de receitas e despesas, e a evolução anual dos saldos bancários.
*   **Exportação para PDF:** Geração de um demonstrativo financeiro mensal em formato PDF (via jsPDF).
*   **Backup e Restauração:** Funcionalidades para salvar e carregar todos os dados do sistema através de um arquivo JSON.
*   **Persistência Local:** Todos os dados são armazenados no navegador do usuário (`localStorage`).

## Tecnologias Utilizadas

*   **HTML5:** Estrutura da aplicação.
*   **CSS3:** Estilização (estilos embutidos no arquivo).
*   **JavaScript (Vanilla JS):** Lógica de negócios e manipulação do DOM.
*   **Chart.js:** Biblioteca para criação de gráficos e visualizações de dados.
*   **jsPDF:** Biblioteca para geração de documentos PDF.
*   **html2canvas:** Biblioteca auxiliar para captura de elementos HTML.

## Como Usar

Por ser um arquivo HTML de página única, a utilização é extremamente simples:

1.  **Download:** Baixe o arquivo `SistemaFinanceiroCondominio_v.1.4.html`.
2.  **Execução:** Abra o arquivo diretamente no seu navegador web (Chrome, Firefox, Edge, etc.).
3.  **Uso:** Comece a inserir as informações financeiras nas abas correspondentes.

**Importante:** Os dados são salvos automaticamente no seu navegador. Para garantir a segurança e portabilidade dos seus dados, utilize a função **"Backup"** regularmente.

## Estrutura do Projeto

O projeto consiste em um único arquivo:

```
.
└── SistemaFinanceiroCondominio_v.1.4.html
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir *issues* ou enviar *pull requests* para melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE.md](LICENSE.md) (a ser criado) para mais detalhes.
