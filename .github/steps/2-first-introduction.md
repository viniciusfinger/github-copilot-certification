## Passo 2: Trabalhando com o Copilot

Na etapa anterior, o GitHub Copilot nos ajudou a entender o projeto. Só isso já economiza muito tempo, mas agora vamos colocar a mão na massa!

Recentemente descobrimos um bug onde estudantes estão se cadastrando duas vezes na mesma atividade. Isso não é aceitável, então vamos consertar isso!

Infelizmente, recebemos poucas informações sobre esse problema. Portanto, vamos usar o Copilot para encontrar o problema e criar uma solução potencial.

Mas antes, vamos aprender mais sobre o Copilot! 🧑‍🚀

### Como o Copilot funciona?

Você pode pensar no Copilot como um colega de trabalho muito focado. Para que ele seja eficaz, você precisa fornecer contexto e instruções claras (prompts). Além disso, pessoas diferentes são boas em coisas diferentes por causa de suas experiências únicas (modelos).

- **Como fornecer contexto?** No nosso ambiente de programação, o Copilot considera automaticamente o código próximo e as abas abertas. Se estiver usando o chat, você também pode se referir explicitamente a arquivos.

- **Qual modelo escolher?** Para nosso exercício, isso não importa muito. Experimentar modelos diferentes faz parte da diversão! 🤖

- **Como criar prompts?** Ser [explícito e claro](https://learn.microsoft.com/en-us/training/modules/introduction-prompt-engineering-with-github-copilot/2-prompt-engineering-foundations-best-practices) ajuda o Copilot a trabalhar melhor. Diferentemente de sistemas tradicionais, você sempre pode esclarecer seu pedido com prompts adicionais.

### Atividade: Use o Copilot para corrigir o bug de registro

1. Peça ao Copilot sugestões sobre a possível origem do bug. Abra o painel **Copilot Chat** e pergunte:

   ```prompt
   @workspace Os alunos conseguem se inscrever duas vezes em uma atividade. De onde pode estar vindo esse bug?
   ```

2. Sabendo que o problema está no arquivo `src/app.py` e no método `signup_for_activity`, siga a recomendação do Copilot e corrija o problema (semi-manualmente):

   1. No VS Code, abra a aba **Explorer** e o arquivo `src/app.py`.
   2. Role até o método `signup_for_activity`.
   3. Localize o comentário que descreve a adição do estudante. Acima dele parece lógico fazer nossa validação.
   4. Insira o comentário abaixo e pressione enter. O Copilot sugerirá automaticamente uma solução!

      ```python
      # Validar se o aluno já está inscrito
      ```

   5. Pressione `Tab` para aceitar a sugestão do Copilot.

### :keyboard: Atividade: Gere dados de exemplo usando o Copilot 📋

Em novos projetos, é útil ter dados fictícios realistas para testes. O Copilot é excelente nisso, então vamos adicionar atividades adicionais usando o **Inline Chat**.

**Inline Chat** é parecido com o painel **Copilot Chat**, mas com contexto mais específico para linhas ou funções individuais.

1. Abra o arquivo `src/app.py`.
2. Próximo à linha 23, encontre a variável `activities`.
3. Clique com o botão direito sobre as linhas relacionadas e selecione **Copilot → Editor Inline Chat**.
4. Insira o prompt abaixo e envie:

   ```prompt
   Adicione mais 2 atividades esportivas, 2 artísticas e 2 intelectuais.
   ```

5. Após o Copilot sugerir mudanças diretamente no código, revise e clique em **Accept**.

### :keyboard: Atividade: Use o Copilot para descrever nosso trabalho 💬

Ótimo trabalho corrigindo o bug e expandindo as atividades! Vamos agora enviar nosso trabalho para o GitHub novamente com ajuda do Copilot!

1. Na barra lateral esquerda, selecione a aba `Source Control`.
2. Localize o arquivo `app.py` e pressione o sinal `+` para preparar suas alterações.
3. Acima das alterações, encontre o campo **Message**, mas não escreva nada ainda.
4. Clique no botão **Generate Commit Message with Copilot** (ícone com brilhos).
5. Clique em **Commit** e depois em **Sync Changes** para enviar ao GitHub.
6. Aguarde Mona verificar seu trabalho, fornecer feedback e compartilhar a próxima lição.

<details>
<summary>Encontrando problemas? 🤷</summary><br/>

Se não houver feedback, verifique:
- Se você enviou corretamente as alterações no arquivo `src/app.py` para a branch `accelerate-with-copilot`.

</details>

