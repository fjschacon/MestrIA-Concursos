# 🧠 MestrIA — Plataforma Inteligente para Preparação em Concursos

> Plataforma web de estudos baseada em Inteligência Artificial, desenvolvida para oferecer uma experiência de preparação personalizada, adaptativa e orientada às necessidades de candidatos a concursos públicos.

[![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge\&logo=react\&logoColor=black)](https://react.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3+-06B6D4?style=for-the-badge\&logo=tailwindcss\&logoColor=white)](https://tailwindcss.com/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=for-the-badge\&logo=supabase\&logoColor=white)](https://supabase.com/)
[![Vercel](https://img.shields.io/badge/Vercel-Deploy-000000?style=for-the-badge\&logo=vercel\&logoColor=white)](https://vercel.com/)

---

## 📚 Sobre o Projeto

O **MestrIA** é uma aplicação web desenvolvida para otimizar a preparação para concursos públicos por meio da combinação de **Inteligência Artificial, aprendizagem adaptativa e ferramentas educacionais interativas**.

A plataforma foi projetada para transformar conteúdos de estudo em experiências personalizadas, permitindo que o usuário tenha acesso a diferentes estratégias de aprendizagem dentro de um único ambiente.

O sistema utiliza IA para auxiliar na geração e organização de conteúdos educacionais, questões, revisões e experiências de estudo personalizadas de acordo com as necessidades do usuário.

### 🎯 Objetivo

Criar uma plataforma capaz de:

* 📖 Facilitar a compreensão de conteúdos complexos;
* 🧠 Melhorar a retenção de conhecimento;
* 🔄 Automatizar processos de revisão;
* 📝 Personalizar exercícios e simulados;
* 👨‍🏫 Adaptar a experiência de ensino por meio de diferentes personas de professores;
* 🤖 Utilizar IA como ferramenta de apoio ao processo de aprendizagem.

---

# 🚀 Principais Funcionalidades

## 🤖 Aulas Guiadas por IA

Motor responsável pela geração e estruturação dinâmica de conteúdos educacionais.

A IA pode atuar como um professor virtual, adaptando a explicação de acordo com a interação e o contexto do conteúdo estudado.

**Principais conceitos envolvidos:**

* Geração dinâmica de conteúdo;
* Engenharia de prompts;
* Estruturação de conteúdos educacionais;
* Processamento contextual;
* Personalização da experiência de aprendizagem.

---

## 🧠 Sistema de Flashcards

Sistema desenvolvido para auxiliar na retenção de informações e revisão de conteúdos.

A funcionalidade foi pensada com base em conceitos de **repetição espaçada**, permitindo que o usuário utilize ciclos de revisão para reforçar o aprendizado.

**Recursos:**

* Criação e gerenciamento de flashcards;
* Organização por disciplinas e conteúdos;
* Revisões estruturadas;
* Controle do progresso de estudo.

---

## 📝 Gerador de Questões

Sistema responsável pela criação de questões e simulados personalizados utilizando inteligência artificial.

As questões podem ser estruturadas de acordo com diferentes contextos de estudo, permitindo uma experiência mais dinâmica de preparação.

**Possibilidades:**

* Geração de questões;
* Simulados personalizados;
* Diferentes níveis de dificuldade;
* Organização por disciplina;
* Feedback após resolução.

---

## 👨‍🏫 Personas de Professores

Um dos recursos centrais do MestrIA é a possibilidade de personalizar a forma como a IA apresenta os conteúdos.

O sistema utiliza **engenharia de prompts** para definir diferentes estilos de ensino, permitindo que o mesmo conteúdo seja apresentado de maneiras distintas.

Exemplos de características que podem ser configuradas:

* Didática;
* Linguagem;
* Profundidade das explicações;
* Estilo de comunicação;
* Estratégia pedagógica.

---

# 🏗️ Arquitetura e Desenvolvimento

O projeto foi desenvolvido ao longo de um ciclo de aproximadamente **sete meses**, entre fevereiro e setembro de 2026.

A arquitetura foi planejada considerando aspectos como:

* Escalabilidade;
* Organização de componentes;
* Persistência de dados;
* Autenticação;
* Controle de acesso;
* Integração com serviços de Inteligência Artificial;
* Experiência responsiva;
* Facilidade de manutenção e evolução.

A aplicação utiliza uma arquitetura baseada em **Frontend + Backend as a Service**, com o Supabase sendo responsável por serviços essenciais de backend e persistência.

### Fluxo simplificado

```text
┌──────────────────────┐
│      Usuário         │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│   React + Tailwind   │
│      Frontend        │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│      Supabase        │
│ Auth + PostgreSQL    │
│        + RLS         │
└──────────┬───────────┘
           │
           ▼
┌──────────────────────┐
│ Inteligência Artificial│
│ Geração e processamento│
│      de conteúdo      │
└──────────────────────┘
```

---

# 🛠️ Stack Tecnológica

| Tecnologia                       | Utilização                                           |
| -------------------------------- | ---------------------------------------------------- |
| ⚛️ **React**                     | Construção da interface e arquitetura de componentes |
| 🎨 **Tailwind CSS**              | Estilização e design responsivo                      |
| 🗄️ **Supabase**                 | Backend as a Service                                 |
| 🐘 **PostgreSQL**                | Persistência e gerenciamento dos dados               |
| 🔐 **Supabase Auth**             | Autenticação dos usuários                            |
| 🛡️ **Row Level Security (RLS)** | Controle de acesso aos dados                         |
| 🤖 **Google Gemini**             | Suporte ao desenvolvimento e recursos de IA          |
| ▲ **Vercel**                     | Deploy e infraestrutura de hospedagem                |
| 💻 **VS Code**                   | Ambiente de desenvolvimento                          |
| 📦 **npm**                       | Gerenciamento de dependências                        |

---

# 🧩 Engenharia de Software

Durante o desenvolvimento, foram aplicados conceitos de engenharia de software voltados à criação de uma aplicação moderna e escalável.

### Principais práticas utilizadas

* Componentização com React;
* Hooks personalizados;
* Separação de responsabilidades;
* Reutilização de componentes;
* Modelagem de dados;
* Controle de acesso utilizando RLS;
* Integração com APIs e serviços externos;
* Refatoração contínua;
* Otimização de desempenho;
* Organização de regras de negócio;
* Desenvolvimento orientado à experiência do usuário.

---

# 🤝 AI Pair Programming

A Inteligência Artificial também foi utilizada como ferramenta de **AI Pair Programming**, atuando como suporte durante diferentes etapas do desenvolvimento.

O **Google Gemini** foi utilizado como ferramenta auxiliar para análise, implementação e revisão de soluções.

### 🧠 Principais aplicações

**Arquitetura e dados**

* Apoio na definição de decisões arquiteturais;
* Modelagem e organização do banco de dados;
* Análise de relacionamentos entre entidades.

**Desenvolvimento Frontend**

* Refatoração de componentes React;
* Otimização de código;
* Identificação de possíveis problemas;
* Organização de hooks e lógica de interface.

**Integração e processamento**

* Construção de rotinas de processamento de texto;
* Integração com serviços de IA;
* Tratamento e transformação de dados.

**Regras de negócio**

* Análise de fluxos educacionais;
* Identificação de casos de uso;
* Validação de diferentes cenários;
* Apoio na resolução de problemas lógicos.

> A IA foi utilizada como ferramenta de apoio ao desenvolvimento, enquanto as decisões de arquitetura, implementação e validação das soluções fizeram parte do processo de desenvolvimento do projeto.

---

# 📂 Estrutura do Projeto

A estrutura pode variar conforme a evolução da aplicação, mas a organização segue uma abordagem baseada na separação de responsabilidades:

```text
MestrIA-Concursos/
│
├── src/
│   ├── components/       # Componentes reutilizáveis
│   ├── pages/            # Páginas da aplicação
│   ├── hooks/            # Hooks personalizados
│   ├── services/         # Integrações e serviços
│   ├── lib/              # Configurações e bibliotecas
│   └── ...
│
├── public/               # Arquivos públicos
├── .env                  # Variáveis de ambiente
├── package.json
├── tailwind.config.js
└── README.md
```

---

# 💻 Como Executar Localmente

## 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/MestrIA-Concursos.git
```

## 2. Acesse o diretório

```bash
cd MestrIA-Concursos
```

## 3. Instale as dependências

```bash
npm install
```

## 4. Configure as variáveis de ambiente

Crie um arquivo `.env` na raiz do projeto:

```env
VITE_SUPABASE_URL=sua_url_aqui
VITE_SUPABASE_ANON_KEY=sua_chave_anonima_aqui
```

> ⚠️ **Importante:** nunca compartilhe chaves privadas ou informações sensíveis do seu ambiente de produção.

## 5. Execute o projeto

```bash
npm run dev
```

Após iniciar o servidor, acesse a aplicação pelo endereço disponibilizado pelo Vite no terminal.

---

# 🔐 Segurança

O projeto utiliza recursos do **Supabase** para gerenciamento de autenticação e controle de acesso aos dados.

Entre os mecanismos utilizados está o **Row Level Security (RLS)**, permitindo definir políticas de acesso diretamente no banco de dados.

As credenciais e configurações sensíveis são mantidas por meio de **variáveis de ambiente**, evitando que informações privadas sejam diretamente inseridas no código-fonte.

---

# 📈 Evolução do Projeto

O MestrIA foi desenvolvido de forma incremental, passando por diferentes ciclos de implementação, testes, refatoração e evolução da arquitetura.

O projeto representa não apenas uma aplicação de estudos, mas também um laboratório prático para aplicação de conceitos como:

* Desenvolvimento Frontend moderno;
* Integração com Inteligência Artificial;
* Engenharia de prompts;
* Banco de dados relacional;
* Autenticação e autorização;
* Segurança de dados;
* Arquitetura de aplicações web;
* UX/UI;
* Automação e deploy.

---

# 🎓 Aprendizados

Durante o desenvolvimento do projeto, foram explorados diferentes aspectos do desenvolvimento de software, especialmente na integração entre **aplicações web, banco de dados e Inteligência Artificial**.

Entre os principais aprendizados estão:

* Desenvolvimento de aplicações utilizando React;
* Construção de interfaces responsivas;
* Modelagem de bancos PostgreSQL;
* Implementação de autenticação;
* Aplicação de Row Level Security;
* Integração com serviços de IA;
* Engenharia de prompts;
* Organização de regras de negócio;
* Refatoração e manutenção de código;
* Deploy de aplicações web.

---

# 🌐 Projeto

**MestrIA — Plataforma Inteligente para Preparação em Concursos**

Desenvolvido como projeto de estudo, experimentação e aplicação prática de tecnologias modernas de desenvolvimento web e Inteligência Artificial.

---

## 👨‍💻 Autor

**MestrIA Concursos**

Projeto desenvolvido com foco em **desenvolvimento web, Inteligência Artificial e educação personalizada**.

---

<p align="center">
  Desenvolvido com ☕, código e Inteligência Artificial.
</p>
