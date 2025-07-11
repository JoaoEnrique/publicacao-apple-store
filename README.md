# Manual de como publicar na Apple Store
Documentação criada para os alunos e para a Fatec Zona Leste publicar seus aplicativos 

Documentação para a Play Store: https://github.com/JoaoEnrique/publicacao-play-store

Link da Apple Store Connect, onde os apps são gerenciados: https://appstoreconnect.apple.com

# Administrador/Fatec
É necessário que a Fatec crie os aplicativos para os alunos gerenciarem, pois apenas administradores podem criar o Bundle ID (identificador único do app usado no build, ex: com.fateczl.nomeapp), que é um requisito para a criação do aplicativo.

### Criar Bundle ID
Para isso, acesse a conta de desenvolvedor em: https://developer.apple.com/account e na opção do meio em "Certificates, IDs & Profiles", clique em "Identifiers".

<img src="./img/Imagem11.png?v=2">

Clique no ícone "+" para adicionar um novo Bundle ID.

<img src="./img/Imagem7.png?v=1">

Deixe marcado a primeira opção e clique em continuar. Depois deixe novamente a primeira opção marcada e clique em continuar mais uma vez.
<img src="./img/Imagem8.png?v=1">
<img src="./img/Imagem9.png?v=1">

Adicione uma descrição para o App ID e o valor do Bundle ID, como: com.fateczl.nomeapp 

É possível adicionar essas informações, podendo alterar depois:

- Capabilities (Capacidades): São funcionalidades que seu app pode usar, como câmera, notificações push, ou iCloud. Você ativa essas capacidades para que o app tenha permissão para usar esses recursos.

- App Services (Serviços do app): São serviços específicos que seu app pode utilizar, como Apple Pay, Game Center, ou CloudKit, que facilitam funcionalidades avançadas.

- Capability Requests (Solicitações de capacidade): São os pedidos que seu app faz para usar alguma capacidade, e que precisam ser aprovados pela Apple durante a submissão para garantir que o app tem autorização para usar esses recursos.

<img src="./img/Imagem10.png?v=1">

## Criar App
A após ter criado o Bundle ID, é preciso criar o app (é possível adicionar permissão para os alunos criarem o aplicativo, portanto apenas a etapa de criação do Bundle ID é preciso ser feito pela Fatec).

Acesse a conta em: https://developer.apple.com/account e selecione em "App Store Connect" a primeira opção, "Apps".

<img src="./img/Imagem13.png?v=1">
<br>

Clique no ícone azul para adicionar um aplicativo

<img src="./img/Imagem12.png?v=1">
<br>

Preencha todas as informações que foram solicitadas

<img src="./img/Imagem14.png?v=1">
<br>

# Alunos
Manual para os alunos aceitarem o convite e gerenciarem os aplicativos

### Aceitar convite
Ao abrir o link do convite, é necessário criar uma conta na Apple se não tiver. Preecnha todos os dados e clique em Continuar, confirme seu email e número de telefone. É possível e provavel que de erro. Você pode tentar novamente ou criar uma conta por um dispositivo iOS ou MacOS, que facilita na criação. por fim, aceite os termos de uso.

<img src="./img/Imagem1.png?v=1">
<img src="./img/Imagem2.png?v=1">
<img src="./img/Imagem3.png?v=1">
<img src="./img/Imagem4.png?v=1">

