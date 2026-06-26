# TCC 2026 — [Próximo Passo]
**LTP3 + QP3 · CEMIC 2026 · Prof. Rafael Martins Alves**

---

## 👥 Integrantes

| Samara Silva Pessoa | GitHub | 3C |
|--------------|--------|-------|
| (Laura Ferreira de Almada) | @username  | 3C |
| (Andressa Queiroz de Sousa) | @username | 3C |
| (Ana Beatriz Americo Almada do Nascimento) | @username | 3C |
| (Rafaela Pereira de Santana) | @username | 3C |

**Tema:** (Site de teste vocacional, ondem não só ajuda os estudantes de ensino médio a descobrirem novas áreas como também ajuda a organizar e a planejar durante uma decisão importante das suas vidas.)
**Tecnologia:** Python + CSS + Flask + HTML + Banco de Dados

---

## 🎯 O que o sistema faz

(O problema é a dificuldade que os estudantes de ensino medio tem de decidir que curso seguir futuramente.
Nosso publico alvo e estudantes entre 14 a 17 anos de idade que esteja cursando ensinpo médio.
Pretendemos disponibilizar um Quiz onde o usuario pode responder e tera uma porcentagem de qual área suas preferencias mais se encaixam, disponibilizando também algumas opções de organização e planejamento.)

---

## 🔄 Como o grupo trabalha toda semana

1. **Segunda** — revisamos o que cada integrante fez na semana
2. **Durante a semana** — trabalhamos no desenvolvimento do site
3. **Sexta** — fazemos revisão gertal tanto da escrita como do site
4. **Push** — métricas de participação aparecem automaticamente no Actions

---

## 📁 Estrutura do projeto

```
Portal-Vocacional/
│
├── README.md           ← apresentação do projeto
├── BACKLOG.md          ← funcionalidades do MVP e futuras melhorias
│
├── docs/
│   ├── arquitetura.md  ← arquitetura do sistema
│   ├── requisitos.md   ← requisitos funcionais e não funcionais
│   ├── banco-dados.md  ← modelo de dados
│   └── decisoes/
│       ├── ADR-001-framework.md
│       └── ADR-002-banco-dados.md
│
├── diagramas/
│   ├── caso-de-uso.png
│   ├── arquitetura.png
│   ├── fluxo-usuario.png
│   └── modelo-er.png
│
├── evidencias/
│   ├── tela-home.png
│   ├── comparador-cursos.png
│   ├── resultado-vocacional.png
│   └── perfil-faculdade.png
│
├── src/
│   ├── frontend/
│   ├── backend/
│   └── database/
│
├── tests/
│   ├── frontend/
│   └── backend/
│
└── assets/
├── imagens/
└── icones/

```

---

## ⚡ Comandos rápidos

```bash
# Clonar o repositório
git clone <URL>

# Rodar o projeto
pip install -r requirements.txt
python src/app.py

# Rodar os testes
pytest tests/ -v
```
