# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem <autograder.builder.template_library.templates.web_dev.WebDevTemplate object at 0x7f8ebcc6cee0> créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback da Avaliação de Código

Olá! Parabéns pelo trabalho que você fez até agora no portal de notícias. Você fez um ótimo trabalho com a manipulação do DOM para criar conteúdo dinâmico e a utilização de URLSearchParams para ler parâmetros da URL. 👍

No entanto, existem alguns pontos que precisamos ajustar para que seu projeto atenda a todos os requisitos da atividade. Vamos lá!

## Pontos de Atenção

- **Uso de Bootstrap**: De acordo com as orientações da atividade, o uso de frameworks como o Bootstrap é proibido. No entanto, alguns dos testes falharam porque esperavam encontrar classes do Bootstrap no seu código. Isso indica que os testes podem estar configurados incorretamente. Nesse caso, você não precisa se preocupar com essas falhas de teste.

- **Uso excessivo de seletores de ID**: Os IDs são ótimos para referenciar elementos únicos, mas usar muitos deles pode tornar seu CSS difícil de gerenciar e menos eficiente. Tente usar classes em vez de IDs sempre que possível. Seu código atualmente usa 7 seletores de ID, mas o limite recomendado é 2.

- **Imagens**: Parece que você está tentando usar imagens do diretório `imgs`, mas ele não existe no seu projeto. Certifique-se de que o diretório e as imagens que você está tentando usar existem.

- **Tags `<article>` e `<img>`**: O teste indica que alguns elementos `<article>` e `<img>` estão faltando. Certifique-se de que você está criando esses elementos para cada notícia em `index.html` e também em `detalhes.html`.

- **Links para detalhes da notícia**: Cada card de notícia em `index.html` deve ter um link para `detalhes.html` com o ID da notícia na query string (ex: `detalhes.html?id=1`). Verifique se você está criando esses links corretamente.

- **Unidades relativas no CSS**: Tente usar unidades relativas (em, rem, %, vh, vw) em vez de unidades absolutas no seu CSS. Isso tornará seu layout mais flexível e responsivo.

## Sugestões de Melhoria

Aqui estão algumas dicas que podem te ajudar a corrigir os problemas mencionados:

- **Uso excessivo de seletores de ID**: Tente substituir alguns dos seus IDs por classes. Por exemplo, você pode mudar `id="noticias-container"` para `class="noticias-container"` e atualizar o seu JavaScript e CSS para referenciar a classe em vez do ID.

- **Imagens**: Verifique o caminho para o diretório `imgs` e certifique-se de que todas as imagens mencionadas em `app.js` estão presentes nesse diretório.

- **Tags `<article>` e `<img>`**: Em `app.js`, você está criando um elemento `<article>` para cada notícia e um elemento `<img>` dentro do link de cada notícia. Verifique se esses elementos estão sendo criados corretamente e se estão aparecendo no HTML final.

- **Links para detalhes da notícia**: Em `app.js`, você está criando um link para `detalhes.html` com o ID da notícia na query string. Verifique se o valor do ID está sendo inserido corretamente na URL.

- **Unidades relativas no CSS**: Experimente substituir algumas das suas unidades absolutas (como `px`) por unidades relativas (como `em`, `rem`, `%`, `vh`, `vw`). Por exemplo, você pode mudar `padding: 1rem;` para `padding: 1em;`.

## Recursos de Aprendizagem

Aqui estão alguns recursos que podem te ajudar a entender melhor os conceitos envolvidos:

- Se você tiver dúvidas sobre como manipular o DOM para criar conteúdo dinâmico, dê uma olhada neste [guia sobre Manipulação do DOM](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction).
  
- Se você quiser saber mais sobre como usar URLSearchParams para ler parâmetros da query string da URL, este [tutorial sobre URLSearchParams](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams) pode ser útil.

- Se você quiser aprender mais sobre como trabalhar com a estrutura de dados JSON em JavaScript, confira este [guia sobre JSON](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON).

- Se você quiser saber mais sobre como usar o atributo 'alt' em imagens para acessibilidade, este [guia sobre o atributo 'alt'](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img) pode ser útil.

Tenho certeza de que você está bem perto de completar este projeto com sucesso. Continue trabalhando duro e não hesite em pedir ajuda se precisar. Você está indo muito bem! 💪


---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Detalhes do Teste |
|:---|:---|:---|
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`tag`: `article`, `required_count`: `4`</sub> |
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`tag`: `img`, `required_count`: `5`</sub> |
| Revisar | `link` | **Teste:** `check_internal_links_to_article`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`required_count`: `4`</sub> |
| Revisar | `responsivity` | **Teste:** `uses_relative_units`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_bootstrap_linked`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_internal_links`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`class_names`: `['row']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`class_names`: `['col-*']`, `required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`class_names`: `['text-center']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`class_names`: `['d-flex', 'd-*-flex']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`class_names`: `['bg-*']`, `required_count`: `1`</sub> |
| Revisar | `linking_and_integrity` | **Teste:** `link_points_to_page_with_query_param`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`target_page`: `detalhes.html`, `query_param`: `id`, `required_count`: `3`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `check_id_selector_over_usage`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`max_allowed`: `2`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `has_forbidden_tag`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`tag`: `script`</sub> |
| Corrigir (Penalidade) | `project_structure` | **Teste:** `check_dir_exists`<br>**O que foi verificado:** *Descrição não disponível.*<br>**Parâmetros:** <sub>`dir_path`: `imgs`</sub> |


---
> Caso queira tirar uma dúvida específica, entre em contato com o Chapter.