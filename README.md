# Game Hub

## Descrição

**Game Hub** é uma plataforma online que reúne uma vasta coleção de jogos em um só lugar. Nosso objetivo é proporcionar aos jogadores uma experiência diversificada e acessível, permitindo que encontrem, joguem e compartilhem seus jogos favoritos com facilidade.

## Funcionalidades

- **Biblioteca de Jogos:** Acesse uma ampla variedade de jogos, desde clássicos até os lançamentos mais recentes.
- **Perfis de Usuário:** Crie um perfil personalizado, acompanhe seu progresso e compartilhe suas conquistas com amigos.
- **Comunidade:** Participe de fóruns de discussão, entre em grupos e faça amigos que compartilham dos mesmos interesses.
- **Avaliações e Comentários:** Leia e escreva avaliações sobre os jogos, ajude outros jogadores a encontrar os melhores títulos.
- **Filtros de Pesquisa:** Utilize filtros avançados para encontrar jogos por gênero, popularidade, avaliação e muito mais.
- **Atualizações e Notícias:** Fique por dentro das últimas novidades do mundo dos jogos com notícias atualizadas e artigos.

## Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3, JavaScript, React
- **Backend:** Node.js, Express.js
- **Banco de Dados:** MongoDB
- **Autenticação:** JWT (JSON Web Tokens)
- **Hospedagem:** Heroku / AWS

## Instalação

Siga os passos abaixo para configurar o ambiente de desenvolvimento local:

1. Clone o repositório:

   ```sh
   git clone https://github.com/seu-usuario/game-hub.git

   ```

2. Navegue até o diretório do projeto:

```sh
Copy code
cd game-hub
```

3. Instale as dependências do backend:

```sh
Copy code
cd backend
npm install
```

4. Instale as dependências do frontend:

```sh
Copy code
cd ../frontend
npm install
```

5. Configure as variáveis de ambiente:
   Crie um arquivo .env na raiz do projeto backend e adicione as seguintes variáveis:

```
makefile
Copy code
MONGO_URI=<seu-mongo-uri>
JWT_SECRET=<seu-segredo-jwt>
PORT=5000
```

6. Inicie o servidor backend:

```sh
Copy code
cd ../backend
npm start
```

7. Inicie o servidor frontend:

```sh
Copy code
cd ../frontend
npm start
```

## Contribuição

### Se você deseja contribuir para o projeto Game Hub, siga os passos abaixo:

1. Fork o repositório.
2. Crie uma branch para sua feature:

```sh
Copy code
git checkout -b minha-feature
```

3. Commit suas mudanças:

```sh
Copy code
git commit -m 'Adiciona minha feature'
```

4. Push para a branch:

```sh
Copy code
git push origin minha-feature
```

5. Abra um Pull Request.

## Licença

### Este projeto está licenciado sob a MIT License.

## Contato

### Para mais informações, dúvidas ou sugestões, entre em contato através do email: contato@gamehub.com.

### Game Hub - Todos os seus jogos favoritos em uma só plataforma!
