# Tarifário Younique Tailor Tours — App de Cotações

App web (ficheiro único `index.html`, sem dependências, funciona offline) baseada no
**Tarifário Geral Serviços Portugal FIT 2027** (válido 01/01/2027 a 31/12/2027). Espanha mantém FIT 2026 até novo tarifário..

## Como usar
1. Abrir `index.html` num browser (basta duplo-clique no ficheiro).
2. **Separador "Tarifário"** — consultar todas as tabelas: traslados privativos
   (Lisboa, Porto, Madeira, Açores, Algarve, Coimbra), tours privativos,
   experiências, tours regulares e condições gerais.
3. **Separador "Cotação"** — construir cotações:
   - Traslados: viatura calculada pelo nº de pax, acréscimo noturno +25% (22h–06h),
     assistência de aeroporto (220 €, obrigatória a partir de 06 pax).
   - Tours privativos com guia oficial opcional (HD/FD conforme o destino: Lisboa/Porto 315/430 €, ilhas 480/640 €, Coimbra/Faro 295/400 €).
   - Experiências por pax (Universidade de Coimbra, Coimbra by Night com Fado,
     Walking Tour Petiscos, Bairrada Wine Tour).
   - Reserva de mesa em restaurante (10 €/pax/refeição).
   - Total NET, resumo em texto, envio por e-mail para bookings@ e impressão.

## Atualizar para 2028
Os preços estão no bloco `DADOS DO TARIFÁRIO 2027` no início do `<script>` em
`index.html` (constantes `TRANSFERS`, `TOURS`, `EXPS`, `REGULARS`, `OPCIONAIS`).
Basta substituir os valores e o texto de validade no cabeçalho.

Os valores servem apenas para cotação; os serviços só ficam reservados após
confirmação formal (Fatura Proforma) da Younique Tailor Tours.
