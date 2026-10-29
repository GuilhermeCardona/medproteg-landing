# MedProteg · Página de vendas

Página de apresentação e venda do MedProteg, plataforma de compliance e LGPD para hospitais, clínicas e laboratórios.

Endereço: https://guilhermecardona.github.io/medproteg-landing/

O produto em si (painel e API de análise com IA) está no repositório [medproteg](https://github.com/GuilhermeCardona/medproteg). As duas partes se ligam: o botão "Ver o painel" leva ao painel, e o logo do painel volta para esta página.

## O que tem na página

- **Apresentação:** proposta de valor para o setor de saúde e um exemplo do resultado de uma análise.
- **Para quem é:** hospitais, clínicas, laboratórios e equipes de jurídico/DPO.
- **Como funciona:** envio do documento, pseudonimização dos dados pessoais e resultado com riscos e recomendações.
- **Avaliação de risco:** quiz de 4 perguntas que calcula o nível de risco e indica um plano.
- **Planos:** Essencial, Mensal e Premium, com contratação pelo WhatsApp.

## Avaliação de risco

Cada resposta de risco soma 1 ponto:

| Pontos | Risco | Plano indicado |
| --- | --- | --- |
| 0 ou 1 | Baixo | Essencial |
| 2 | Médio | Mensal |
| 3 ou 4 | Alto | Premium |

O resultado aparece na própria página, sem enviar nenhum dado. O botão do resultado abre o WhatsApp com o nível de risco já escrito na mensagem.

## Tecnologias

HTML, CSS e JavaScript, sem framework e sem build. Fonte Manrope (Google Fonts) e ícones em SVG próprios.

## Rodar localmente

Abra o `index.html` no navegador.

## Contexto

Projeto interdisciplinar da disciplina Direito, Inovação e Empreendedorismo (PUCRS, 2025), feito com estudantes de Direito, que produziram o conteúdo jurídico. Os planos e preços são simulados.
