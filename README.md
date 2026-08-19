# Calculadora EAC

Site estático e responsivo para os professores calcularem a nova nota após o EAC.

## Regra de cálculo

A aplicação reproduz literalmente a fórmula da planilha `eac.xlsx`:

```text
((((10 - EAC) / 10) * Média) + EAC)
```

Exemplo da planilha:

- Média: `8,0`
- EAC: `4,5`
- Nota nova: `8,9`

## Características

- escala validada de 0 a 10;
- aceita vírgula ou ponto decimal;
- cálculo automático ao preencher os dois valores;
- resultado apresentado com uma casa decimal;
- memória de cálculo exibida na tela;
- layout responsivo para celular, tablet e computador;
- aplicação 100% estática, sem backend e sem armazenamento de dados.

O arquivo `index.html` contém toda a aplicação e pode ser publicado diretamente pelo GitHub Pages.