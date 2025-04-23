
## Passo 1: Olá, Piloto !

Neste exercício, você utilizará diferentes recursos do GitHub Copilot para trabalhar em um site que permite aos estudantes da Escola Secundária Mergington se inscreverem em atividades extracurriculares. 🎻 ⚽️ ♟️


<img width="600" alt="captura de tela do aplicativo da Escola Secundária Mergington" src="https://github.com/user-attachments/assets/472398fd-1aa1-4084-b443-4e242deb30d9" />

### Atividade: Conheça o projeto usando o Copilot Chat
Para o exercício de hoje, vamos praticar com VS Code em um ambiente de desenvolvimento pré-configurado conhecido como [Codespaces](https://github.com/features/codespaces).

Vamos iniciar nosso ambiente de desenvolvimento, utilizar o Copilot para aprender um pouco sobre o projeto e depois testá-lo.

1. Clique com o botão direito no botão abaixo para abrir a página **Criar Codespace** em uma nova guia. Use a configuração padrão.

   [![Abrir no GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/{{full_repo_name}}?quickstart=1)

2. Confirme que o campo **Repositório** seja sua cópia do exercício, não o original, e clique no botão verde **Create Codespace**.

   - ✅ Sua cópia: `/{{{full_repo_name}}}`
   - ❌ Original: `/Copilot-Workshop-Invillia/skills-getting-started-with-github-copilot`

3. Aguarde um momento enquanto o Visual Studio Code carrega no seu navegador.

4. Na barra lateral esquerda, clique na aba extensões e verifique se as extensões `GitHub Copilot` , `GitHub Actions` e `Python` estão instaladas e habilitadas.

5. No topo do VS Code, clique no **ícone do Copilot** para abrir o painel Copilot Chat.

6. Caso seja sua primeira vez usando GitHub Copilot, você precisará aceitar os termos de uso.

7. Insira o seguinte prompt para pedir ao Copilot que apresente o projeto:

   ```prompt
   @workspace Por favor, explique brevemente a estrutura deste projeto.
   O que devo fazer para executá-lo?
   ```

   > **Nota**: Não é necessário seguir as instruções recomendadas pelo Copilot. Nós já preparamos o ambiente para você.

8. Agora, vamos executar o projeto. Na barra lateral esquerda, selecione a aba `Run and Debug` e clique no ícone **Start Debugging**.

9. Para visualizar a página rodando no navegador, encontre a porta `8000` no painel inferior, guia **Ports**, passe o cursor sobre o link e clique no ícone **Open in browser**.

### Atividade: Peça ajuda ao Copilot para lembrar um comando do terminal 🙋

Agora que estamos familiarizados com o app e sabemos que funciona, vamos pedir ao Copilot ajuda para criar uma nova branch.

1. Retorne ao VS Code.
2. No painel inferior, selecione a guia **Terminal** e clique no sinal de `+` para criar uma nova janela do terminal.
3. Na nova janela do terminal, clique com o botão direito, selecione `Copilot` e depois `Terminal Inline Chat` (ou use o atalho `Ctrl + I` no Windows ou `Cmd + I` no Mac).

4. Pergunte ao Copilot como criar e publicar uma nova branch:

   ```prompt
   Ei, Copilot, como posso criar e publicar uma nova branch do Git?
   ```

5. O Copilot fornecerá algo semelhante ao seguinte comando:

   ```bash
   git checkout -b {nome_da_nova_branch}
   git push -u origin {nome_da_nova_branch}
   ```

   Em seguida, solicite ao Copilot para usar um nome específico:

   ```prompt
   Ótimo! Obrigado, Copilot! Vamos usar o nome da branch "accelerate-with-copilot".
   ```

6. Aperte o botão `Run` para executar o comando diretamente com a ajuda do Copilot.

7. Verifique na barra de status inferior esquerda do VS Code se a branch ativa é `accelerate-with-copilot`. Se sim, você concluiu esta etapa!

8. Com sua branch publicada no GitHub, aguarde que Mona verifique seu trabalho nos comentários e siga para a próxima lição.

<details>
<summary>Encontrando problemas? 🤷</summary><br/>

Se você não recebeu feedback, confira:
- O nome exato da branch criada: `accelerate-with-copilot`.
- Se a branch foi realmente publicada em seu repositório.

</details>
