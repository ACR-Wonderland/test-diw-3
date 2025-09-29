# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem 9 créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback sobre a Atividade de Portal de Notícias

Olá! Parabéns pelo trabalho feito até agora no seu projeto de Portal de Notícias. Você fez um bom trabalho na implementação da estrutura de dados em `app.js` e na renderização dinâmica dos cards na `index.html`. Também percebi que você fez um bom uso dos elementos semânticos do HTML e suas tags `meta` estão bem configuradas, o que é excelente para SEO. Além disso, todas as suas imagens têm o atributo `alt`, o que é uma ótima prática de acessibilidade. 👍

Porém, alguns testes falharam e eu gostaria de te ajudar a entender por que e como resolver essas questões:

- **Tags `article` e `img` faltantes**: O teste está esperando encontrar um número específico dessas tags, mas não conseguiu. Certifique-se de que você está usando a quantidade necessária dessas tags e que elas estão bem estruturadas. 
- **Links internos para `article`**: Parece que há uma falta de links apontando para tags `article`. Verifique se você criou esses links corretamente.
- **Uso de unidades relativas no CSS**: O teste não encontrou nenhuma unidade relativa (em, rem, %, vh, vw) no seu CSS. Essas unidades são importantes para tornar o site responsivo e adaptável a diferentes tamanhos de tela e dispositivos.
- **Links para o Bootstrap**: O teste está procurando por links para o CSS ou JS do Bootstrap, mas não encontrou nenhum. Como a atividade não permite o uso de frameworks, você pode ignorar esse erro.
- **Links internos**: O teste não encontrou nenhum link interno válido. Verifique se você está usando âncoras corretamente para criar links internos.
- **Classes CSS do Bootstrap**: O teste está procurando por várias classes CSS específicas do Bootstrap (`row`, `col-*`, `text-center`, `d-flex`, `d-*-flex`, `bg-*`), mas não encontrou nenhuma. Novamente, como a atividade não permite o uso de frameworks, você pode ignorar esses erros.
- **Links para `detalhes.html` com o parâmetro de consulta 'id'**: O teste não encontrou nenhum link válido para 'detalhes.html' com o parâmetro de consulta 'id'. Verifique se você está criando esses links corretamente.

Além disso, houve algumas más práticas detectadas:

- **Uso excessivo de seletores de ID**: O teste detectou um número excessivo de seletores de ID. Tente usar classes em vez de IDs sempre que possível, pois as classes são mais reutilizáveis e flexíveis.
- **Tag `script` proibida**: O teste encontrou uma tag `script` em seu HTML. Como a atividade proíbe o uso de JavaScript inline, certifique-se de que todo o seu JavaScript está em um arquivo externo.
- **Diretório 'imgs' não encontrado**: O teste não encontrou o diretório 'imgs'. Verifique se você criou esse diretório e se ele contém todas as imagens necessárias.

Para ajudar a resolver esses problemas, sugiro que você consulte os seguintes recursos de aprendizagem:

- [Guia sobre Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico.](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL.](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Aprenda a trabalhar com a estrutura de dados JSON em JavaScript.](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Guia completo sobre como usar o atributo 'alt' em imagens para acessibilidade.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Espero que este feedback ajude você a melhorar seu projeto. Lembre-se, a prática leva à perfeição. Continue codando! 😊


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