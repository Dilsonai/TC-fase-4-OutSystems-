Tech Challenge - Blogging Dinâmico (Filosblog)
Este repositório contém o código-fonte e a documentação técnica do projeto desenvolvido para o Tech Challenge - Fase 4. A aplicação consiste em um sistema de blog dinâmico que diferencia a experiência de uso entre perfis administrativos e perfis de leitura.

🚀 Instruções de Instalação e Execução
Para visualizar e testar o projeto localmente, siga os passos abaixo:

Requisito: É necessário ter o OutSystems Service Studio 11 instalado.

Download: Baixe o arquivo Filosblog.oml presente neste repositório.

Importação: Abra o Service Studio, vá em Module > Open File e selecione o arquivo baixado.

Publicação: Clique no botão 1-Click Publish (botão verde no topo) para publicar o módulo no seu ambiente pessoal.

🛠️ Tecnologias Utilizadas
Plataforma: OutSystems (Desenvolvimento Low-Code).

Banco de Dados: Tabelas relacionais para armazenamento de Posts e controle de usuários.

Lógica de Interface: Uso de variáveis de entrada e parâmetros (IsAdmin) para controle de permissões em tempo real.

🧠 Lógica de Acesso e Navegação
A aplicação foi projetada para garantir segurança e fluidez:

Perfil Cliente (Alun@): Acesso restrito à leitura dos textos. A navegação permite visualizar a lista e os detalhes de um post específico.

Perfil Administrad@r (Profess@r): Mediante validação de senha (credencial '1234'), o sistema habilita o link de edição para posts existentes e o ícone de criação (+) para novos conteúdos.





