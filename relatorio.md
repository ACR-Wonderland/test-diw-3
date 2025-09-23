# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem 9 créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback do Código

Olá!

Parabéns pelo seu progresso até agora! Você fez um bom trabalho na implementação da estrutura de dados em `app.js` e na renderização dinâmica dos cards na `index.html` usando manipulação do DOM. Além disso, você conseguiu criar links em cada card que apontam para `detalhes.html` com o 'id' do item na query string. Muito bem!

Agora, vamos para algumas dicas para melhorar ainda mais o seu código:

## Pontos de Atenção

- Parece que você tem algumas tags `<article>` faltando no seu HTML. Como esse é um dos requisitos para passar no teste, seria ideal adicionar mais 2 tags `<article>` no seu HTML.

- A tag `<img>` também está faltando no seu HTML. Certifique-se de adicionar as tags `<img>` correspondentes para passar no teste.

- Vamos evitar o uso excessivo de seletores de ID no CSS. A regra geral é usar classes para estilização e IDs para JavaScript. Isso ajuda a manter o CSS limpo e evita problemas de especificidade.

- Notei que você está usando medidas absolutas (px) no seu CSS. Para tornar o seu site mais responsivo, seria interessante usar medidas relativas como (em, rem, %, vh, vw).

- O seu diretório 'imgs' não existe. Certifique-se de que o diretório 'imgs' exista e que todas as imagens estejam corretamente armazenadas nele.

- Embora o Bootstrap seja uma ótima ferramenta, o uso dele não é permitido neste projeto. Portanto, remova qualquer referência ao Bootstrap do seu código.

- Foi detectado o uso da tag `<script>`, que é proibida neste projeto. Certifique-se de remover todas as ocorrências dessa tag.

## Sugestões de Melhoria

- Para resolver o problema dos links internos, você pode adicionar âncoras (`<a>`) no seu HTML que apontam para diferentes seções da sua página.

- A adição de classes CSS como 'row', 'col-*', 'text-center', 'd-flex', 'd-*-flex', 'bg-*' vai ajudar a passar nos testes e tornar o seu site mais responsivo.

- Para corrigir o teste `link_points_to_page_with_query_param`, certifique-se de que seus links apontem para 'detalhes.html' com o parâmetro de consulta 'id'.

## Recursos de Aprendizagem

Para te ajudar a corrigir esses problemas, aqui estão alguns recursos que você pode achar úteis:

- [Guia sobre Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico.](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL.](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Aprenda a trabalhar com a estrutura de dados JSON em JavaScript.](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Guia completo sobre como usar o atributo 'alt' em imagens para acessibilidade.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Lembre-se, a prática leva à perfeição. Continue trabalhando duro e você vai melhorar cada vez mais!

Bons estudos!

---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Detalhes do Teste |
|:---|:---|:---|
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que ele faz:** *Verifica se uma tag HTML específica aparece um número mínimo de vezes.*<br>**Parâmetros:** <sub>`tag`: `article`, `required_count`: `4`</sub> |
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que ele faz:** *Verifica se uma tag HTML específica aparece um número mínimo de vezes.*<br>**Parâmetros:** <sub>`tag`: `img`, `required_count`: `5`</sub> |
| Revisar | `link` | **Teste:** `check_internal_links_to_article`<br>**O que ele faz:** *Verifica a existência de um número mínimo de links âncora internos apontando para IDs em tags `<article>`.*<br>**Parâmetros:** <sub>`required_count`: `4`</sub> |
| Revisar | `responsivity` | **Teste:** `uses_relative_units`<br>**O que ele faz:** *Verifica se o arquivo CSS usa unidades relativas como em, rem, %, vh, vw.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_bootstrap_linked`<br>**O que ele faz:** *Verifica se o framework Bootstrap (CSS ou JS) está vinculado no arquivo HTML.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_internal_links`<br>**O que ele faz:** *Verifica a existência de um número mínimo de links âncora internos que apontam para IDs de elementos válidos.*<br>**Parâmetros:** <sub>`required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que ele faz:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['row']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que ele faz:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['col-*']`, `required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que ele faz:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['text-center']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que ele faz:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['d-flex', 'd-*-flex']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que ele faz:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['bg-*']`, `required_count`: `1`</sub> |
| Revisar | `linking_and_integrity` | **Teste:** `link_points_to_page_with_query_param`<br>**O que ele faz:** *Verifica a existência de tags âncora que levam a uma página específica com um parâmetro de query string obrigatório.*<br>**Parâmetros:** <sub>`target_page`: `detalhes.html`, `query_param`: `id`, `required_count`: `3`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `check_id_selector_over_usage`<br>**O que ele faz:** *Conta o número de seletores de ID usados e penaliza se exceder o máximo permitido.*<br>**Parâmetros:** <sub>`max_allowed`: `2`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `has_forbidden_tag`<br>**O que ele faz:** *Verifica a presença de uma tag HTML proibida.*<br>**Parâmetros:** <sub>`tag`: `script`</sub> |
| Corrigir (Penalidade) | `project_structure` | **Teste:** `check_dir_exists`<br>**O que ele faz:** *Verifica se um diretório específico existe no envio.*<br>**Parâmetros:** <sub>`dir_path`: `imgs`</sub> |


---
> Caso queira tirar uma dúvida específica, entre em contato com o Chapter.