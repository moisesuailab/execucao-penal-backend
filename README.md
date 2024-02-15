Está é uma API Rest, então não tem interface nesse repositório. Porém, é possível conectar um interface a ele. A interface está em outro repositório.

# Como rodar 

Você vai precisar do nodens instalado no seu computador para rodar o projeto.

Clone o repositório:
```
$ git clone https://github.com/lvsouza/youtube-curso-react-materialui-typescript.git
```

Entre na pasta
```
$ cd youtube-curso-react-materialui-typescript
```

Instale as dependências
```
$ npm install
```

Configure as variáveis ambiente, crie o arquivo `.env` na pasta raiz do projeto coloque o conteúdo a seguir dentro
```
PORT=3333
NODE_ENV=dev

IS_LOCALHOST=true

ENABLED_CORS=[Lista de endereços separados por ";"]
JWT_SECRET=[Uma string qualquer]
```

Rode o projeto
```
$ npm start
```

