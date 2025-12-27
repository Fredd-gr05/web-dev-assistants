# 🤖 Web Development Assistants Team

Equipe de 3 assistentes IA para desenvolvimento web profissional com comunicação integrada.

## 📦 Assistentes

### 1. **Prototipi** - Prototipador Web
**Especialidade:** Prototipagem rápida com Bootstrap 5
- Stack: HTML5 + Bootstrap 5 + JavaScript vanilla
- Objetivo: Criar protótipos funcionais para aprovação em 2-4 horas
- Backend: Supabase REST API (opcional)
- Entrega: Protótipo + Documento de especificação para produção

### 2. **VueBuilder Pro** - Desenvolvedor Vue.js
**Especialidade:** Aplicações Vue.js profissionais
- Stack: Vue 3 + TypeScript + Tailwind CSS
- Backend: Supabase (@supabase/supabase-js)
- Features: Composition API, Pinia (state management), Vue Router
- Segurança: Warnings inline, validação rigorosa, RLS no banco
- Entrega: App completo + Checklist para revisão

### 3. **DebugMaster** - Revisor de Código
**Especialidade:** Análise técnica e otimização
- Tecnologias: Vue.js, TypeScript, HTML/CSS/JS
- Foco: Bugs, segurança, performance, type safety
- Metodologia: Code review objetivo com fixes
- Entrega: Relatório completo + Código otimizado + Veredicto

## 🔄 Workflow de Comunicação

```
FASE 1: PROTOTIPAGEM
  └─ Prototipi cria protótipo Bootstrap
     └─ Gera: "=== SPEC PRODUÇÃO ===" para VueBuilder Pro

FASE 2: DESENVOLVIMENTO
  └─ VueBuilder Pro recebe especificação
     └─ Desenvolve app Vue profissional
     └─ Gera: "=== CHECKLIST REVISÃO ===" para DebugMaster

FASE 3: REVISÃO
  └─ DebugMaster analisa código
     └─ Emite: "=== CODE REVIEW ===" com veredicto
     └─ Se crítico: retorna para VueBuilder Pro
```

## 📋 Estrutura do Repositório

```
web-dev-assistants/
├── README.md                    # Documentação (este arquivo)
├── prompts/
│   ├── prototipi.md            # Prompt do Prototipi
│   ├── vuebuilder_pro.md       # Prompt do VueBuilder Pro
│   └── debugmaster.md          # Prompt do DebugMaster
└── docs/
    └── workflow_exemplo.md     # Exemplo detalhado de uso
```

## 🚀 Como Usar

### No Perplexity Spaces:
1. Copie o conteúdo do arquivo `.md` do assistente desejado
2. Crie um novo Espaço/Assistente no Perplexity
3. Cole o prompt completo
4. Configure conforme as instruções

### Workflow Completo:
1. **Descreva o projeto ao Prototipi** (página, app, dashboard)
2. **Prototipi entrega o protótipo** e a especificação
3. **Aprove ou ajuste o protótipo**
4. **Envie a especificação ao VueBuilder Pro**
5. **VueBuilder Pro entrega a app completa**
6. **Envie código + checklist para DebugMaster**
7. **DebugMaster faz code review final**

## 🔧 Stack Tecnológica

### Frontend
- **Vue 3** com Composition API
- **TypeScript** para type safety
- **Tailwind CSS** para styling escalável
- **Vue Router** para navegação
- **Pinia** para state management

### Backend
- **Supabase** para banco de dados e autenticação
- **PostgreSQL** como banco relacional
- **RLS (Row Level Security)** para segurança

### Ferramentas
- **Git/GitHub** para versionamento
- **TypeScript** para desenvolvimento seguro
- **ESLint/Prettier** (recomendado)

## 📊 Características Principais

✅ **Comunicação integrada** entre assistentes
✅ **Warnings de segurança** inline nos códigos
✅ **TypeScript** para maior confiabilidade
✅ **Supabase** como backend padrão
✅ **Código comentado** de forma sucinta
✅ **Boas práticas** profissionais
✅ **Uso comercial** otimizado
✅ **Tom técnico e direto**

## 📝 Exemplo de Uso

**Usuário:** "Crie um dashboard de vendas com gráficos"

**Prototipi:** Entrega protótipo Bootstrap em 2h + especificação

**Usuário:** "Aprovado!"

**VueBuilder Pro:** Recebe spec → Desenvolve app Vue → Entrega em 8h

**DebugMaster:** Revisa → Aprova → Relatório final

## ⚙️ Configuração para Supabase

Os assistentes estão configurados para integração com Supabase. Você precisará:

1. Criar projeto no [Supabase](https://supabase.com)
2. Obter credenciais (Project URL, Anon Key)
3. Criar tabelas conforme necessário
4. Configurar RLS (Row Level Security)

## 🔐 Segurança

Todos os assistentes seguem padrões de segurança:
- Validação de inputs rigorosa
- Proteção XSS/CSRF
- Autenticação JWT
- Criptografia com bcrypt
- Headers de segurança
- Rate limiting

## 📚 Documentação Adicional

Veja `/docs/workflow_exemplo.md` para um exemplo completo e prático de como a equipe funciona em um projeto real.

## 🤝 Contribuições

Este repositório é o home dos assistentes. Para sugestões ou melhorias, abra uma issue!

## 📄 Licença

MIT License - veja LICENSE para detalhes

---

**Versão:** 1.0
**Última atualização:** Dezembro 2025
**Status:** Production Ready ✅
