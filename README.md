# Desafio Técnico - API de Visualização de Perfil GitHub

## Contexto
Você foi contratada para criar uma aplicação que permita ao usuário pesquisar e visualizar informações básicas de um perfil público do GitHub. O principal objetivo é que você desenvolva uma API que consulte os dados do GitHub e os exponha de forma organizada para que possam ser consumidos por um frontend simples.

## Descrição do Problema

### Backend
Desenvolva uma API que:

1. **Endpoint para Buscar Perfil de Usuário**: Um endpoint que permita buscar as informações de um perfil público do GitHub baseado no username.
   - O endpoint deve receber o username como parâmetro.
   - Deve retornar as seguintes informações:
     - Nome do usuário
     - Foto de perfil
     - Bio
     - Número de repositórios públicos
     - Número de seguidores

3. **Tratamento de Erros**: A API deve lidar com cenários como:
   - Username inexistente.
   - Falhas de conexão com a API do GitHub.

### Frontend
Desenvolva um frontend simples que consuma a API que você desenvolveu:

1. **Busca de Perfil**: Permita ao usuário inserir um username e exiba as informações retornadas pela API.
2. **Interface Simples**: Não há necessidade de um design elaborado; o foco deve ser na funcionalidade.

## Requisitos
- **Backend**: Pode ser desenvolvido em Java (usando Spring Boot), Python, Node.js, ou qualquer outra tecnologia com a qual você se sinta confortável.
- **Frontend**: Pode ser desenvolvido em qualquer framework ou biblioteca de sua escolha (ex: Angular, React, Vue, etc.).
- **API GitHub**: Utilize a [API pública de usuários do GitHub](https://docs.github.com/en/rest/users/users#get-a-user) para buscar as informações.
- **Teste Automatizados**: Se possível, inclua testes unitários ou de integração para garantir que a API funcione corretamente.
- **Entrega**: Compartilhe o código via GitHub. Faça um fork deste repositório, desenvolva sua solução e crie uma Pull Request (PR) no final final.

## O que será avaliado
- **Funcionalidade do Backend**: Se a API retorna as informações corretas e lida bem com erros.
- **Estrutura e Organização do Código**: Clareza e manutenção do código.
- **Testes**: Testes automatizados serão considerados um diferencial.
- **Interface Simples**: A interface deve ser funcional e fácil de usar, mas o foco principal é a API.

## O que NÃO será avaliado
- **Design da Interface**: Não é necessário um design elaborado para o frontend. Foque na funcionalidade, e não na estética.
- **Persistência em Banco de Dados**: Não há necessidade de persistir os dados, caso ache necessário pode ser em memória.
- **Completar 100% da Solução**: Não estamos avaliando se você conseguiu finalizar a solução por completo. Nossa expectativa é ver o que foi feito até agora e entender a qualidade do que foi entregue.

## Instruções
1. Faça um fork deste repositório para a sua conta do GitHub.
2. Desenvolva a sua solução dentro do tempo limite de 3 horas.
3. Após completar, crie uma Pull Request (PR) com a sua solução.
4. Prepare-se para uma conversa descontraída sobre a sua solução com o Tech Lead, onde discutiremos suas escolhas técnicas e exploraremos outras possíveis abordagens.

## Dicas
- Foque na qualidade e funcionalidade da API.
- Sinta-se à vontade para usar qualquer tech stack com a qual você se sinta mais confortável.
- Pesquisa na internet é permitida e encorajada. Utilize todas as ferramentas disponíveis para você, como Google, Stack Overflow, GitHub Copilot, ou ChatGPT.

![Challenge Accepted](https://c.tenor.com/Jcj-pVqCYTgAAAAC/challenge-accepted.gif)

Boa sorte!