### Apps
Após aceitar o convite, você verá uma tela como essa, com os aplicativos que você tem acesso no [Apple Store Connect](https://appstoreconnect.apple.com/apps)

<img src="./img/Imagem5.png?v=1">
<br>

Ao selecionar o aplicativo, é apresentado a tela de configuração do app que contém a lista de passos para a publicação na Apple Store

<img src="./img/Imagem6.png?v=1">

### Plataformas
Na parte superior direita do aplicativo é listado todas as plataformas selecionadas para seu app (iOS, macOS, tvOS ou visionOS) e em cada uma é possível adicionar captura de telas e descrições sobre o aplicativo.

<img src="./img/Imagem15.jpeg?v=1">

### Visualizações e capturas de tela
É aqui que você vai adicionar as capturas de telas para a plataforma selecionada 

As capturas de tela devem estar no formato JPG ou PNG e no espaço de cores RGB. As visualizações de aplicativos devem estar no formato M4V, MP4 ou MOV e não podem exceder 500 MB. [Saiba Mais](https://developer.apple.com/help/app-store-connect/manage-app-information/upload-app-previews-and-screenshots)

<img src="./img/Imagem16.png?v=1">
<img src="./img/Imagem18.png?v=1">

Mais abaixo, é preciso aidionar as informações do seu aplicativo. Nenhuma dessas informações é obrigatória.

#### Texto promocional:
O texto promocional permite que você informe os visitantes da App Store sobre os recursos atuais do aplicativo sem exigir um envio atualizado. Esse texto aparecerá acima da sua descrição na App Store para clientes com dispositivos com iOS 11 ou posterior e macOS 10.13 ou posterior.

#### Descrição
Uma descrição do seu aplicativo, detalhando os recursos e funcionalidades.

#### Keywords
Inclua uma ou mais palavras-chave que descrevam seu aplicativo. As palavras-chave tornam os resultados de pesquisa da App Store mais precisos. Separe as palavras-chave com uma vírgula em inglês, uma vírgula em chinês ou uma mistura de ambas.

#### URL de suporte
Uma URL com informações de suporte para seu aplicativo. Isso aparece na página do produto do seu aplicativo assim que você lança seu aplicativo na App Store.

#### Marketing URL
Um URL com informações de marketing sobre seu aplicativo. Este URL ficará visível na App Store.

#### Versão
A versão do aplicativo que você está adicionando. A numeração deve seguir as convenções de controle de versão de software.

#### Direitos autorais
O nome da pessoa ou entidade que detém os direitos exclusivos do seu aplicativo, precedido pelo ano em que os direitos foram obtidos (por exemplo, "2008 Acme Inc."). Não forneça uma URL.

#### Arquivo de cobertura de aplicativo de roteamento
Especifique as regiões geográficas compatíveis com seu aplicativo. O arquivo deve estar no formato .geojson e pode conter apenas um elemento MultiPolygon. [Saiba Mais](https://developer.apple.com/help/app-store-connect/reference/platform-version-information)

<img src="./img/Imagem19.png?v=2">

### Clipe de Aplicativo
Não é obrigatório. Permite ao usuário acessar uma parte do app sem precisar instalá-lo completamente. Para isso, é necessário primeiro enviar uma compilação que contenha o clipe. Após o envio, é possível adicionar uma imagem de cabeçalho no formato JPG ou PNG (1800x1200 px), um subtítulo com até 56 caracteres descrevendo a ação principal do clipe e selecionar a ação desejada (como fazer um pagamento ou reserva). Quando tudo estiver configurado corretamente, o link do clipe será gerado automaticamente para ativação via Safari.

<img src="./img/Imagem20.png?v=1">

### Clipe de Aplicativo
Não é obrigatório. Capturas de tela específicas para aplicativos que usam iMessage.

<img src="./img/Imagem21.png?v=1">

### Build
Mostra todos os buids que você subiu no seu aplicativo.
<img src="./img/Imagem22.png?v=1">

Se você ainda não subiu, terá essa tela
<img src="./img/Imagem23.png?v=1">

### Game Center (Central de Jogos)
Marque essa opção se o seu aplicativo for um jogo

        O Game Center é a plataforma da Apple que permite integrar funcionalidades sociais e competitivas aos aplicativos de jogos, como rankings, conquistas, partidas multiplayer e perfis de jogadores. Ele melhora a experiência do usuário ao permitir que jogadores comparem pontuações, desafiem amigos e acompanhem seu progresso entre dispositivos Apple.


### Informações de revisão do aplicativo
Se o seu aplicativo tiver alguma funcionalidade restrita por meio de login, é necessário informar um login e senha de teste para a Apple analisar, adicionar informações adicionais (se houver) para realizar o login e informações de contato caso a Apple encontre algum problema.

Sobre o anexo:

        Você pode anexar documentação específica do aplicativo, vídeos de demonstração e outros itens para ajudar a evitar atrasos durante o processo de revisão do aplicativo. Certifique-se de usar arquivos com as seguintes extensões: .pdf, .doc, .docx, .rtf, .pages, .xls, .xlsx, .numbers, .zip, .rar, .plist, .crash, .jpg, .png, .mp4 ou .avi.

<img src="./img/Imagem24.png?v=1">

### Lançamento da versão da App Store
Você decide se o aplicativo vai ser lançado automaticamente ou manualmente ao ser aprovado pela Apple. 

<img src="./img/Imagem25.png?v=1">
