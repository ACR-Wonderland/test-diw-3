# Relatório de Desempenho - Portal de Notícias Dinâmico
<sup>Este é um feedback gerado por IA e pode conter erros. Você tem 9 créditos restantes.</sup>

Olá, **ArthurCRodrigues**! Aqui está um feedback detalhado sobre sua atividade.
> **Nota Final:** **`68.38 / 100`**
---
# Feedback sobre o Projeto

Olá! Parabéns pelo trabalho no seu portal de notícias. Você fez um grande progresso e eu gostaria de apontar alguns aspectos positivos antes de nos aprofundarmos em áreas de melhoria.

## Pontos Positivos

- Primeiramente, ótimo trabalho na estruturação dos dados em `app.js`. Você criou um array de objetos bem estruturado com todos os campos necessários para cada notícia, incluindo um 'id' único para cada item. Isso é fundamental para carregar dinamicamente as informações no site.
- Sua implementação de manipulação do DOM em `app.js` para renderizar dinamicamente os cards de notícia na página inicial está correta. Você fez um bom uso dos métodos `document.createElement` e `appendChild`.
- Você fez um bom trabalho na criação de links para a página `detalhes.html` com o 'id' do item na query string. Isso é essencial para carregar a notícia correta na página de detalhes.
- Sua página `detalhes.html` consegue ler o 'id' da URL, encontrar o item correspondente na estrutura de dados e exibir suas informações. Isso é feito de forma eficaz através do uso de `URLSearchParams`.
- Finalmente, você fez um bom trabalho ao não usar nenhum framework de JavaScript no seu projeto, cumprindo a exigência do projeto.

## Pontos de Melhoria

Agora, vamos falar sobre algumas das áreas onde você pode melhorar:

- A primeira coisa que notei é que você não tem tags `<article>` suficientes em seu HTML. Você tem 2, mas o teste requer 4. Certifique-se de que você está usando a tag `<article>` para agrupar conteúdo relacionado.
- Seu HTML também está faltando a quantidade necessária de tags `<img>`. Certifique-se de que cada card de notícia e a página de detalhes têm uma imagem.
- O teste de links internos para tags `<article>` falhou. Isso significa que os links no seu site não estão apontando corretamente para uma tag `<article>`.
- Seu CSS não está usando unidades relativas (como em, rem, %, vh, vw). Essas unidades são importantes para garantir que seu site seja responsivo e funcione bem em todos os tamanhos de tela.
- Outros testes de CSS falharam porque você não está usando classes específicas necessárias para o teste. Certifique-se de ler atentamente os requisitos do teste para entender quais classes você precisa usar.
- No seu JavaScript, você está usando seletores de ID mais vezes do que o permitido. Tente usar classes em vez de IDs para estilizar vários elementos de uma vez.
- O teste de presença da tag `<script>` falhou, o que significa que você tem uma tag `<script>` em seu HTML. Como este projeto deve ser feito sem o uso de JavaScript no HTML, você deve remover essa tag.
- A pasta 'imgs' parece estar faltando no seu projeto. Verifique se você a adicionou ao seu projeto e se todas as suas imagens estão lá.
- Por último, os links para a página 'detalhes.html' com o parâmetro de consulta 'id' estão faltando. Você precisa ter pelo menos 3 desses links no seu site.

## Recursos de Aprendizagem

Aqui estão alguns recursos que podem ajudá-lo a melhorar em áreas onde você teve dificuldades:

- [Guia sobre Manipulação do DOM (Document Object Model) para criar conteúdo dinâmico.](https://developer.mozilla.org/pt-BR/docs/Web/API/Document_Object_Model/Introduction)
- [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL.](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)
- [Aprenda a trabalhar com a estrutura de dados JSON em JavaScript.](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/Objects/JSON)
- [Guia completo sobre como usar o atributo 'alt' em imagens para acessibilidade.](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

## Conclusão

Você está no caminho certo! Com algumas melhorias e ajustes, tenho certeza de que você será capaz de completar este projeto com sucesso. Mantenha o bom trabalho e lembre-se, a prática leva à perfeição! Happy coding! 😊


---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Teste |
|:---|:---|:---|
| Revisar | `structure` | `has_tag` |
| Revisar | `structure` | `has_tag` |
| Revisar | `link` | `check_internal_links_to_article` |
| Revisar | `responsivity` | `uses_relative_units` |
| Revisar | `bootstrap_fundamentals` | `check_bootstrap_linked` |
| Revisar | `bootstrap_fundamentals` | `check_internal_links` |
| Revisar | `bootstrap_fundamentals` | `has_class` |
| Revisar | `bootstrap_fundamentals` | `has_class` |
| Revisar | `bootstrap_fundamentals` | `has_class` |
| Revisar | `bootstrap_fundamentals` | `has_class` |
| Revisar | `bootstrap_fundamentals` | `has_class` |
| Revisar | `linking_and_integrity` | `link_points_to_page_with_query_param` |
| Corrigir (Penalidade) | `html` | `check_id_selector_over_usage` |
| Corrigir (Penalidade) | `html` | `has_forbidden_tag` |
| Corrigir (Penalidade) | `project_structure` | `check_dir_exists` |


---
> Caso queira tirar uma dúvida específica, entre em contato com o Chapter.