# DuWaiWai 🚀

Aplicação mobile desenvolvida com **React Native** e **Expo** para aprendizado e interação com a língua indígena Kirwanhe. O projeto implementa autenticação de usuários, gamificação e recursos multimídia para tornar o aprendizado mais engajador.

## 📱 Sobre o Projeto

DuWaiWai é uma plataforma educacional que combina:
- **Autenticação**: Login e cadastro de usuários
- **Gamificação**: Seleção de dificuldade e mapa de progresso
- **Aprendizado Interativo**: Prática de digitação, gravação de áudio e visualização no mapa
- **Interface Responsiva**: Suporta web, iOS e Android

## 🛠️ Tecnologias Utilizadas

- [React Native](https://reactnative.dev/) - Framework para desenvolvimento mobile
- [Expo](https://expo.dev/) - Plataforma para desenvolvimento e deployment
- [React Navigation](https://reactnavigation.org/) - Navegação entre telas
- [Styled Components](https://styled-components.com/) - Estilização de componentes
- [TypeScript](https://www.typescriptlang.org/) - Type safety
- [AsyncStorage](https://react-native-async-storage.github.io/async-storage/) - Armazenamento local

## 📂 Estrutura do Projeto

```
src/
├── pages/
│   ├── Home/              # Tela inicial
│   ├── login/             # Autenticação
│   ├── cadastro/          # Registro de usuários
│   ├── dificuldade/       # Seleção de nível
│   ├── selecao/           # Seleção de conteúdo
│   ├── digitacao/         # Prática de digitação
│   ├── gravacao/          # Gravação de áudio
│   └── mapa/              # Visualização de progresso
├── routes/
│   └── Routes.tsx         # Configuração de navegação
```

## 🚀 Como Executar

### Pré-requisitos
- Node.js 16+
- npm ou yarn

### Instalação e Execução

1. **Instalar dependências**
   ```bash
   npm install
   ```

2. **Iniciar o projeto**
   ```bash
   npm start
   ```

3. **Executar em plataformas específicas**
   ```bash
   npm run android    # Emulador Android
   npm run ios        # Simulador iOS
   npm run web        # Navegador web
   ```

## 📚 Páginas Disponíveis

| Página | Descrição |
|--------|-----------|
| **Home** | Tela de boas-vindas com logo e botão de inicialização |
| **Login** | Autenticação de usuários existentes |
| **Cadastro** | Registro de novos usuários |
| **Dificuldade** | Seleção do nível de dificuldade |
| **Seleção** | Escolha do conteúdo a estudar |
| **Digitação** | Exercício de prática de digitação |
| **Gravação** | Gravação e prática de pronuncia |
| **Mapa** | Visualização do progresso do usuário |

## 🤝 Contribuindo

Para contribuir com o projeto:

1. Faça um fork
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob licença privada.

## 📧 Contato

Para mais informações sobre o projeto, entre em contato através das issues do repositório.
