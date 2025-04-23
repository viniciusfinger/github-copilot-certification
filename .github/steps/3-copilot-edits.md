## Passo 3: Trabalhando ainda _mais rápido_ com o Copilot Edits

Nas etapas anteriores, utilizamos recursos do Copilot que exigem uma orientação mais próxima e produziram resultados mais localizados. Agora vamos explorar o Copilot Edits, um recurso que permite trabalhar de forma mais abrangente em nosso repositório.

[Copilot Edits](https://code.visualstudio.com/docs/copilot/copilot-edits) é uma sessão de edição de código baseada em IA que realiza alterações em **vários arquivos** utilizando **linguagem natural**, aplicando as edições diretamente no editor, onde você pode revisá-las com o contexto completo do código ao redor.

#### Recursos principais

- **Edição em múltiplos arquivos**: Copilot Edits pode fazer alterações em vários arquivos no seu espaço de trabalho.
- **Fluxo iterativo**: Projetado para rápida iteração, permitindo revisar, aceitar ou descartar código gerado pela IA.
- **Edições diretas**: Exibe o código gerado diretamente no seu editor, proporcionando uma experiência semelhante à revisão de código.
- **Conjunto de trabalho**: Permite definir em quais arquivos as edições serão aplicadas.

#### Como funciona

1. **Definir Contexto**: Selecione arquivos para incluir no conjunto de trabalho.
2. **Fornecer Instruções**: Use linguagem natural para descrever as alterações necessárias.
3. **Revisar Alterações**: Veja as mudanças propostas diretamente no código.
4. **Aceitar ou Descartar**: Revise cada edição sugerida e escolha quais manter.
5. **Iterar**: Se necessário, forneça instruções adicionais para refinar as mudanças.

### :keyboard: Atividade: Use o Copilot para adicionar um novo recurso! :rocket:

1. Se o painel Copilot Chat não estiver visível, reabra-o.

2. Na parte superior esquerda da janela do Copilot Chat, clique no ícone **Copilot Edits** para mudar de modo.

   <img width="200" alt="imagem" src="https://github.com/user-attachments/assets/0b17c5bd-d03b-41b1-b97d-624fcbf8ccd1" />

3. Abra os arquivos relacionados à página web e arraste cada janela do editor (ou arquivo) para o painel de chat, informando ao Copilot para usá-los como contexto:

   - `src/static/app.js`
   - `src/static/index.html`
   - `src/static/styles.css`

   > **Dica:** Você também pode usar o botão **Attach files...** para fornecer outras fontes de contexto, como uma issue do GitHub, a base de código completa ou os resultados de uma janela de terminal.

4. Solicite ao Copilot atualizar o projeto para exibir os participantes atuais das atividades. Aguarde um momento para as sugestões aparecerem e serem aplicadas:

   ```prompt
   Olá Copilot, você poderia editar a área onde as atividades são listadas no site para mostrar quais participantes já estão inscritos naquela atividade?
   ```

   - Um ícone extra aparecerá ao lado dos nomes dos arquivos e das janelas do editor indicando edições sugeridas.
   - Um painel de edições sugeridas surgirá no canto inferior direito da janela do editor, oferecendo controles para navegar pelas alterações recomendadas.

5. Antes de aceitar as mudanças, confira novamente o site e verifique se tudo foi atualizado corretamente. Aqui está um exemplo de um cartão de atividade atualizado. Você pode precisar reiniciar o aplicativo ou atualizar a página.

   > **Nota:** Seu cartão de atividade pode estar diferente. O Copilot nem sempre produz resultados idênticos.

   <details>
   <summary>Precisando de ajuda? 🤷</summary><br/>
   Se o site não carregar, confira:

   - Reinicie o depurador do VS Code para garantir que a última versão do site esteja sendo exibida.
   - Se esqueceu a URL ou fechou a janela, revise o passo 1.
   - Tente atualizar a página com força ou abrir em uma janela privada para baixar uma cópia nova.

   </details>

6. Agora que as mudanças estão confirmadas, use o painel para percorrer cada edição sugerida e clique em **Keep** para aplicá-las.

   > **Dica:** Você pode aceitar as mudanças diretamente, modificá-las ou fornecer instruções adicionais usando a interface do chat.

7. Com nosso novo recurso concluído, faça o **commit** e envie (**push**) as alterações para o GitHub.

8. Aguarde um momento para Mona verificar seu trabalho, fornecer feedback e compartilhar a lição final. Está quase lá!

<details>
<summary>Encontrando problemas? 🤷</summary><br/>

Se não receber feedback, verifique:

- Se você enviou corretamente as mudanças na pasta `src/static/` para a branch `accelerate-with-copilot` e sincronizou com o GitHub.
- Caso Mona identifique um erro, faça a correção e envie novamente as alterações. Mona verificará quantas vezes forem necessárias.

</details>

