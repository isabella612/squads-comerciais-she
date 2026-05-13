# Squads Comerciais — Software House Exponencial

Squads de vendas para a **Imersão Software House 10x** e a **Imersão ExponencIA**.
Pipeline completo: prospecção → qualificação → apresentação → fechamento.

---

## Squads disponíveis

| Squad | Produto | Agentes |
|-------|---------|---------|
| `sh10x-commercial` | Imersão Software House 10x | Adilson 10x · Thamyres 10x · Robson 10x · Isadora 10x |
| `exponencia-commercial` | Imersão ExponencIA | Adilson IA · Thamyres IA · Robson IA · Isadora IA |

---

## Pré-requisitos

1. **Claude Code** instalado (`npm i -g @anthropic-ai/claude-code`)
2. **ExpxAgents** configurado no projeto — pasta `_expxagents/` presente na raiz
3. Arquivo `_expxagents/_memory/company.md` preenchido com o perfil da sua empresa

---

## Instalação em outra máquina

### 1. Clone ou copie as squads

Se você tem o repositório:
```bash
git clone <url-do-repositorio>
```

Se está copiando manualmente, copie a pasta `squads/commercial/` para a raiz do seu projeto ExpxAgents.

### 2. Verifique a estrutura esperada

```
seu-projeto/
├── _expxagents/
│   └── _memory/
│       ├── company.md       ← configure com o perfil da sua empresa
│       └── preferences.md
└── squads/
    └── commercial/
        ├── sh10x-commercial/
        └── exponencia-commercial/
```

### 3. Configure o perfil da empresa

Edite `_expxagents/_memory/company.md` com os dados da sua empresa.
O squad usa esse arquivo para personalizar os scripts de venda.

### 4. (Opcional) Limpe as memórias de execução

Os arquivos `_memory/memories.md` dentro de cada squad guardam histórico de execuções.
Ao instalar em uma nova máquina, você pode apagá-los para começar do zero — eles serão recriados automaticamente.

---

## Como rodar

No Claude Code, dentro do projeto:

```
/expxagents run sh10x-commercial
```

```
/expxagents run exponencia-commercial
```

---

## Materiais incluídos

Cada squad vem com os materiais de referência usados pelos agentes:

**sh10x-commercial**
- `PLAYBOOK COMERCIAL 10x claud.pdf` — Playbook completo da Imersão 10x
- `Perfil de cliente 10x (1).pdf` — Perfil do cliente ideal
- `_data/` — Cases, depoimentos, datas, playbook de prospecção
- `transcricoes/` — Transcrições de depoimentos de clientes
- `Videos/` — Depoimento em vídeo (Daniel / ACBr)

**exponencia-commercial**
- `Playbook - ExponencIA (1).pdf` — Playbook da Imersão ExponencIA
- `_data/` — Dados do produto e playbook completo
