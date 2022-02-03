Projeto "Cópia" Discord ForChat 
Projeto criado na Imersão React da Alura.

A Imersão React desenvolveu um projeto de sala de chat para troca de mensagens entre usuários. Contém uma tela de login, que se comunica com a api do Github para trazer a foto e o nome do usuário.

Após entrar na sala de chat, o usuário consegue enviar mensagens, que são armazenadas em um banco de dados. No caso desse projeto, foi utilizado o Supabase para essa finalidade.

Desafios implementados
Além do conteúdo das aulas, segui com alguns desafios propostos e ideias particulares.

Tema "StarWars"
Na ideia original, o tema era "Matrix". Fomos desafiados a trazer um tema diferente, apliquei um dos meu gosto que np caso Star Wars.

Dados do usuário do Github
Inspirada na ideia dos memes, trouxe alguns dados do Github:

Número de seguidores
Número de pessoas que o user segue


Link do repositório da aplicação: https://github.com/AndersonDotore/projectchat-starwars

Link para ver e testar o projeto: https://projectchat-starwars.vercel.app/


Tecnologias utilizadas
Next
Aplicação criada com NextJS com setup manual.

Aplicamos o next/router para redirecionamento de página entre o login e a página de chat. Isso permite com que a transição entre as páginas seja feita do lado do browser, melhorando a performance de carregamento da aplicação.

@skynexui
A fim de facilitar a estilização dos blocos e acelerar a implementação do projeto, foi utilizado componentes já prontos da SkynexUI, que são facilmente editáveis para personalização.

O Storybook dessa biblioteca permite a visualização de possíveis adaptações, o que facilita ainda mais sua implementação.

Supabase
O Supabase foi usado como um serviço de backend. Ele pode ser usado de várias formas, mas neste projeto foi usado como um database para armazenar e alterar as mensagens enviadas.

Para atualização do chat em tempo real, foi usada a feature de subscribe.

Extremamente fácil de criar, administrar e usar, além de ser de graça!

Contribuição
Esse projeto ainda não está bem estruturado para receber contribuições, mas já criei algumas issues, que registram melhorias e bugs já encontrados.

Caso encontre um bug ou tenha uma nova sugestão de melhoria, sinta-se à vontade para criar uma issue para discutirmos sua implementação!

