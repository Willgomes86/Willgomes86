# 👋 Olá, eu sou Willyan Gomes

### Desenvolvedor Sênior • Tech Lead • Backend Developer • Product Builder

Desenvolvedor especializado em **Python e Django**, com foco na construção de produtos SaaS, sistemas de gestão e arquiteturas escaláveis.

Hoje atuo como **Desenvolvedor Sênior e Tech Lead** nos projetos da **Parceiros da Educação**.

Possuo experiência em todo o ciclo de desenvolvimento de software, desde a modelagem de domínio e arquitetura até segurança, observabilidade, automação, documentação e implantação em produção.

Anteriormente atuei como **Cientista de Dados no setor bancário**, experiência que fortaleceu minha visão analítica e orientada a dados.

---

## 💼 Atuação profissional

### 🎓 Parceiros da Educação — Desenvolvedor Sênior / Tech Lead

Atuo nos projetos de tecnologia da **Parceiros da Educação**, organização que trabalha pela melhoria da educação pública no Brasil, liderando tecnicamente o desenvolvimento das plataformas de avaliação e acompanhamento da aprendizagem usadas por redes de ensino.

#### O que faço

- Liderança técnica do time de desenvolvimento e revisão de código
- Arquitetura e modularização de um sistema Django de grande porte
- Definição de padrões: camadas, CQRS leve, taxonomia de erros e ADRs
- Pipeline de CI/CD com quality gates e publicações com rollback seguro
- Segurança, privacidade e LGPD no tratamento de dados de estudantes
- Integrações com serviços de nuvem e inteligência artificial
- Documentação técnica viva, gerada e verificada a partir do código
- Mentoria de desenvolvedores em início de carreira

---

## 🚀 Principais projetos

### 🏥 Santhera *(Projeto Privado)*

Plataforma SaaS de gestão clínica para profissionais de Neuropsicopedagogia, Psicologia, Fonoaudiologia e Terapia Ocupacional. Conecta paciente, agenda, anamnese, testes, encaminhamentos, intervenções, financeiro e relatórios em um único fluxo guiado.

#### Destaques

- Arquitetura modular
- Multi-tenant
- CQRS leve
- Services Layer
- Domain Contracts
- Adapters
- Read Models e Read Services
- Sistema de billing e planos SaaS
- Controle de permissões e RBAC
- Inteligência Artificial aplicada ao domínio
- Leitura automática de testes em PDF e imagem (OCR)
- Sistema de Claims e resolução de conflitos
- Compartilhamento seguro de fichas entre profissionais
- Processamento em segundo plano com Celery e Redis
- Backup e recuperação segura
- Autenticação em dois fatores (2FA)
- Audit Trail
- Observabilidade e métricas
- Documentação técnica automatizada
- Quality Gates no pipeline

#### Métricas atuais

- 24 apps
- +110 models
- +120 services
- +50 adapters
- +125 mil linhas de código
- +4.100 funções
- +1.000 classes
- +1.000 testes automatizados em +180 arquivos
- +800 commits

---

### 🌎 Portal CENPLAFAM

Modernização completa da presença digital da instituição: portal público, área autenticada por papéis e plataforma de capacitação, em produção em VPS Linux.

#### Principais recursos

- Portal institucional e fluxo editorial de notícias
- Sistema de formação e certificação, com cursos, módulos, aulas e avaliações
- Emissão automatizada de certificados
- Gestão de usuários e acompanhamento de equipes
- Controle de acesso baseado em papéis (RBAC) com escopo regional
- Mapeamento global de instrutores com geocodificação
- Comunicação interna entre usuários
- Testes End-to-End com Playwright
- Observabilidade
- Inventário automático da arquitetura e verificação de fronteiras no CI

#### Métricas atuais

- 9 apps
- +45 mil linhas de código
- +600 testes automatizados
- +390 commits

---

### 📣 Ordinis *(Projeto Privado)*

Hub operacional para agências de Social Media: clientes, contratos, produção de conteúdo, aprovação, publicação, atendimento, CRM e financeiro em um só lugar, sem informação espalhada entre planilhas e mensagens.

#### Destaques

