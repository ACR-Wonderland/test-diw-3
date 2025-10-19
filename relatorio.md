# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem 9 créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.62 / 100`**
---
# Feedback do Code Review

Olá! Parabéns pelo seu trabalho no portal de notícias. Você fez um ótimo trabalho ao implementar a estrutura de dados em `app.js` e ao renderizar dinamicamente os cards na `index.html` usando manipulação do DOM. Essas são habilidades muito importantes em desenvolvimento web e você as aplicou bem aqui. 

Vamos falar agora sobre algumas áreas de melhoria e como podemos resolver os problemas que foram encontrados.

## Pontos de Atenção

### HTML

- Parece que você esqueceu de incluir um elemento `<article>` em suas páginas. Lembre-se de que eles são importantes para a semântica e acessibilidade do seu site. Você pode, por exemplo, envolver todo o conteúdo de cada notícia em um elemento `<article>`.

- Seus cards de notícia não possuem imagens. Adicione a tag `<img>` com o atributo `src` apontando para o URL da imagem. Lembre-se também de incluir um atributo `alt` para descrever a imagem, isso é muito importante para a acessibilidade.

- Faltam links internos em seu site. Você pode adicionar um link de volta para a página inicial em `detalhes.html`. Além disso, cada card na página inicial deve ter um link para a página de detalhes, com o ID da notícia na query string.

### CSS

- Seu CSS não está usando medidas relativas, como `em`, `rem`, `%`, `vh`, `vw`. Essas unidades são fundamentais para garantir que seu site seja responsivo e funcione bem em diferentes tamanhos de tela.

- Parece que há uma confusão sobre o uso do Bootstrap. No enunciado do projeto, foi solicitado que não fosse usado nenhum framework, então não se preocupe com a falta do Bootstrap em seu projeto.

### JavaScript

- Ótimo trabalho ao usar a manipulação do DOM para adicionar conteúdo dinamicamente às suas páginas! No entanto, você precisa garantir que cada link nos cards da página inicial aponte para `detalhes.html` com o ID da notícia na query string.

### Outros

- Você usou muitos seletores de ID em seu CSS. Embora os IDs sejam úteis, eles têm uma especificidade muito alta e podem tornar seu CSS difícil de gerenciar. Tente usar classes em vez de IDs sempre que possível.

- A tag `<script>` foi encontrada em seu projeto. Como o objetivo era construir o site sem usar frameworks de JavaScript, essa tag não deveria ser usada.

- O diretório 'imgs' que você está referenciando em seu código JavaScript não existe. Certifique-se de que todas as imagens que você está tentando carregar estejam em um diretório existente.

## Recursos de Aprendizagem

Aqui estão alguns recursos que podem te ajudar a melhorar seu projeto:

- [Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Aprenda a trabalhar com a estrutura de dados JSON em JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Guia completo sobre como usar o atributo 'alt' em imagens para acessibilidade](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Continue trabalhando duro e melhorando suas habilidades! Você está indo muito bem. Se você tiver alguma dúvida, não hesite em perguntar. Estou aqui para ajudar! 😊


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