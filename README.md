# 🖼️ Sistema de Galeria de Imagens

Um sistema web completo para upload, gerenciamento, pesquisa e visualização de imagens. O projeto conta com autenticação de usuários via JWT, validação de arquivos e um sistema de busca avançado por tags e categorias.

## 📋 Requisitos Funcionais (RF)

Abaixo estão descritas as funcionalidades que compõem o sistema, divididas por módulos:

### 🔐 Módulo de Autenticação e Usuários
- **RF01** - O sistema deve permitir que um visitante crie uma conta informando nome, e-mail e senha.
- **RF02** - O sistema deve impedir o cadastro de um e-mail já existente.
- **RF03** - O sistema deve permitir que um usuário cadastrado se autentique com e-mail e senha.
- **RF04** - O sistema deve emitir um token de acesso (JWT) após autenticação bem-sucedida.
- **RF05** - O sistema deve permitir que o usuário autenticado encerre sua sessão (logout).

### 📤 Módulo de Upload e Validação
- **RF06** - O sistema deve permitir que o usuário autenticado publique uma nova imagem, informando nome, tags e arquivo.
- **RF07** - O sistema deve validar o formato da imagem (apenas PNG, JPEG e GIF) e o tamanho do arquivo antes de concluir o envio.

### 🔍 Módulo de Busca e Visualização
- **RF08** - O sistema deve permitir que o usuário pesquise imagens filtrando por nome, tag e/ou extensão.
- **RF09** - O sistema deve exibir os resultados das buscas em formato de galeria, detalhando: nome da imagem, extensão, tamanho e data de upload.
- **RF10** - O sistema deve permitir a visualização da imagem em tamanho real quando o usuário clicar em sua miniatura (thumbnail).

### 🔔 Módulo de Feedbacks
- **RF11** - O sistema deve notificar o usuário (via alertas ou toast notifications) sobre o sucesso ou a falha de cada operação realizada.

---

*Documentação gerada para orientar o desenvolvimento e as etapas de testes (QA) da aplicação.*
