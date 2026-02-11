Questão 01: Você acabou de criar uma pasta chamada projeto-aula. Qual o primeiro
comando para torná-la um repositório Git?
R: _______________________git init____________________________________
Questão 02: Como você verifica qual é o nome de usuário e e-mail que estão
configurados no seu Git atualmente?
R: ___________________git config --local user.name user.email________________________________________
Questão 03: Crie um arquivo chamado notas.txt. Qual o comando para adicionar
apenas este arquivo específico à área de staging?
R: ___________________git add notas.txt.________________________________________
Questão 04: Após adicionar o arquivo, como você faz um commit com a mensagem
"adicionando notas de aula"?
R: ____________________git commit -m 'adicionando notas de aula'_______________________________________
Questão 05: Você modificou o arquivo aula1.md. Como você adiciona essa alteração
e faz o commit em seguida (escreva os dois comandos)?
R: ____________________git add/commit_______________________________________
Questão 06: O professor pediu para remover o arquivo teste.log do projeto (deletar e
avisar ao git). Qual o comando para remover o arquivo e como você faria o commit
dessa remoção? Dica git rm NOMEARQUIVO. PRATIQUE
R: ______________________git rm test.log/commit_____________________________________
Questão 07: Você criou um repositório no GitHub. Como você "CONFIGURA" o
endereço do GitHub para o seu Git local (comando para adicionar o remote origin)?
R: ______________________git remote endereço~~_____________________________________
Questão 08: Sua branch local chama-se master, mas o GitHub exige que seja main.
Qual o comando para renomear essa branch localmente?
R: ______________________git branch -m main_____________________________________
Questão 09: Seu colega subiu uma alteração no GitHub. Qual o comando para você
"puxar" essas novidades para o seu computador?
R: ______________________git pull origin main_____________________________________
Questão 10: Você gerou seu Token no GitHub. Como você atualiza a URL do seu
repositório remoto para incluir esse token e não precisar mais digitar senha?
R: ______________________git remote set-url origin_____________________________________
Desafio Final: Fluxo Completo
Cenário: Você precisa criar um arquivo chamado final.md, escrever "Fim do exercício"
nele, salvar, e enviar para o servidor. Escreva a sequência exata de comandos:
1. (Criar o arquivo no VSCode manualmente)
2. Adicionar: ________git add * _________________________________________
3. Commitar: _________git commit -m 'fim do exercicio'_________________________________________
4. Enviar: ___________git push origin main_________________________________________



fim do exercicio
