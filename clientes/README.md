# Clientes

Cada cliente do escritório tem **uma pasta própria** aqui dentro.

## Como cadastrar um novo cliente

1. Copie a pasta `_modelo-cliente/`.
2. Renomeie para o nome do cliente (minúsculas, sem acento, com hífen).
   Exemplos: `joao-da-silva`, `construtora-alfa-ltda`.
3. Abra o `README.md` da nova pasta e preencha os dados do cliente.

## O que fica dentro de cada cliente

```
nome-do-cliente/
├── README.md          → dados de contato e resumo do cliente
├── cadastro/          → documentos pessoais, procuração, contrato de honorários
└── processos/         → uma pasta por processo/caso do cliente
    └── _modelo-processo/
```

> Dica: mantenha os nomes em ordem alfabética para facilitar a busca. Quando um
> cliente encerrar o relacionamento com o escritório, mova a pasta dele para
> `arquivo/`.
