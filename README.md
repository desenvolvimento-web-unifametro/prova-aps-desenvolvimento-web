# prova-aps-desenvolvimento-web


🛠️ Como Enviar o Código (Passo a Passo com Git no VS Code)
Para garantir que seu arquivo seja enviado para o local correto, siga exatamente este passo a passo.

Crie uma pasta no seu computador

Exemplo: Crie uma pasta chamada ProjetoAPS.

Abra esta Pasta "Pai" no VS Code

Abra o VS Code.

Vá em "Arquivo" > "Abrir Pasta..." (ou "File" > "Open Folder...").

Selecione a pasta que você acabou de criar (a pasta ProjetoAPS, no nosso exemplo).

Abra o Terminal Integrado

Com a pasta ProjetoAPS aberta no VS Code, vá ao menu superior e clique em "Terminal" > "Novo Terminal".

O terminal abrirá automaticamente no caminho correto (ex: C:\...\Documentos\ProjetoAPS>).

Clone o Repositório Dentro da Pasta Agora, no terminal que acabou de abrir, digite o comando para clonar (baixar) o repositório da turma:

Bash

git clone [https://github.com/desenvolvimento-web-unifametro/prova-aps-desenvolvimento-web.git](https://github.com/desenvolvimento-web-unifametro/prova-aps-desenvolvimento-web.git)
Entre na Pasta que foi Clonada (Passo Crítico!) O Git acabou de criar uma nova subpasta chamada prova-aps-desenvolvimento-web. Você precisa entrar nela. Digite no terminal:

Bash

cd prova-aps-desenvolvimento-web
Atenção: Todos os próximos comandos (add, commit, push) devem ser executados DE DENTRO desta pasta.

Crie seu Arquivo .js Usando a barra lateral do VS Code, crie seu arquivo .js (com o nome padrão obrigatório, ex: map_JoaoSilva_MariaSouza.js) dentro da pasta prova-aps-desenvolvimento-web.

Adicione seu Arquivo ao Git Volte ao terminal e digite:

Bash

git add .
Faça o Commit (Mensagem Padrão) Digite o comando de commit, usando a mensagem padrão obrigatória:

Bash

git commit -m "Nome completo do Aluno 1 e Nome completo do Aluno 2"
Envie para o GitHub Por último, envie suas alterações para a branch main do repositório:

Bash

git push origin main
Verifique! Abra o link do repositório no seu navegador e confirme se o seu arquivo .js apareceu lá com o conteúdo correto.
