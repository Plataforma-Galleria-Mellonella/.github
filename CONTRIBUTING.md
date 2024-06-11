# Contribuindo para Plataforma G. mellonella

Obrigado por seu interesse em contribuir para a Plataforma G. mellonella! Estamos animados para trabalhar com você. Este documento descreve como você pode contribuir para o projeto.

## Código de Conduta

Por favor, leia e siga nosso [Código de Conduta](CODE_OF_CONDUCT.md) para garantir um ambiente acolhedor e respeitoso para todos.

## Relatando Problemas

Se você encontrar um bug ou tiver uma sugestão para uma nova funcionalidade, por favor, abra uma issue seguindo estas etapas:

1. Verifique se a issue já foi relatada buscando em [Issues](https://github.com/PlataformaGalleriaMellonella/NOME_REPOSITORIO/issues).
2. Se não encontrar, abra uma nova issue e forneça o máximo de detalhes possível:
   - Descreva o problema ou a funcionalidade sugerida.
   - Forneça passos para reproduzir o problema, se aplicável.
   - Inclua qualquer informação relevante, como mensagens de erro ou capturas de tela.

## Solicitando Novas Funcionalidades

Para solicitar uma nova funcionalidade:

1. Abra uma issue de `Nova funcionalidade` seguindo o [template de solicitação de funcionalidade](https://github.com/PlataformaGalleriaMellonella/NOME_REPOSITORIO/issues/new?template=feature_request.md).
2. Descreva a funcionalidade detalhadamente e explique por que seria útil para o projeto.

## Configurando o Ambiente de Desenvolvimento

Para configurar o ambiente de desenvolvimento localmente:

1. Clone o repositório:

   ```bash
   git clone https://github.com/PlataformaGalleriaMellonella/NOME_REPOSITORIO.git
   cd NOME_REPOSITORIO
   ```
2. Instale as dependências:

    ```bash
    npm install
    ```
3. Configure as variáveis de ambiente, se necessário, de acordo com o arquivo .env.example.

4. Inicie o servidor de desenvolvimento:

    ```bash
    npm start
    ```
5. Você está pronto para começar a desenvolver!


# Enviando Pull Requests

Para enviar uma pull request (PR):

1. Crie um branch para sua contribuição:

    ```bash
    # Caso seja uma nova funcionalidade
    git checkout -b feature/descricao-funcionalidade

    # Caso seja uma resolução de bug
    git checkout -b hotfix/descricao-bug
    ```

2. Faça suas alterações no código e adicione testes, se necessário.

3. Commit suas alterações com uma mensagem de commit clara:

    ```bash
    git commit -m "Descrição clara das alterações"
    ```

4. Envie suas alterações para o seu fork:

    ```bash
    git push origin NOME-DA-BRANCH
    ```

5. Abra uma pull request a partir do seu fork no GitHub.

6. Aguarde a revisão. Fique atento a comentários e faça ajustes conforme necessário.

# Revisão de Código

Todas as pull requests passarão por uma revisão de código. Certifique-se de seguir as melhores práticas de codificação e os padrões do projeto. A revisão de código ajuda a garantir a qualidade e a consistência do código.

# Recursos Adicionais
 - [Wiki do Projeto](https://github.com/PlataformaGalleriaMellonella/NOME_REPOSITORIO/wiki).
 - [Fórum de Discussão](https://github.com/orgs/PlataformaGalleriaMellonella/discussions)