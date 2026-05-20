## ✅ 1. Descrição do desafio escolhido

O projeto apresentado no site consiste em um **sistema de gerenciamento de estoque com integração via API documentada (Swagger)**.

O desafio central abordado é:

- Criar uma aplicação web capaz de gerenciar produtos, quantidades e movimentações de estoque (entrada e saída);
- Prover uma interface simples para visualização e controle dessas informações;
- Integrar ou simular uma API REST documentada, permitindo testes e entendimento das operações do sistema.

Esse tipo de sistema resolve problemas comuns em empresas, como:

- Controle manual ineficiente de estoque;
- Falta de rastreabilidade de movimentações;
- Dificuldade de integração entre front-end e back-end.

A escolha de usar Swagger indica que o projeto também foca em:

- Documentação clara de endpoints;
- Possibilidade de testar requisições diretamente pela interface. [1](https://medium.com/@matheus787/documentando-suas-apis-usando-o-swagger-680965f12163)


---

## ✅ 2. Justificativa técnica da escolha da plataforma

O sistema foi desenvolvido utilizando a plataforma **Lovable**, que utiliza inteligência artificial para gerar aplicações web a partir de descrições em linguagem natural.

### Motivos técnicos para essa escolha:

### 🟢 1. Desenvolvimento acelerado (no-code/low-code)

- Lovable permite criar aplicações completas sem escrever código manualmente, gerando front-end e back-end automaticamente. [2](https://www.locaweb.com.br/blog/temas/codigo-aberto/o-que-e-lovable-e-como-funciona-guia-completo/)  
- Ideal para prototipagem rápida de sistemas como controle de estoque.

### 🟢 2. Integração automática de interface e lógica

- A plataforma já organiza interface, regras de negócio e banco de dados em um único fluxo. [3](https://studioartemis.co/conteudos/negocios/lovable-o-que-e/)  
- Isso facilita a criação de dashboards e telas típicas de sistemas de estoque.

### 🟢 3. Facilidade de deploy

- O sistema pode ser publicado rapidamente via link (como o próprio site analisado), sem necessidade de configurar infraestrutura.

### 🟢 4. Compatibilidade com APIs e Swagger

- Projetos gerados podem integrar APIs externas e usar documentação padrão (OpenAPI/Swagger), essencial para sistemas modernos. [4](https://swagger.io/?lang=pt)  

### 🟢 5. Foco em protótipos funcionais (MVP)

- Lovable é altamente eficiente para criar MVPs, permitindo validar ideias rapidamente antes de um desenvolvimento mais robusto. [5](https://www.eesel.ai/pt/blog/lovable)  

👉 Em resumo: a escolha da plataforma é justificável pela **rapidez, simplicidade e foco em prototipação**, ideal para um projeto acadêmico ou inicial.


---

## ✅ 3. Reflexão crítica sobre as limitações encontradas

Apesar das vantagens, o uso do Lovable e desse tipo de solução apresenta algumas limitações importantes:

### 🔴 1. Limitações de personalização avançada

- A geração automática pode dificultar alterações mais complexas ou específicas no código;
- Em alguns casos, não há controle total sobre arquitetura e otimizações.

### 🔴 2. Dependência da plataforma

- O sistema fica dependente do ecossistema do Lovable (deploy, estrutura, integrações);
- Isso pode dificultar migração para outras tecnologias no futuro.

### 🔴 3. Escalabilidade limitada

- Embora adequado para protótipos, pode não ser ideal para sistemas de grande escala ou alta complexidade;
- Aplicações empresariais robustas exigem maior controle de performance e segurança.

### 🔴 4. Possíveis falhas na geração automática

A IA pode gerar:

- Inconsistências na lógica;
- Interfaces pouco refinadas;
- Funcionalidades incompletas.

Isso exige validação manual constante.

### 🔴 5. Integrações externas podem ser limitadas

- Para funcionalidades mais avançadas (ex: ERP completo, BI, automações complexas), pode ser necessário sair da plataforma.
