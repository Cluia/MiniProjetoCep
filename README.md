# MiniProjetoCep
Este é um aplicativo Android desenvolvido em Kotlin utilizando Jetpack Compose, que permite buscar informações de endereço com base no CEP fornecido. O aplicativo realiza a busca através da API ViaCEP e armazena os dados localmente em um banco de dados Room para acesso offline.

Além disso, o aplicativo possui as seguintes funcionalidades:

Entrada do CEP com validação.
Busca de dados de endereço através da API.
Armazenamento e consulta de endereços localmente usando Room Database.
Compartilhamento de informações do endereço.
Navegação entre telas com Jetpack Navigation.

----------------------------------------------------------------------
Funcionalidades Principais

Validação do formato do CEP.
Verificação de conectividade com a internet.
Consulta na API ViaCEP para obter os dados do endereço.
Armazena os endereços no banco de dados local usando Room.
Acesso offline aos endereços previamente consultados.
Permite compartilhar o endereço obtido através de aplicativos como WhatsApp, Email ou outros.

-------------------------------------------------------------------------
Tecnologias Utilizadas
Kotlin: Linguagem de programação principal.
Jetpack Compose: Toolkit para a construção da interface do usuário.
Room Database: Solução para armazenamento local.
Retrofit: Biblioteca para chamadas HTTP.
Coroutines: Gerenciamento de threads e operações assíncronas.
Navigation Component: Gerenciamento de navegação entre telas.

--------------------------------------------------------------------------
Pré-requisitos
Android Studio: Certifique-se de ter a versão mais recente instalada.
SDK mínimo: 21 (Lollipop)
SDK de compilação: 33 ou superior.
Sincronize as dependências do Gradle.
Execute o projeto em um dispositivo ou emulador Android.

--------------------------------------------------------------------------

Como Usar o Aplicativo
Tela Inicial:
Digite um CEP no campo fornecido (ex.: "01001000").
Pressione o botão Buscar Endereço.

Resultados:
O endereço será exibido na próxima tela.
Caso o endereço já tenha sido consultado, ele será recuperado do banco de dados local.

Compartilhamento:
Clique no botão Compartilhar Endereço para enviar as informações para outros aplicativos.

Erros e Mensagens:
O aplicativo exibirá mensagens de erro caso:
O CEP seja inválido.
Não haja conexão com a internet.
O CEP não seja encontrado na API.

