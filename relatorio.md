# Relatório de Desempenho - Portal de Notícias Dinâmico
> **Nota Final:** **`71.38 / 100`**

Olá, **ArthurCRodrigues**! 👋

Aqui está o feedback detalhado sobre sua atividade. Use este guia para entender seus acertos e os pontos que podem ser melhorados.

---

## ⭐ Pontos Extras e Boas Práticas
Nenhum item bônus foi completado desta vez. Continue se desafiando!

---

## ✅ Requisitos Essenciais
Encontramos alguns pontos nos requisitos essenciais que precisam de sua atenção:

#### Tópico: Structure
> ❌ **Falhou** no teste `has_tag` (Parâmetros: `tag`: `img`, `required_count`: `5`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 5 tags `<img>` necessárias.


#### Tópico: Link
> ❌ **Falhou** no teste `check_internal_links_to_article` (Parâmetros: `required_count`: `4`)
> - **Detalhes:** Atenção: Encontrados 0 de 4 links internos válidos para tags <article>.


#### Tópico: Responsivity
> ❌ **Falhou** no teste `uses_relative_units`
> - **Detalhes:** Atenção: Não foram utilizadas medidas relativas como (em, rem, %, vh, vw) no seu CSS.


#### Tópico: Bootstrap fundamentals
> ❌ **Falhou** no teste `check_bootstrap_linked`
> - **Detalhes:** Atenção: Não foi encontrado um link para o CSS ou JS do Bootstrap.

> ❌ **Falhou** no teste `check_internal_links` (Parâmetros: `required_count`: `3`)
> - **Detalhes:** Atenção: Encontrados 0 de 3 links internos válidos ('âncoras').

> ❌ **Falhou** no teste `has_class` (Parâmetros: `class_names`: `['row']`, `required_count`: `1`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 classes CSS necessárias. Classes encontradas: []

> ❌ **Falhou** no teste `has_class` (Parâmetros: `class_names`: `['col-*']`, `required_count`: `3`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 3 classes CSS necessárias. Classes encontradas: []

> ❌ **Falhou** no teste `has_class` (Parâmetros: `class_names`: `['text-center']`, `required_count`: `1`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 classes CSS necessárias. Classes encontradas: []

> ❌ **Falhou** no teste `has_class` (Parâmetros: `class_names`: `['d-flex', 'd-*-flex']`, `required_count`: `1`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 classes CSS necessárias. Classes encontradas: []

> ❌ **Falhou** no teste `has_class` (Parâmetros: `class_names`: `['bg-*']`, `required_count`: `1`)
> - **Detalhes:** Atenção: Foram encontradas 0 de 1 classes CSS necessárias. Classes encontradas: []


#### Tópico: Linking and integrity
> ❌ **Falhou** no teste `link_points_to_page_with_query_param` (Parâmetros: `target_page`: `detalhes.html`, `query_param`: `id`, `required_count`: `3`)
> - **Detalhes:** Atenção: Encontrados 0 de 3 links válidos para 'detalhes.html' com o parâmetro de consulta 'id'.

> - 📚 **Recurso Sugerido:** [Tutorial sobre como usar URLSearchParams para ler parâmetros da query string da URL.](https://developer.mozilla.org/pt-BR/docs/Web/API/URLSearchParams)


---

## 🚨 Pontos de Atenção e Más Práticas
Ótimo trabalho! Nenhuma má prática foi detectada no seu projeto.

---

### 📝 Resumo dos Pontos de Atenção
| Ação | Tópico | Detalhes do Teste |
|:---|:---|:---|
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Verifica se uma tag HTML específica aparece um número mínimo de vezes.*<br>**Parâmetros:** <sub>`tag`: `article`, `required_count`: `4`</sub> |
| Revisar | `structure` | **Teste:** `has_tag`<br>**O que foi verificado:** *Verifica se uma tag HTML específica aparece um número mínimo de vezes.*<br>**Parâmetros:** <sub>`tag`: `img`, `required_count`: `5`</sub> |
| Revisar | `link` | **Teste:** `check_internal_links_to_article`<br>**O que foi verificado:** *Verifica a existência de um número mínimo de links âncora internos apontando para IDs em tags `<article>`.*<br>**Parâmetros:** <sub>`required_count`: `4`</sub> |
| Revisar | `responsivity` | **Teste:** `uses_relative_units`<br>**O que foi verificado:** *Verifica se o arquivo CSS usa unidades relativas como em, rem, %, vh, vw.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_bootstrap_linked`<br>**O que foi verificado:** *Verifica se o framework Bootstrap (CSS ou JS) está vinculado no arquivo HTML.*<br>**Parâmetros:** <sub>N/A</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `check_internal_links`<br>**O que foi verificado:** *Verifica a existência de um número mínimo de links âncora internos que apontam para IDs de elementos válidos.*<br>**Parâmetros:** <sub>`required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['row']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['col-*']`, `required_count`: `3`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['text-center']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['d-flex', 'd-*-flex']`, `required_count`: `1`</sub> |
| Revisar | `bootstrap_fundamentals` | **Teste:** `has_class`<br>**O que foi verificado:** *Verifica a presença de classes CSS específicas, com suporte a curingas, um número mínimo de vezes.*<br>**Parâmetros:** <sub>`class_names`: `['bg-*']`, `required_count`: `1`</sub> |
| Revisar | `linking_and_integrity` | **Teste:** `link_points_to_page_with_query_param`<br>**O que foi verificado:** *Verifica a existência de tags âncora que levam a uma página específica com um parâmetro de query string obrigatório.*<br>**Parâmetros:** <sub>`target_page`: `detalhes.html`, `query_param`: `id`, `required_count`: `3`</sub> |

---
> Continue praticando e melhorando seu código. Cada desafio é uma oportunidade de aprender! 🚀