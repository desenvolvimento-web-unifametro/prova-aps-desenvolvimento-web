## 🛠️ Avaliação Prática Supervisionada (APS)

### Tópico: Análise e Aplicação de Métodos JavaScript

### 1. Objetivo da Avaliação

O objetivo desta atividade é avaliar a capacidade do aluno em pesquisar, compreender e demonstrar o uso prático de um método fundamental da linguagem JavaScript, aplicando-o na resolução de um problema concreto.

### 2. Formato e Atribuição

* **Formato:** A atividade será realizada em **duplas**.
* **Atribuição:** A cada dupla será **sorteado 1 (um) método** da lista oficial fornecida abaixo.

### Lista de Métodos para Sorteio


`.map()`, `.filter()`, `.reduce()`, `.forEach()`, `.find()`, `.includes()`, `.findIndex()`, `.some()`, `.every()`, `.push()`, `.pop()`, `.unshift()`, `.shift()`, `.splice()`, `.slice()`, `.join()`, `.toString()`, `.toFixed()`, `Number()`, `Number.parseInt()`, `Number.parseFloat()`, `Number.isNaN()`, `Math.random()`, `Math.floor()`, `Math.ceil()`, `Math.round()`, `Math.max()`, `Math.min()`, `Math.abs()`, `JSON.stringify()`, `JSON.parse()` 

### 3. O que deve ser Entregue (As Duas Etapas)

A avaliação é composta por duas partes obrigatórias: um arquivo de código e uma apresentação oral.

#### Etapa 1: O Código-Fonte (Submissão no GitHub)

O repositório para esta atividade já existe. O link para o repositório é:

`https://github.com/desenvolvimento-web-unifametro/prova-aps-desenvolvimento-web.git`

Cada dupla deverá **enviar seu arquivo `.js`** para a `branch main` deste repositório.

* **Prazo Máximo:** O arquivo deve estar no repositório até o dia **21/11/2025, às 17h00** (horário de Brasília). Envios após este horário não serão considerados.
* **Nome do Arquivo:** Para organização e identificação, o arquivo deve ser nomeado seguindo **obrigatoriamente** o padrão: nomeDoMetodo_NomeAluno1_NomeAluno2.js *(Exemplo: map_JoaoSilva_MariaSouza.js\)*

**Requisitos Críticos do Código:**

1.  **Funcionalidade:** O código deve estar 100% funcional e ser executável.
2.  **Relevância:** O script deve resolver um problema prático e relevante. (Evitem exemplos genéricos como \`[1, 2, 3].map(x => x * 2)\`). Criem um pequeno contexto ou cenário para o problema.
3.  **PROIBIÇÃO DE COMENTÁRIOS:** O arquivo de código **não pode conter nenhum comentário** (\`//\` ou \`/* */\`). A explicação do código será feita **exclusivamente** de forma verbal durante a apresentação.

#### Etapa 2: A Apresentação

A dupla fará uma apresentação oral para a turma sobre o método sorteado.

* **Tempo:** A apresentação deve ter duração de **5 a 10 minutos** (limite máximo).
* **Participação:** **Ambos os integrantes** da dupla devem, obrigatoriamente, apresentar.

**Conteúdo da Apresentação:**

A apresentação deve ser dividida em duas partes:

* **Parte Teórica (Explicação do Método):**
    * O que o método faz?
    * Qual é a sua sintaxe?
    * Quais parâmetros ele aceita?
    * O que ele retorna? (Ex: um novo array, um booleano, um número, etc.)
* **Parte Prática (Análise do Código):**
    * Apresentar o código-fonte (que foi enviado ao repositório).
    * Explicar qual problema prático o código se propõe a resolver.
    * Mostrar como o método sorteado foi utilizado para chegar à solução.

> **Sugestão de divisão:** Um integrante pode focar na parte teórica, enquanto o outro explica a parte prática.

### 4. Entrega e Avaliação

A avaliação da dupla será composta pela soma das duas etapas:

1.  **Entrega do Código:** O upload do arquivo `.js` nomeado corretamente na `branch main` do repositório da turma, respeitando o prazo máximo (21/11, 17h00).
2.  **Apresentação Oral:** A apresentação (Teoria + Prática) na data 21/11/2025.

**Atenção:** É de **responsabilidade total da dupla** verificar no repositório do GitHub se o arquivo subiu corretamente.

---
## 🛠️ Como Enviar o Código (Passo a Passo com Git no VS Code)

Para garantir que seu arquivo seja enviado para o local correto, siga exatamente este passo a passo.

1.  **Crie uma pasta no seu computador**
    * *Exemplo: Crie uma pasta chamada `ProjetoAPS`.*

2.  **Abra esta pasta no VS Code**
    * Abra o VS Code.
    * Vá em "Arquivo" > "Abrir Pasta..." (ou "File" > "Open Folder...").
    * Selecione a pasta que você acabou de criar (a pasta `ProjetoAPS`, no nosso exemplo).

3.  **Abra o Terminal Integrado**
    * Com a pasta `ProjetoAPS` aberta no VS Code, vá ao menu superior e clique em "Terminal" > "Novo Terminal".
    * O terminal abrirá automaticamente no caminho correto (ex: `C:\...\Documentos\ProjetoAPS>`).

4.  **Clone o Repositório Dentro da Pasta**
    Agora, no terminal que acabou de abrir, digite o comando para clonar (baixar) o repositório da turma:
    ```bash
    git clone [https://github.com/desenvolvimento-web-unifametro/prova-aps-desenvolvimento-web.git](https://github.com/desenvolvimento-web-unifametro/prova-aps-desenvolvimento-web.git)
    ```

5.  **Entre na Pasta que foi Clonada (Passo Crítico!)**
    O Git acabou de criar uma nova subpasta chamada `prova-aps-desenvolvimento-web`. Você precisa entrar nela.
    Digite no terminal:
    ```bash
    cd prova-aps-desenvolvimento-web
    ```
    **Atenção:** Todos os próximos comandos (`add`, `commit`, `push`) devem ser executados DE DENTRO desta pasta.

6.  **Crie seu Arquivo .js**
    Crie seu arquivo `.js` (com o nome padrão obrigatório, ex: `map_JoaoSilva_MariaSouza.js`) dentro da pasta `prova-aps-desenvolvimento-web`.

7.  **Adicione seu Arquivo ao Git**
    Volte ao terminal e digite:
    ```bash
    git add .
    ```

8.  **Faça o Commit (Mensagem Padrão)**
    Digite o comando de commit, usando a mensagem padrão obrigatória:
    ```bash
    git commit -m "Nome completo do Aluno 1 e Nome completo do Aluno 2"
    ```

9.  **Envie para o GitHub**
    Por último, envie suas alterações para a `branch main` do repositório:
    ```bash
    git push origin main
    ```

10. **Verifique se seu arquivo esta no repositório!**
    Abra o link do repositório no seu navegador e confirme se o seu arquivo `.js` apareceu lá com o conteúdo correto.
