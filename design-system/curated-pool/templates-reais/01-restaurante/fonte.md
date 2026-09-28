# 01 — Restaurante

Levantamento em 2026-09-28, refeito com os critérios de classificação por seções e conversão. Só templates GRATUITOS. Preço e licença lidos da página de cada fonte.

**Como as seções foram contadas:** pelo HTML dos demos, olhando os nomes das camadas (Framer) e as classes de seção (Webflow). É uma contagem aproximada, não visual. Onde a página carrega conteúdo só depois do JavaScript, a contagem sai menor que a real (Qitchen, Pastora). Layout de 2 colunas, 1 CTA por seção, motion e performance **não foram verificados**: o Chromium do container não confia no certificado do proxy, então não abri os sites ao vivo.

## SELEÇÃO PROPOSTA (aguardando aprovação do Lyon)

| Tier | Template | Fonte | Seções (aprox.) | Link | Demo |
|---|---|---|---|---|---|
| Ouro | Brewni | Framer (Free), Mezario | 10 | https://www.framer.com/marketplace/templates/brewni/ | https://brewni.framer.website/ |
| Prata | Umami | Framer (Free), Istiaq (EV Studio) | 6 | https://www.framer.com/marketplace/templates/umami/ | https://umami-template.framer.website/ |
| Bronze | Foodee | Framer (Free), Anvics | 5 | https://www.framer.com/marketplace/templates/foodee/ | https://foodee.framer.website/ |

Alternativa de Ouro para fine dining: Aveline Dining (9 seções, Nestory), https://www.framer.com/marketplace/templates/aveline-dining/. Tem a estética mais próxima do Old Money, mas não tem FAQ nem CTA final, itens que o seu Ouro pede.

## CRITÉRIOS DE CLASSIFICAÇÃO

### Por número de seções:
- Bronze (Foodee): 5. Hero, sobre, diferenciais, prova social, contato. Sem FAQ, sem galeria, sem pricing.
- Prata (Umami): 6. Hero, sobre, cardápio, prova social (reviews e depoimentos), contato, footer. **Não tem FAQ**, que o Prata pede.
- Ouro (Brewni): 10. Hero, sobre, diferenciais, prova social com números, galeria, FAQ, blog, contato, CTA final, footer. Sem pricing, que não se aplica a restaurante. Está 1 acima do teto de 9.

### Arquétipo de conversão:
- Bronze: Conversão (promessa, diferenciais, prova, contato).
- Prata: Conversão (hero direto para reserva, cardápio, prova).
- Ouro: Storytelling (marca, ambiente e comunidade antes da reserva).
- Restaurante não se encaixa em Autoridade. Não forcei.

### Estilo visual:
- Bronze: Bold Minimalism (fundo vermelho, tipografia grande).
- Prata: Bold Minimalism (verde escuro, tipografia grande, CTA "Book a table").
- Ouro: Bold Minimalism (verde e laranja, tipografia grande, CTA em laranja).
- Dark Mode não foi priorizado: a regra é para tech, fintech e academia, não restaurante.

### Boas práticas aplicadas:
- [ ] Layout 2 colunas: não verificado
- [ ] 1 CTA por seção: não verificado
- [ ] Prova social estratégica: presente nos 3 (posição na página não checada)
- [ ] Performance: não medida
- [ ] Mobile-first: não testado

## Todos os candidatos, por número de seções

| Template | Autor | Seções (aprox.) | Faixa pela contagem | Observação |
|---|---|---|---|---|
| Brewni | Mezario | 10 | Ouro (+1) | Único com FAQ e CTA final |
| Aveline Dining | Nestory | 9 | Ouro | Sem FAQ, sem CTA final |
| Luna Rossa | Mehanuz Meghla | 8 | Ouro | Padaria, tem blog |
| Foodly | Anayatul Islam | 8 | Ouro | Colorido e informal |
| Sushi | Framebucket | 8 | Ouro | Tem blog |
| Club 54 | Michał Kielar | 8 | Ouro | Minimalista, editorial |
| Sofra | Framebucket | 7 | Ouro | Escuro com dourado |
| Ninth Nour | Oleksandr Demydov | 7 | Ouro | Café |
| Zeal Taste (Webflow) | ZealousWeb | 7 | Ouro | Hero, destaque, sobre, menu, depoimentos, reserva, footer |
| Umami | Istiaq (EV Studio) | 6 | Prata | Sem FAQ |
| The Burger | Yana TRC | 4-5 | Bronze | Vários blocos de reserva, pode ter CTAs competindo |
| Foodee | Anvics | 5 | Bronze | Contagem possivelmente incompleta |
| Qitchen | Pawel Gola | não medido | | Conteúdo carregado por JS |
| Pastora | Framebite | não medido | | Conteúdo carregado por JS |
| CoffeeStyle (Webflow) | Webflow | não medido | | Loja com carrinho, foge do escopo |

## Fontes pesquisadas

### Webflow (filtro FREE)
Só 2 templates gratuitos encontrados nas buscas restaurant, food, cafe, bistro, menu, pizza, bar e coffee: Zeal Taste (https://webflow.com/templates/html/zealtaste-food-website-template) e CoffeeStyle (https://webflow.com/templates/html/coffeestyle-business-website-template).

### Framer (filtro FREE)
Categoria `restaurant`: 24 templates, 13 gratuitos. Todos na tabela acima ou no grupo dos não medidos, com link em https://www.framer.com/marketplace/templates/category/restaurant/.

### Astro Themes
Varri os 687 temas. Os de restaurante e café são todos **pagos** (Tasteful $99 ×2, Lime Restaurant, Artisan Coffee). **Nenhum gratuito.**

### 21st.dev
**Não encontrado.** A busca é renderizada no navegador e não devolveu componentes por HTTP.

### Awwwards
**Sem acesso.** Conexão resetada pelo proxy nas 3 tentativas. As 3 referências visuais ficam pendentes.

## Pendências

- Aprovação do Lyon da seleção Ouro, Prata e Bronze.
- Liberar o Awwwards na rede do ambiente.
- Verificar 2 colunas, 1 CTA, motion e performance nos 3 escolhidos, com navegador ou com o Lyon abrindo os demos.
- Nenhum candidato de Prata tem FAQ. Para cumprir o seu Prata, o FAQ teria de ser adicionado na hora de construir.
