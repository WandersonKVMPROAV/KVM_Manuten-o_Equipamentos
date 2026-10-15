# Painel de Manutenção — KVM Pro AV

Painel interno para acompanhamento de equipamentos em manutenção: da chegada na KVM Pro AV até o envio de volta ao cliente.

## O que o painel mostra
- Quantos equipamentos estão em manutenção agora
- Em que etapa cada um está (recebido, em assistência, orçamento/proposta, aprovado, retornado/em bancada, pronto para envio, enviado ao cliente)
- Alertas de equipamentos parados há muito tempo em uma etapa
- Lista completa filtrável por cliente, tipo de equipamento e etapa

## Como abrir
Basta abrir o arquivo `index.html` no navegador, ou publicar via GitHub Pages (Settings → Pages → Branch: main → pasta `/root`).

Os dados ficam salvos dentro do próprio painel (não depende de planilha externa depois de publicado).

## Resumo para TV (AdMooh)
`resumo.html` é uma página independente do painel, em 16:9 e tema escuro, sem barra lateral, feita para ser exibida no AdMooh.
Ela lê os dados de `index.html` (mesma pasta) a cada 5 minutos e recarrega sozinha a cada 60 minutos.
Endereço: `https://wandersonkvmproav.github.io/KVM_Manuten-o_Equipamentos/resumo.html`
