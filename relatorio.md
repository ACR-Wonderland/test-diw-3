# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem 9 créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback do Código

Olá! Parabéns pelo trabalho feito até agora no seu portal de notícias. Você fez um ótimo trabalho criando a estrutura de dados em `app.js` e carregando o conteúdo dinamicamente na `index.html` e `detalhes.html`. Além disso, você fez um excelente trabalho ao garantir que todas as imagens tenham um atributo 'alt', o que é uma ótima prática de acessibilidade.

No entanto, existem algumas áreas que precisam ser aprimoradas para passar em todos os testes. Vamos abordá-las uma por uma:

## 1. Uso de Bootstrap e Classes CSS

Parece que os testes estão esperando que você use o Bootstrap, mas você escolheu não usar nenhum framework CSS. Isso não é necessariamente um problema, mas está fazendo com que você falhe em vários testes que estão procurando por classes específicas do Bootstrap, como 'row', 'col-*', 'text-center', 'd-flex', 'd-*-flex' e 'bg-*'. 

Se a intenção era não usar o Bootstrap, você pode ignorar esses testes. No entanto, se você quiser passar em todos eles, recomendamos que você inclua o Bootstrap em seu projeto e use as classes necessárias.

## 2. Uso de Medidas Relativas no CSS

O teste `uses_relative_units` falhou porque você está usando principalmente pixels em seu CSS. Recomendamos a utilização de unidades relativas como em, rem, %, vh e vw, que são mais flexíveis e melhoram a responsividade do seu site.

## 3. Uso Excessivo de Seletores de ID

O teste `check_id_selector_over_usage` falhou porque você está usando muitos seletores de ID em seu CSS. Como regra geral, é melhor usar classes em vez de IDs para estilizar elementos, pois as classes são reutilizáveis e têm uma especificidade menor, o que torna seu CSS mais fácil de gerenciar.

## 4. Uso de Tags Script

O teste `has_forbidden_tag` falhou porque você está usando a tag `<script>` em seu HTML. Isso é proibido por razões de segurança e para garantir que todo o seu JavaScript esteja contido em arquivos .js separados. Remova todas as tags `<script>` do seu HTML.

## 5. Diretório de Imagens

O teste `check_dir_exists` falhou porque o diretório 'imgs' que você está referenciando em seu JavaScript não existe. Certifique-se de que todas as imagens que você está usando estão presentes nesse diretório.

## 6. Links para Artigos

O teste `check_internal_links_to_article` falhou porque não há links suficientes apontando para tags `<article>`. Certifique-se de que cada card de notícia na `index.html` seja envolto em um link que aponte para a `detalhes.html` com o ID da notícia como parâmetro de consulta.

## 7. Links para Detalhes da Notícia

O teste `link_points_to_page_with_query_param` falhou porque você não tem links suficientes apontando para 'detalhes.html' com o parâmetro de consulta 'id'. Certifique-se de que cada card de notícia na `index.html` tenha um link que aponte para a `detalhes.html` com o ID da notícia como parâmetro de consulta.

---

Espero que essas sugestões sejam úteis! Lembre-se, a prática leva à perfeição. Continue codificando e não hesite em pedir ajuda se precisar. Você está indo muito bem até agora, então continue assim! 💪👍


---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Detalhes do Teste |
|:---|:---|:---|
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Verifies that a specific HTML tag appears a minimum number of times.*<br>**Parâmetros:** <sub>`tag`: `article`, `required_count`: `4`</sub> |
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Verifies that a specific HTML tag appears a minimum number of times.*<br>**Parâmetros:** <sub>`tag`: `img`, `required_count`: `5`</sub> |
| Revisar | `link` | **Teste:** `check_internal_links_to_article`<br>**O que foi verificado:** *Checks for a minimum number of internal anchor links pointing to IDs on <article> tags.*<br>**Parâmetros:** <sub>`required_count`: `4`</sub> |
| Revisar | `responsivity` | **Teste:** `uses_relative_units`<br>**O que foi verificado:** *Check if the css file uses relative units like em, rem, %, vh, vw.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_bootstrap_linked`<br>**O que foi verificado:** *Verifies that the Bootstrap framework (CSS or JS) is linked in the HTML file.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_internal_links`<br>**O que foi verificado:** *Checks for a minimum number of internal anchor links pointing to valid element IDs.*<br>**Parâmetros:** <sub>`required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Checks for the presence of specific CSS classes, with wildcard support, a minimum number of times.*<br>**Parâmetros:** <sub>`class_names`: `['row']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Checks for the presence of specific CSS classes, with wildcard support, a minimum number of times.*<br>**Parâmetros:** <sub>`class_names`: `['col-*']`, `required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Checks for the presence of specific CSS classes, with wildcard support, a minimum number of times.*<br>**Parâmetros:** <sub>`class_names`: `['text-center']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Checks for the presence of specific CSS classes, with wildcard support, a minimum number of times.*<br>**Parâmetros:** <sub>`class_names`: `['d-flex', 'd-*-flex']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Checks for the presence of specific CSS classes, with wildcard support, a minimum number of times.*<br>**Parâmetros:** <sub>`class_names`: `['bg-*']`, `required_count`: `1`</sub> |
| Revisar | `linking_and_integrity` | **Teste:** `link_points_to_page_with_query_param`<br>**O que foi verificado:** *Checks for anchor tags linking to a specific page with a required query string parameter.*<br>**Parâmetros:** <sub>`target_page`: `detalhes.html`, `query_param`: `id`, `required_count`: `3`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `check_id_selector_over_usage`<br>**O que foi verificado:** *Counts the number of ID selectors used and penalizes if it exceeds max_allowed.*<br>**Parâmetros:** <sub>`max_allowed`: `2`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `has_forbidden_tag`<br>**O que foi verificado:** *Checks for the presence of a forbidden HTML tag.*<br>**Parâmetros:** <sub>`tag`: `script`</sub> |
| Corrigir (Penalidade) | `project_structure` | **Teste:** `check_dir_exists`<br>**O que foi verificado:** *Checks if a specific directory exists in the submission.*<br>**Parâmetros:** <sub>`dir_path`: `imgs`</sub> |


---
> Caso queira tirar uma dúvida específica, entre em contato com o Chapter.