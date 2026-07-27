# Área de Trabalho — Carneiro & Sérvolo Advocacia

Este repositório organiza os **documentos jurídicos** do escritório de forma
padronizada, para que qualquer pessoa da equipe encontre rapidamente o que
precisa e para que nada se perca.

## Como a organização funciona

A estrutura principal é **por cliente → por processo → por tipo de documento**.
Além disso há uma área de **modelos** (para reaproveitar peças) e uma de
**arquivo** (para casos encerrados).

```
cmx/
├── clientes/          → uma pasta por cliente (o coração do escritório)
│   └── _modelo-cliente/   → copie esta pasta ao cadastrar um novo cliente
├── modelos/           → templates reutilizáveis (petições, contratos, etc.)
├── consultivo/        → trabalhos sem processo (pareceres, contratos avulsos)
└── arquivo/           → clientes/casos encerrados ou inativos
```

## Regras rápidas

1. **Novo cliente?** Copie a pasta `clientes/_modelo-cliente/`, renomeie para o
   nome do cliente e preencha o `README.md` dela.
2. **Novo processo?** Dentro do cliente, copie `processos/_modelo-processo/`.
3. **Nomeie os arquivos com data no início** no formato `AAAA-MM-DD`, por
   exemplo `2026-07-27-peticao-inicial.docx`. Assim eles ficam em ordem
   cronológica automaticamente.
4. **Nunca guarde documentos soltos na raiz** — sempre dentro do cliente,
   modelo, consultivo ou arquivo correspondente.

## Convenção de nomes de pastas

- Use letras minúsculas, sem acento e sem espaço (use hífen): `joao-da-silva`,
  `contrato-locacao`, `processo-0012345`.
- Isso evita problemas de compatibilidade entre sistemas.

> As pastas que começam com `_` (como `_modelo-cliente`) são **modelos de
> estrutura**: não apague, apenas copie.
