# Le Scone

Código-fonte para o website "Le Scone". O website foi desenvolvido utilizando Sass para melhorar a organização e manutenção do estilo.

## Sobre o Projeto

O projeto "Le Scone" é um website fictício para um restaurante, proporcionando aos usuários informações sobre o menu, localização e detalhes de contato. O design foi criado com o uso de Sass para facilitar a criação e manutenção de estilos CSS.

## Tecnologias Utilizadas

- HTML5
- CSS3 (utilizando Sass)

## Estrutura de Pastas

- **`/css`**: Contém o arquivo CSS resultante do processo de compilação do Sass, `style.css`.
  - **`/css/scss`**: Contém os arquivos Sass.
- **`/img`**: Armazena as imagens utilizadas no website.

## Como Contribuir

Se deseja contribuir para o projeto, siga as etapas abaixo:

1. Faça um fork do repositório.
2. Clone o repositório forkado para o seu ambiente local.
3. Crie uma branch para suas alterações: `git checkout -b nome-da-sua-branch`.
4. Faça suas modificações e adições.
5. Commit suas alterações: `git commit -m 'Descrição das alterações'`.
6. Faça o push para a branch: `git push origin nome-da-sua-branch`.
7. Crie um Pull Request na [página de Pull Requests](https://github.com/yuri-italo/le-scone/pulls) do repositório original.

## Ambiente de Desenvolvimento

Certifique-se de ter o Sass instalado para compilar os arquivos. Utilize o seguinte comando para compilar os estilos:

```bash
sass --watch ./css/scss/style.scss:./css/style.css
```

Isso garantirá que as alterações nos arquivos Sass sejam refletidas nos estilos CSS.