# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem <autograder.builder.template_library.templates.web_dev.WebDevTemplate object at 0x7f63b0c1cee0> créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback sobre o seu código

Olá! Parabéns pelo seu trabalho até agora. Você já fez muitas partes importantes do projeto corretamente. Vamos abordar alguns pontos que precisam de ajustes e melhorias. Não se preocupe, você está indo muito bem! 😊

## Pontos positivos

- Você fez um ótimo trabalho ao criar a estrutura de dados em `app.js` e garantir que cada item tenha um 'id'. Isso é fundamental para identificar cada notícia de maneira única. 👏
- Fiquei bastante impressionado com a maneira como você lidou com a manipulação do DOM para renderizar dinamicamente os cards de notícia na página inicial. Isso é uma habilidade valiosa e você a fez muito bem! 🎉
- Você fez um bom trabalho ao criar links em cada card que apontam para `detalhes.html` com o 'id' do item na query string. Isso é uma prática muito boa para permitir que a página de detalhes saiba qual notícia exibir. 👍
- Excelente trabalho ao usar `URLSearchParams` para ler o 'id' da URL na página de detalhes e encontrar a notícia correspondente na estrutura de dados. Isso é exatamente o que era necessário para essa parte do projeto. 🌟
- A sua utilização do atributo `alt` em todas as imagens é uma excelente prática de acessibilidade. Mantenha o bom trabalho! 🥇

## Pontos a melhorar

- A sua aplicação não passou em alguns testes porque o sistema de testes esperava encontrar certos elementos HTML ou classes CSS que são específicos do Bootstrap, um framework CSS. No entanto, o projeto especifica que o uso de frameworks como Bootstrap, React, Vue ou Angular é proibido. Portanto, você pode ignorar esses testes falhados. No futuro, certifique-se de ler atentamente os requisitos do projeto para evitar confusões. 😊
- A aplicação está utilizando muitos seletores de ID no CSS. Embora isso não seja necessariamente um problema, é uma boa prática usar classes em vez de IDs para estilização, pois os IDs têm uma especificidade muito alta e podem tornar a manutenção do CSS mais difícil no futuro. Tente refatorar o CSS para usar mais classes e menos IDs. 🎨
- Parece que o diretório 'imgs' não existe ou está vazio. Verifique se o diretório foi carregado corretamente ou se o nome está correto. As imagens são uma parte importante de qualquer site e é essencial que sejam carregadas corretamente. 🖼️

## Recursos para aprendizado

- Como você fez um excelente trabalho ao manipular o DOM para criar conteúdo dinâmico, acho que você pode se interessar por [este guia](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction) para aprender ainda mais sobre o assunto.
- Você também pode achar útil este [tutorial sobre como usar URLSearchParams](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams) para ler parâmetros da query string da URL. É uma habilidade muito útil para dominar!

Lembre-se, a prática leva à perfeição. Continue codificando e explorando diferentes maneiras de resolver problemas. Você está indo muito bem! 💪😊

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