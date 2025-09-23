# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem <autograder.builder.template_library.templates.web_dev.WebDevTemplate object at 0x7f2e9bff8f10> créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback do Código

Olá! Acabei de revisar o seu código e gostaria de parabenizá-lo pelo trabalho feito até agora! 👏 Você fez um ótimo trabalho ao implementar a funcionalidade de carregar dinamicamente as notícias na página principal e os detalhes da notícia em uma página separada. Isso é uma parte fundamental do projeto e você fez isso muito bem!

Agora, vamos abordar alguns pontos que precisam de atenção. Não se preocupe, estou aqui para ajudar!

## Pontos a serem melhorados

1. **Tags `<article>`**: O teste de validação apontou que você não está usando a quantidade necessária de tags `<article>`. No seu código, você está usando apenas duas tags `<article>`, uma para cada página. O teste espera pelo menos quatro. Isso pode ser facilmente resolvido adicionando mais tags `<article>` na sua página. Lembre-se que a tag `<article>` é usada para encapsular um conteúdo independente dentro de um documento.

2. **Tags `<img>`**: O teste de validação também apontou que você não está usando a quantidade necessária de tags `<img>`. No seu código, você não está usando nenhuma tag `<img>`. O teste espera pelo menos cinco. Você pode solucionar isso adicionando tags `<img>` para as imagens das notícias tanto na página inicial quanto na página de detalhes.

3. **Links internos**: O teste de validação mostrou que você não está usando links internos em seu projeto. Os links internos são importantes para a navegação do usuário no site. Você pode adicionar links internos usando a tag `<a>` com o atributo `href` apontando para a página interna desejada.

4. **Classe CSS**: O teste de validação indicou que algumas classes CSS esperadas não estão presentes no seu projeto. Certifique-se de usar as classes CSS corretas para estilizar os elementos do seu site. 

5. **Uso de ID**: O teste de validação apontou um excesso de uso de seletores de ID no seu CSS. O uso excessivo de seletores de ID pode tornar o seu CSS difícil de gerenciar e não é uma boa prática. Tente usar classes em vez de IDs sempre que possível.

6. **Diretório 'imgs' não encontrado**: O teste de validação indicou que o diretório 'imgs' não existe. Certifique-se de que você tenha criado este diretório e que ele contém todas as imagens que você pretende usar no seu site.

## Boas práticas

Você fez um excelente trabalho garantindo que todas as imagens tenham o atributo 'alt'. Isso é essencial para a acessibilidade do site e é uma ótima prática! 👍

Também aprecio o fato de que você forneceu detalhes completos nas tags `<head>` de suas páginas HTML. Isso é muito importante para a otimização de mecanismos de busca (SEO) e para fornecer informações relevantes ao navegador.

Para melhorar ainda mais, aqui estão alguns recursos úteis que você pode consultar:

- [Manipulação do DOM (Document Object Model)](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Como usar URLSearchParams para ler parâmetros da query string da URL](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Trabalhando com a estrutura de dados JSON em JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Como usar o atributo 'alt' em imagens para acessibilidade](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Espero que essas sugestões sejam úteis! Continue trabalhando duro e você chegará lá! 🚀


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