# Repositório da Disciplina de Programação Web

Este repositório contém todos os trabalhos práticos desenvolvidos na disciplina de Programação Web, abordando desde conceitos básicos de HTML e CSS até a construção de aplicações completas com o framework Ruby on Rails.

## 💻 Tecnologias e Conceitos Abordados

Ao longo da disciplina e dos projetos, foram utilizadas as seguintes tecnologias e conceitos:

* **Frontend:** HTML5 (Tags Estruturais), CSS3, JavaScript (ES6+), JQuery, AJAX, JSON
* **Backend:** Ruby, Ruby on Rails
* **Banco de Dados:** ActiveRecord (ORM), Relações (1x1, 1xN, NxN)
* **Estrutura de Dados:** XML
* **Ferramentas:** Git, GitHub, Rake (Testes)

## 📂 Estrutura do Repositório

O repositório está organizado em pastas, uma para cada trabalho desenvolvido:

* **/Trabalho1-PaginaPessoal**: Solução do T1, focada em HTML5 e CSS3.
* **/Trabalho2-ActiveRecord**: Solução do T2, com um script em Ruby para manipulação de banco de dados.
* **/Trabalho3-ProcessadorGrafico**: Solução do T3, utilizando JavaScript e Canvas para manipulação de formas.
* **/Trabalho4-VisualizadorGrade**: Solução do T4, para visualização de históricos acadêmicos com JS e XML.
* **/Trabalho5-AplicacaoRails**: Solução do T5, uma aplicação web completa em Ruby on Rails.

## 🚀 Trabalhos Desenvolvidos

Abaixo está a descrição detalhada de cada um dos trabalhos.

### Trabalho 1: Página Pessoal (HTML5/CSS)

* **Objetivo:** Criar uma página pessoal estática utilizando apenas HTML5 e CSS3, com foco no uso de tags estruturais semânticas.
* **Características:**
    * Layout dividido em duas seções (menu à esquerda e conteúdo à direita).
    * Hiperlinks no menu que atualizam o conteúdo principal.
    * Proibido o uso de `<iframe>` ou `<frame>`.
    * Incentivado o uso de tags como `<header>`, `<nav>`, `<main>`, `<article>`, e `<footer>` em vez de `<div>`.

### Trabalho 2: Banco de Dados com Ruby e ActiveRecord

* **Objetivo:** Criar um programa em Ruby para gerenciar um banco de dados via linha de comando, utilizando o ActiveRecord para mapeamento objeto-relacional.
* **Características:**
    * Implementação de relações: **um-para-um**, **um-para-muitos** e **muitos-para-muitos**.
    * Operações de **inclusão**, **alteração**, **exclusão** e **listagem** de registros via linha de comando.
    * Exemplo de sintaxe: `insere pessoas last_name="Svendson" first_name="Tove"`.
    * O ActiveRecord gerencia exclusões em cascata automaticamente.

### Trabalho 3: Processador de Retas e Polígonos (JavaScript/Canvas)

* **Objetivo:** Desenvolver uma aplicação interativa para criar e manipular formas geométricas (retas e polígonos) no Canvas do HTML5.
* **Características:**
    * **Mover reta:** Arrastar o centro da reta para movê-la.
    * **Redimensionar reta:** Arrastar uma das extremidades para redimensioná-la.
    * **Dividir reta:** Clicar com o botão direito para dividir uma reta em duas.
    * **Gerar Polígono:** Criar um polígono regular (3 a 8 lados) e aplicar as mesmas manipulações a cada um de seus segmentos.

### Trabalho 4: Visualizador de Grade Curricular (JS/XML/JSON)

* **Objetivo:** Criar um visualizador da grade curricular que exibe o histórico de alunos de forma interativa.
* **Características:**
    * **Visualização em Grade:** As disciplinas são exibidas em um layout de linhas e colunas.
    * **Status por Cor:** Cada disciplina é colorida de acordo com o status do aluno (Aprovado, Reprovado, Matriculado, etc.).
    * **Popup de Informações (Clique Esquerdo):** Exibe detalhes da última vez que a disciplina foi cursada (nota, frequência, ano/semestre).
    * **Histórico Completo (Clique Direito):** Mostra todas as vezes que o aluno cursou aquela disciplina.
    * **Busca por RA:** Campo para buscar o histórico de um aluno específico.

### Trabalho 5: Aplicação Web Completa com Rails

* **Objetivo:** Desenvolver uma aplicação web completa utilizando o framework Ruby on Rails.
* **Características:**
    * **Modelo de Dados:** Reutiliza as restrições do Trabalho 2 (relações 1x1, 1xN, NxN), mas com gerenciamento via interface web.
    * **Views (CRUD):** Telas para inserir, alterar e excluir registros das tabelas do banco de dados.
    * **Autenticação de Usuário:** Sistema de login com dois níveis de acesso:
        * **Administrador:** Acesso total ao CRUD.
        * **Usuário:** Apenas consulta os registros.
    * **Testes:** Presença de um framework de testes (executável com `rake test`).
    * **JavaScript/JQuery:** Uso de scripts para melhorar a interatividade.

## 🛠️ Como Utilizar

Para clonar este repositório e ter acesso a todos os trabalhos, utilize o seguinte comando:

```bash
git clone [https://github.com/EduCNeves/progweb.git](https://github.com/EduCNeves/progweb.git)
```
Cada pasta de trabalho contém seu próprio código-fonte. Para instruções específicas de execução (especialmente para os trabalhos 2 e 5), consulte os arquivos `README.md` dentro de cada diretório.

## 👨‍💻 Autor

* **Eduardo Neves**
    * GitHub: [@EduCNeves](https://github.com/EduCNeves)

---
