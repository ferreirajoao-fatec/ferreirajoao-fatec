<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=220&section=header&text=Jo%C3%A3o%20Gabriel&fontSize=52&fontColor=ffffff&fontAlignY=34&animation=fadeIn&desc=Desenvolvedor%20Backend%20%7C%20Node.js%20%7C%20Clean%20Architecture&descAlignY=54&descSize=18" width="100%" />

<a href="https://github.com/ferreirajoao-fatec">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=650&lines=Estudante+de+DSM+na+Fatec+Mat%C3%A3o;Backend+com+Node.js+e+Express;Clean+Architecture%2C+SOLID+e+TDD;Corre%C3%A7%C3%A3o+antes+de+atalho." alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://img.shields.io/github/followers/ferreirajoao-fatec?style=for-the-badge&logo=github&label=Seguidores&color=58A6FF&labelColor=0D1117" />
<img src="https://komarev.com/ghpvc/?username=ferreirajoao-fatec&label=Visitas+no+perfil&color=58A6FF&style=for-the-badge" />

</div>

<br/>

## Sobre mim

```js
const joao = {
  nome: "João Gabriel",
  formacao: "Desenvolvimento de Software Multiplataforma — Fatec Matão",
  atuacao: "Desenvolvimento backend",
  stackPrincipal: ["Node.js", "NestJS", "TypeScript"],
  estudandoAgora: ["Arquitetura limpa", "Testes automatizados"],
  filosofia: "Código que passa no teste é o mínimo. Código que sobrevive à manutenção é o objetivo."
};
```

- Curso **DSM na Fatec Matão** e aplico **Clean Architecture, SOLID e TDD** nos projetos que desenvolvo
- Atuo principalmente no **backend**: modelagem de dados, APIs REST, autenticação, testes e segurança
- Gosto de documentar o que construo — roteiros, PRs descritivos e material didático fazem parte da entrega
- Uso **conventional commits** e fluxo de trabalho com Git Flow

<br/>

## Stack e ferramentas

<div align="center">

### Back-end
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

### Front-end
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### Banco de dados
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### Testes e infraestrutura
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=for-the-badge&logo=turborepo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

### Ferramentas
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![pnpm](https://img.shields.io/badge/pnpm-F69220?style=for-the-badge&logo=pnpm&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

</div>

<br/>

## Projetos em destaque

### [Sinapse](https://github.com/ferreirajoao-fatec/sinapse)

Plataforma de estudos em português: organização de anotações em hierarquia (grupos, seções, páginas e subpáginas), editor de texto rico com autosave, command palette e atalhos de teclado.

Monorepo **pnpm + Turborepo** com **Next.js 15** no front e **NestJS 11 + Prisma + PostgreSQL + Redis** no back. Autenticação JWT com cookies httpOnly e rotação de refresh token, OAuth do Google e exportação/exclusão de dados em conformidade com a LGPD. O isolamento de dados entre contas é garantido em nível de ORM por uma extensão do Prisma que injeta o filtro por usuário e bloqueia operações inseguras, coberto por testes e2e.

![Linguagem](https://img.shields.io/github/languages/top/ferreirajoao-fatec/sinapse?style=flat-square&labelColor=0D1117&color=58A6FF)
![Último commit](https://img.shields.io/github/last-commit/ferreirajoao-fatec/sinapse?style=flat-square&labelColor=0D1117&color=58A6FF&label=%C3%BAltimo%20commit)
![Tamanho](https://img.shields.io/github/repo-size/ferreirajoao-fatec/sinapse?style=flat-square&labelColor=0D1117&color=58A6FF&label=tamanho)

### [DevShelf](https://github.com/ferreirajoao-fatec/devshelf)

Fichário digital de projetos para desenvolvedores. O usuário entra com a conta do GitHub, importa ou cadastra seus repositórios, organiza tudo por status e tecnologia, e publica um catálogo visual com página própria para cada projeto e um perfil público compartilhável.

Construído em **Next.js + TypeScript** com API Routes e Server Actions no back, **PostgreSQL + Prisma**, validação com **Zod** e autenticação exclusiva por **GitHub OAuth** via Auth.js. A importação de repositórios consome a **GitHub REST API**. Interface com Tailwind e shadcn/ui.

![Linguagem](https://img.shields.io/github/languages/top/ferreirajoao-fatec/devshelf?style=flat-square&labelColor=0D1117&color=58A6FF)
![Último commit](https://img.shields.io/github/last-commit/ferreirajoao-fatec/devshelf?style=flat-square&labelColor=0D1117&color=58A6FF&label=%C3%BAltimo%20commit)
![Tamanho](https://img.shields.io/github/repo-size/ferreirajoao-fatec/devshelf?style=flat-square&labelColor=0D1117&color=58A6FF&label=tamanho)

<br/>

## Contribuições

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ferreirajoao-fatec/ferreirajoao-fatec/output/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ferreirajoao-fatec/ferreirajoao-fatec/output/snake.svg" />
  <img alt="Animacao da cobrinha comendo as contribuicoes" src="https://raw.githubusercontent.com/ferreirajoao-fatec/ferreirajoao-fatec/output/snake.svg" />
</picture>

</div>

<br/>

## Onde me encontrar

<div align="center">

<a href="https://www.linkedin.com/in/SEU-LINKEDIN">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>
<a href="mailto:joao.ferreira1b2@gmail.com">
  <img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>
<a href="https://github.com/ferreirajoao-fatec">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" width="100%" />

</div>
