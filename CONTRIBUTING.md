# Contribuindo para Plataforma G. mellonella

Obrigado por seu interesse em contribuir para a Plataforma G. mellonella! Estamos animados para trabalhar com você. Este documento descreve como você pode contribuir para o projeto.

## Código de Conduta

Por favor, leia e siga nosso [Código de Conduta](CODE_OF_CONDUCT.md) para garantir um ambiente acolhedor e respeitoso para todos.

## Relatando Problemas

Se você encontrar um bug ou tiver uma sugestão para uma nova funcionalidade, por favor, abra uma issue seguindo estas etapas:

1. Verifique se a issue já foi relatada buscando em [Issues do Frontend](https://github.com/PlataformaGalleriaMellonella/pgm-front/issues) ou [Issues do Backend](https://github.com/PlataformaGalleriaMellonella/pgm-back/issues).
2. Se não encontrar, abra uma nova issue e forneça o máximo de detalhes possível:
   - Descreva o problema ou a funcionalidade sugerida.
   - Forneça passos para reproduzir o problema, se aplicável.
   - Inclua qualquer informação relevante, como mensagens de erro ou capturas de tela.

Você pode usar o template de relatar bugs ([Frontend](https://github.com/PlataformaGalleriaMellonella/pgm-front/issues/new?template=bug_report.md) ou [Backend](https://github.com/PlataformaGalleriaMellonella/pgm-back/issues/new?template=bug_report.md)) para facilitar o processo de reportar problemas.

## Solicitando Novas Funcionalidades

Para solicitar uma nova funcionalidade:

1. Abra uma issue de `Nova funcionalidade` seguindo o template de solicitação de funcionalidade ([Frontend](https://github.com/PlataformaGalleriaMellonella/pgm-front/issues/new?template=feature_request.md) ou [Backend](https://github.com/PlataformaGalleriaMellonella/pgm-back/issues/new?template=feature_request.md)).
2. Descreva a funcionalidade detalhadamente e explique por que seria útil para o projeto.

## Configurando o Ambiente de Desenvolvimento

Para configurar o ambiente de desenvolvimento localmente:

1. Clone o repositório:

   ```bash
   # Frontend
   git clone https://github.com/PlataformaGalleriaMellonella/pgm-front.git
   cd pgm-front

   # Backend
   git clone https://github.com/PlataformaGalleriaMellonella/pgm-back.git
   cd pgm-back
   ```

2. Instale as dependências:

   ```bash
   npm install
   ```

3. Inicie o servidor de desenvolvimento:

   ```bash
   npm start
   ```

4. Você está pronto para começar a desenvolver!


# Criando commits e enviando Pull Requests

Para enviar uma pull request (PR):

1. Crie um branch para sua contribuição:

   ```bash
   # Caso seja uma nova funcionalidade
   git checkout -b feature/descricao-funcionalidade

   # Caso seja uma resolução de bug
   git checkout -b bugfix/descricao-bug

   # Caso seja um hotfix
   git checkout -b hotfix/descricao-hotfix

   # Caso seja uma refatoração
   git checkout -b refactor/descricao-refactor
   ```

2. Faça suas alterações no código e adicione testes, se necessário.

3. Para garantir um histórico de commits claro e consistente rode o comando de commit sem mensagem:

   ```bash
   git commit
   ```

   Isso acionará o Husky para rodar o cz (Commitizen), que pedirá a mensagem de commit no escopo correto.

4. Envie suas alterações para o seu fork:

   ```bash
   git push origin NOME-DA-BRANCH
   ```

5. Abra uma pull request a partir do seu fork no GitHub.

6. Aguarde a revisão. Fique atento a comentários e faça ajustes conforme necessário.

# Revisão de Código

Todas as pull requests passarão por uma revisão de código. Certifique-se de seguir as melhores práticas de codificação e os padrões do projeto. A revisão de código ajuda a garantir a qualidade e a consistência do código.

# Recursos Adicionais

- [Fórum de Discussão](https://github.com/orgs/PlataformaGalleriaMellonella/discussions)
