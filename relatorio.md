# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem <autograder.builder.template_library.templates.web_dev.WebDevTemplate object at 0x7fd30cb6cee0> créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback do Código

Olá! Estou aqui para te ajudar a melhorar seu código. Parabéns pelo trabalho até agora e pela iniciativa de aprender mais sobre programação! 

Vamos começar falando sobre o que foi bem feito no seu projeto e, em seguida, vou te dar algumas dicas de como melhorar nos pontos que precisam de atenção.

## Pontos Positivos

- Ótimo trabalho utilizando JavaScript puro para manipular o DOM! Você conseguiu carregar dinamicamente o conteúdo das notícias a partir dos dados no `app.js`, tanto na página inicial quanto nos detalhes. Isso é uma habilidade muito importante e você a aplicou muito bem.
- Seu código JavaScript está bem estruturado e fácil de entender. A organização dos dados em um array de objetos e o uso do método `forEach` para iterar por eles estão corretos.
- Parabéns por usar o objeto `URLSearchParams` para ler o parâmetro 'id' da URL na página de detalhes da notícia. Isso é uma prática avançada e você fez isso corretamente.
- Você fez um bom trabalho garantindo que todas as imagens tenham um texto alternativo. Isso é muito importante para a acessibilidade e SEO.
- Seu código HTML está bem estruturado e fácil de ler. Parabéns por isso!
- A estrutura de arquivos e diretórios está organizada e faz sentido.

## Pontos de Atenção e Sugestões de Melhoria

- Observo que alguns testes falharam porque estavam esperando o uso do Bootstrap, mas o enunciado do exercício especificava que o uso de frameworks é proibido. Portanto, você fez certo em não usar o Bootstrap. No entanto, é importante ler atentamente os requisitos dos testes para evitar confusões. 

- Seu CSS está usando seletores de ID, o que não é uma boa prática. Os IDs são únicos e não podem ser reutilizados, o que limita a eficiência do seu CSS. Tente usar classes em vez de IDs sempre que possível.

- Percebi que você tem uma pasta 'imgs' referenciada no seu código JavaScript, mas ela não existe no seu projeto. Isso está causando um erro, pois o código não consegue encontrar as imagens das notícias. Certifique-se de que todas as pastas e arquivos referenciados no seu código existem e estão no local correto.

- Você precisa adicionar mais tags `article` e `img` no seu HTML. Atualmente, você tem apenas 2 tags `article` e 0 tags `img`, mas os testes requerem 4 de cada. Lembre-se de que cada notícia deve ser um `article` e deve conter uma `img`.

- As regras do CSS devem preferencialmente usar unidades relativas (como em, rem, %, vh, vw), em vez de unidades absolutas (como px). Isso torna seu design mais flexível e responsivo a diferentes tamanhos de tela e configurações de usuário.

- Por fim, certifique-se de que cada notícia na página inicial tenha um link para a página de detalhes com o parâmetro 'id' correto na query string da URL. Atualmente, os testes não estão encontrando esses links.

Aqui estão alguns recursos que podem te ajudar a melhorar seu código:

- [Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Como usar URLSearchParams para ler parâmetros da query string da URL](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Como trabalhar com a estrutura de dados JSON em JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Como usar o atributo 'alt' em imagens para acessibilidade](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

Continue assim e você vai longe! Se tiver alguma dúvida, estou à disposição. Happy coding! 🚀

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