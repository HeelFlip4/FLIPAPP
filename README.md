# HortFruit App

HortFruit App é um aplicativo mobile desenvolvido em **Flutter**, que simula uma loja de hortifrúti. 
O projeto foi criado com o objetivo de estudo e prática no desenvolvimento de aplicativos móveis.

## Funcionalidades

- **Catálogo de Produtos**: Exibição de produtos organizados em categorias como frutas, verduras e legumes.
- **Carrinho de Compras**: Adicione itens ao carrinho e veja o resumo dos produtos selecionados.
- **Simulação de Compra**: Finalize uma simulação de compra para entender melhor o fluxo de um e-commerce.

## Tecnologias Utilizadas

### Front-end Mobile
- **Flutter**: Framework para desenvolvimento mobile multiplataforma (iOS e Android) com design nativo.
- **Dart**: Linguagem de programação utilizada pelo Flutter para escrever a lógica do aplicativo.

### Backend Simulado
- **Mock Data**: O aplicativo utiliza dados fictícios armazenados localmente para simular um ambiente de e-commerce.

## Configuração e Execução

### Pré-requisitos
- **Flutter SDK**: Para compilar e rodar o aplicativo.
- **Android Studio** ou **VS Code**: Para emular o ambiente de desenvolvimento.
- **Dispositivo ou Emulador**: Um smartphone ou emulador configurado para rodar aplicativos Flutter.

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/HeelFlip4/HortFruit_App.git
   cd HortFruit_App
   ```

2. Instale as dependências do projeto:
   ```bash
   flutter pub get
   ```

3. Conecte um dispositivo ou inicie um emulador compatível.

4. Execute o aplicativo:
   ```bash
   flutter run
   ```

## Estrutura do Projeto

- **`lib/`**: Contém todo o código principal do aplicativo.
  - **`screens/`**: Telas do aplicativo (ex.: catálogo, carrinho, etc.).
  - **`models/`**: Modelos de dados usados no app (ex.: Produto).
  - **`widgets/`**: Componentes reutilizáveis para a interface do usuário.
- **`assets/`**: Recursos estáticos como imagens e ícones.
- **`pubspec.yaml`**: Arquivo de configuração do Flutter e lista de dependências.

## Funcionalidades Detalhadas

### Catálogo de Produtos
- Navegue por uma lista de produtos organizados em categorias.
- Visualize os detalhes de cada item, incluindo nome, preço e imagem.

### Carrinho de Compras
- Adicione ou remova produtos do carrinho.
- Veja o resumo dos itens selecionados, incluindo o total de produtos e o preço acumulado.

### Simulação de Compra
- Finalize o pedido para simular a experiência completa de um e-commerce.

## Próximos Passos

- Implementar um backend real para persistência de dados.
- Adicionar autenticação de usuário para uma experiência mais personalizada.
- Criar testes unitários e de integração para garantir maior estabilidade.

## Como Contribuir

1. Faça um fork do repositório.
2. Crie uma nova branch para suas alterações:
   ```bash
   git checkout -b minha-feature
   ```
3. Faça o commit das suas alterações:
   ```bash
   git commit -m "Minha nova feature"
   ```
4. Envie suas alterações:
   ```bash
   git push origin minha-feature
   ```
5. Abra um pull request no GitHub.

---

Este projeto é de caráter educacional e foi desenvolvido para aprender mais sobre desenvolvimento mobile utilizando Flutter.
