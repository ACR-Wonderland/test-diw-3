# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem <autograder.builder.template_library.templates.web_dev.WebDevTemplate object at 0x7f9997a60ee0> créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback sobre o seu Código

Olá! Espero que esteja tudo bem com você. Parabéns pelo seu esforço em criar este portal de notícias! Você fez um ótimo trabalho, especialmente na manipulação dinâmica do DOM para renderizar o conteúdo das notícias e na implementação da leitura dos parâmetros da URL na página de detalhes. Além disso, é bom ver que todos os elementos de imagem contêm o atributo 'alt', o que é uma ótima prática para a acessibilidade.

No entanto, existem algumas melhorias que podem ser feitas para atender aos requisitos do projeto e melhorar ainda mais o seu código. Vamos passar por elas:

## Melhorias Críticas

1. **Tags `<article>` e `<img>` faltantes**: Os testes estão procurando por um número específico de tags `<article>` e `<img>`. Certifique-se de ter a quantidade correta dessas tags em seu HTML.

2. **Links internos para tags `<article>`**: Os testes estão procurando links internos que apontam para tags `<article>`. Verifique se você tem a quantidade correta desses links.

3. **Uso de medidas relativas no CSS**: Seu CSS deve usar unidades relativas (como em, rem, %, vh, vw) para medidas. Isso torna o layout mais flexível e adaptável a diferentes tamanhos de tela.

4. **Links internos e classes CSS faltantes**: Os testes estão procurando por um número específico de links internos e classes CSS em seu código. Por favor, verifique se eles estão presentes e corretos.

5. **Links para a página de detalhes**: Os testes estão procurando por links que apontam para 'detalhes.html' com o parâmetro de consulta 'id'. Certifique-se de que esses links estão presentes e corretos.

## Melhorias Adicionais

1. **Uso excessivo de IDs**: Tente limitar o uso de IDs em seu CSS. Eles têm uma especificidade muito alta, o que pode tornar o seu CSS difícil de gerenciar à medida que o projeto cresce.

2. **Uso de tags `<script>`**: A tag `<script>` foi encontrada em seu código. Como este projeto proíbe o uso de frameworks de JavaScript, você não deve precisar dessa tag.

3. **Diretório 'imgs' faltante**: Os testes não conseguiram encontrar o diretório 'imgs'. Certifique-se de que ele existe e contém todas as imagens necessárias para o projeto.

## Recursos para Aprendizado

Aqui estão alguns recursos que podem ajudar você a entender e corrigir os problemas mencionados:

- [Guia sobre Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Aprenda a trabalhar com a estrutura de dados JSON em JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Guia completo sobre como usar o atributo 'alt' em imagens para acessibilidade](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Espero que isso ajude! Continue praticando e não hesite em pedir ajuda se precisar. Você está indo muito bem e estou ansioso para ver o seu progresso! 👍


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