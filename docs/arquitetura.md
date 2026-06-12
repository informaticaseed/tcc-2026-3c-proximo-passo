# Arquitetura do Sistema

**Grupo:** (nome do grupo)
**Última atualização:** (data)

---

## Diagrama de arquitetura

> Cole aqui o link da imagem, foto ou diagrama em texto.

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
]
```

---

## Separação de camadas

| Camada | Arquivo | Responsabilidade |
|--------|---------|-----------------|
| Web | `app.py` | Rotas e renderização |
| Dados | `repositorio.py` | Todo o SQL |
| Templates | `templates/` | HTML ao usuário |
| Testes | `tests/` | Testes automáticos |

---

## Decisões técnicas

Ver pasta `docs/decisoes/` para os registros de decisão (ADR).
