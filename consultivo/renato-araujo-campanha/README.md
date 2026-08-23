# Organograma de campanha — Renato Araujo (Angra dos Reis)

Estrutura organizacional de campanha reaproveitada do organograma de eleição
majoritária enviado pelo cliente. **Toda a estrutura (caixas, hierarquia, cores e
conexões) foi mantida**; os nomes das pessoas que constavam no material original
foram removidos e substituídos por linhas em branco para preenchimento.

O único nome inserido é o do candidato, no topo do organograma:

> **RENATO ARAUJO** — Candidato a Deputado Federal 2026 — **Angra dos Reis / RJ**

## Arquivos

| Arquivo | Para que serve |
| --- | --- |
| `2026-08-23-organograma-angra-dos-reis.html` | Versão **editável**. Abra no navegador, clique sobre qualquer linha e digite o nome. |
| `2026-08-23-organograma-angra-dos-reis.pdf` | Versão para **imprimir e preencher à mão** (1 página, paisagem). |
| `2026-08-23-organograma-angra-dos-reis.png` | Imagem para **compartilhar** (WhatsApp, apresentações). |

O HTML é autossuficiente: a fonte está embutida no próprio arquivo, então ele
funciona offline e mantém a aparência em qualquer computador.

### Como preencher pelo navegador

1. Abra o `.html` (duplo clique, ou arraste para o Chrome/Edge).
2. Clique sobre a linha ao lado do ícone de pessoa e digite o nome.
3. Para gerar um PDF já preenchido: `Ctrl + P` → **Salvar como PDF**.
   A frase de instrução no rodapé não sai na impressão.

> Atenção: o texto digitado no navegador **não é salvo** no arquivo `.html`.
> Salve o resultado como PDF ao terminar o preenchimento.

## Estrutura mantida

- **Topo:** candidato
- **Coordenação Geral** (ligada diretamente ao candidato)
- **Conselho Político** (6 vagas) e **Estratégica Política** (2 vagas)
- **Marketing** (6 vagas, uma delas identificada como *video maker*), com os
  blocos derivados **Comunicação**, **Ass. de Imprensa**, **Rede Social / Web** e
  **TV Web**
- **Financeiro** (2 vagas)
- **Cerimonial / Precursora** e **Locutor** (apoio direto)
- **Sete coordenações de base:** Jurídica (eleitoral, criminal, cível), de
  Equipes, Contábil, Galpão / Rua, Religiosa, Assessoria Direta (agenda,
  motorista) e Região / Bairros

Os rótulos em cinza ao lado de algumas linhas (*eleitoral*, *criminal*, *cível*,
*agenda*, *motorista*, *evangélico*, *rua*, *video maker*) são as funções que já
estavam previstas no organograma original — são atribuições, não nomes, por isso
foram preservadas.

## Como alterar a estrutura

O arquivo `.html` é texto puro. Para incluir ou remover uma vaga, duplique ou
apague um bloco `<div class="item">…</div>` dentro da lista correspondente. Para
trocar o nome do candidato, edite o conteúdo da caixa `caixa topo`.
