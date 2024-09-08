# Eduardo — Um modelo de portfólio 11ty
Lance seu portfólio pessoal em minutos e modifique o conteúdo sem abrir um editor de código!

### <pre>🖥 [Demo](https://eduardooliveira.dev/)</pre>

## 🤔 O que é isso?
Um tema [Eleventy](https://www.11ty.io/) projetado para simplificar o processo de criação de um lindo portfólio e blog. Totalmente integrado com [Vercel](https://vercel.com/) para gerenciamento de conteúdo flexível e com tecnologia Git.

## ✨ Recursos
* Integração profunda com [Vercel](https://vercel.com/). Modifique o conteúdo sem abrir um editor de código.
* Páginas de blog e projeto personalizáveis ​​com suporte a tags
* Formulário de contato funcional.
* Velocidades de página rápidas e altas pontuações de farol
* Usa Markdown para arquivos de conteúdo e Nunjucks para layouts
* Framework 100% Javascript gratuito
* Suporte SCSS com estilos básicos sensatos
* Fluxo de trabalho de implantação contínua via [Netlify](https://www.netlify.com/)
* Imagens responsivas geradas no momento da construção
* HTML minimizado com [HTMLMinifier](https://github.com/kangax/html-minifier)
* CSS minimizado com [cssnano](https://github.com/cssnano/cssnano)
* Integração [Turbolinks](https://github.com/turbolinks/turbolinks) para permitir navegação instantânea sem atualização de página
* Filtros Nunjuck úteis criados em

## 🏠 Desenvolvimento local
Se você quiser testar as coisas localmente antes de implantar, siga os passos abaixo:

- abra seu terminal
- Clone o repositório localmente
- Navegue até a pasta raiz
- Instale os produtos: `npm install`
- Execute: `npm start`
- Agora você deve conseguir ver tudo em execução no localhost:8080

## 💻 Scripts de desenvolvimento

**`npm start`**

> Execute 11ty com hot reload no localhost:8080

**`npm run build`**

> Gere build de produção minificada

## 💡 Modo escuro

Para habilitar a troca do modo claro para o escuro, `global.json` tem algumas configurações:

- `enable_theme_switch`: defina como `true` se quiser que seus visitantes possam alternar o tema
- `default_theme`: defina como `dark` ou outro valor (que sempre significa `light`)
- `use_system_theme`: defina como `true` se quiser que a preferência do sistema seja aplicada