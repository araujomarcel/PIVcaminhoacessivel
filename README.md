# Caminho Acessível

## Descrição do Projeto
O **Caminho Acessível** é um aplicativo desenvolvido em **Flutter** que visa facilitar a mobilidade de pessoas com deficiência e/ou mobilidade reduzida. Através do mapeamento colaborativo, o aplicativo identifica rotas acessíveis em diversas cidades, destacando caminhos sem obstáculos, rampas, e outras condições necessárias para a locomoção segura.

## Objetivo
O objetivo principal do projeto é oferecer uma ferramenta prática que melhore a autonomia e a qualidade de vida de pessoas que enfrentam desafios de mobilidade. Permitindo que os usuários compartilhem informações e avaliem rotas acessíveis, o **Caminho Acessível** cria uma rede de suporte colaborativa para aumentar a conscientização sobre acessibilidade urbana.

## Tecnologias Utilizadas

- **Flutter**: Framework para desenvolvimento mobile cross-platform.
- **Dart**: Linguagem de programação utilizada com Flutter.
- **Firebase**: Para autenticação, banco de dados em tempo real e armazenamento de dados.
- **Google Maps API**: Para captar estabelecimentos com acessibilidade.

## Funcionalidades Principais

- **Mapeamento colaborativo**: Usuários podem inserir novas rotas acessíveis e reportar obstáculos em tempo real.
- **Classificação de acessibilidade**: Avaliação de rotas baseada em critérios de acessibilidade, como presença de rampas e condições de calçadas.
- **Autenticação de usuários**: Login através de contas Google ou Facebook para participação na comunidade.
- **Feedback da comunidade**: Usuários podem deixar comentários e avaliar a acessibilidade de rotas.

## Estrutura do Projeto

- `lib/`: Contém o código Dart principal do aplicativo.
  - `screens/`: Telas do aplicativo.
  - `widgets/`: Componentes reutilizáveis da interface.
  - `services/`: Classes responsáveis pela integração com Firebase e APIs externas.
- `assets/`: Imagens, ícones e outros arquivos estáticos.
- `android/` e `ios/`: Configurações específicas para as plataformas Android e iOS.

## Como Executar o Projeto

### Pré-requisitos

- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- Conta no [Firebase](https://firebase.google.com) para configuração do backend

### Licença
Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE para mais detalhes.