- Fluxo editorial completo: ideia → produção → revisão → aprovação do cliente → agendamento → publicação
- Aprovação pelo cliente com login ou por link de uso único com validade
- Integração com a API oficial da Meta (Instagram, Facebook, Messenger e WhatsApp), com webhook assinado e idempotente
- Fila de publicação auditável, com retentativas
- Inbox multicanal com triagem, sentimento, prioridade, SLA e qualificação de leads
- Relatórios executivos por cliente e recomendações automáticas de legenda, hashtags e melhores horários
- Cofre de credenciais criptografado por perfil social
- CRM em pipeline e financeiro com fluxo de caixa previsto x realizado
- Controle de acesso: a equipe interna vê toda a operação; cada cliente vê apenas as próprias empresas

---

### 🏛️ Portal Universitário *(Projeto Privado)*

Sistema de gestão para uma universidade, com painéis, relatórios e APIs por área administrativa: Reitoria, Pró-Reitorias Administrativa e Acadêmica, Controladoria, RH, TI e Comunicação.

#### Destaques

- RBAC com escopo por departamento e unidade
- Dashboards executivos por área
- Agenda corporativa com solicitações e aprovações
- Comunicação integrada: campanhas de e-mail, WhatsApp e Facebook, com modelos e histórico
- Indicadores acadêmicos e financeiros dos estudantes
- Relatórios em Excel e PDF
- Auditoria das ações

#### Métricas atuais

- 8 módulos de domínio
- +20 mil linhas de código
- +420 commits

---

### 🔐 Custodia Ingressus *(Projeto Privado)*

Controle de acesso físico integrado a equipamentos Hikvision: cadastro de pessoas com foto e face, dispositivos e permissões de acesso sincronizados com os equipamentos.

#### Destaques

- Integração com dispositivos Hikvision via HTTP Digest
- Sincronização global e por dispositivo em jobs assíncronos (Celery + Redis), idempotentes e auditáveis
- Revogação confiável em bloqueio, expiração ou remoção
- Monitoramento da saúde dos dispositivos (online/offline e tempo de resposta)
- Reprocessamento de falhas e logs de integração
- Perfis de administrador, operador e auditor

---

### 🧩 Outros projetos

- ⛪ **Ecclesia Voco** *(Privado)* — escala de acólitos com geração automática de um mês inteiro, regras litúrgicas, disponibilidade, conflitos de horário e substituições (Django + DRF).
- 🍺 **Dominum** *(Privado)* — gestão para bares e restaurantes: mesas, comandas com QR Code, painéis de cozinha e caixa, estoque e DRE simplificada.
- 🍔 **Burguer & Quests** *(Privado)* — pedidos para hamburgueria com gamificação estilo RPG (níveis, classes e conquistas) e pagamento via Mercado Pago.

### 🎓 Projetos acadêmicos (Univesp)

- 🏗️ [**pi_04**](https://github.com/Willgomes86/pi_04) — produtividade em obras: API Django REST, telemetria simulada de equipamentos e previsão de produtividade com Random Forest (scikit-learn).
- 📊 [**pi_02**](https://github.com/Willgomes86/pi_02) — painel de KPIs para incorporadora: ingestão de planilhas e indicadores de vendas, carteira, compras e planejamento.

---

# ⚙️ Stack Principal

### Backend

- Python
- Django
- Django REST Framework
- Flask
- Celery
- Redis

### Banco de Dados

- PostgreSQL
- MySQL
- Oracle

### Arquitetura

- Services Layer
- Repository Pattern
- CQRS
- Domain Contracts
- Adapters
- Multi-Tenant
- RBAC

### DevOps e Infraestrutura

- Docker
- Linux
- Gunicorn
- Nginx
- Git
- VPS Linux
- GitHub Actions

### Integrações

- Mercado Pago
- API oficial da Meta (Instagram, Facebook e WhatsApp)
- Equipamentos de controle de acesso Hikvision
- AWS S3

### Qualidade e Segurança

- Pytest
- Playwright
- Ruff
- Black
- Bandit
- Pip-Audit
- Gitleaks
- CI/CD
- Audit Logs
- 2FA
- Observabilidade

### Dados e Inteligência Artificial

- Pandas
- Scikit-Learn
- Power BI
- OCR
- OpenAI
- Web Scraping
- Automação de Processos

---

# 📚 Áreas de Interesse

- Engenharia de Software
- Arquitetura de Sistemas
- Domain-Driven Design
- SaaS
- DevSecOps
- APIs REST
- Inteligência Artificial
- Observabilidade
- Automação

---

# 📫 Contato

📧 **willyangomes86@gmail.com**

[LinkedIn](https://www.linkedin.com/in/willyan-gomes-218071297/)


---

> "Transformando ideias em produtos reais através de arquitetura, automação e engenharia de software."
