# Relatório de Desempenho - Portal de Notícias Dinâmico
> **Nota Final:** **`68.62 / 100`**

Olá, **ArthurCRodrigues**! 👋

Aqui está o feedback detalhado sobre sua atividade. Use este guia para entender seus acertos e os pontos que podem ser melhorados.

---

## ⭐ Pontos Extras e Boas Práticas
Parabéns! Você completou os seguintes itens bônus, demonstrando um ótimo conhecimento:

#### Tópico: Accessibility
> ✅ **Passou** no teste `check_all_images_have_alt`
> - **Detalhes:** Parabéns! Nenhuma imagem encontrada para verificar.


#### Tópico: Head detail
> ✅ **Passou** no teste `check_head_details` (Parâmetros: `detail_tag`: `title`)
> - **Detalhes:** Parabéns! A tag `<title>` foi encontrada na seção `<head>`.

> ✅ **Passou** no teste `check_head_details` (Parâmetros: `detail_tag`: `meta`)
> - **Detalhes:** Parabéns! A tag `<meta>` foi encontrada na seção `<head>`.

> ✅ **Passou** no teste `check_attribute_and_value` (Parâmetros: `tag`: `meta`, `attribute`: `charset`, `value`: `UTF-8`)
> - **Detalhes:** Parabéns! Encontrada a tag `<meta>` com `charset='UTF-8'`.

> ✅ **Passou** no teste `check_attribute_and_value` (Parâmetros: `tag`: `meta`, `attribute`: `name`, `value`: `viewport`)
> - **Detalhes:** Parabéns! Encontrada a tag `<meta>` com `name='viewport'`.

> ✅ **Passou** no teste `check_attribute_and_value` (Parâmetros: `tag`: `meta`, `attribute`: `name`, `value`: `description`)
> - **Detalhes:** Parabéns! Encontrada a tag `<meta>` com `name='description'`.

> ✅ **Passou** no teste `check_attribute_and_value` (Parâmetros: `tag`: `meta`, `attribute`: `name`, `value`: `author`)
> - **Detalhes:** Parabéns! Encontrada a tag `<meta>` com `name='author'`.

> ✅ **Passou** no teste `check_attribute_and_value` (Parâmetros: `tag`: `meta`, `attribute`: `name`, `value`: `keywords`)
> - **Detalhes:** Parabéns! Encontrada a tag `<meta>` com `name='keywords'`.


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
Foram detectadas algumas práticas que resultaram em penalidades. Veja os detalhes abaixo para entender como corrigi-las:

#### Tópico: Html
> ❌ **Falhou** no teste `check_id_selector_over_usage` (Parâmetros: `max_allowed`: `2`)
> - **Detalhes:** Cuidado! 7 seletores de ID detectados (limite: 2).

> ❌ **Falhou** no teste `has_forbidden_tag` (Parâmetros: `tag`: `script`)
> - **Detalhes:** Cuidado! A tag `<script>` foi encontrada e é proibida.


#### Tópico: Project structure
> ❌ **Falhou** no teste `check_dir_exists` (Parâmetros: `dir_path`: `imgs`)
> - **Detalhes:** Cuidado! O diretório 'imgs' não existe.


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
| Corrigir (Penalidade) | `html` | **Teste:** `check_id_selector_over_usage`<br>**O que foi verificado:** *Conta o número de seletores de ID usados e penaliza se exceder o máximo permitido.*<br>**Parâmetros:** <sub>`max_allowed`: `2`</sub> |
| Corrigir (Penalidade) | `html` | **Teste:** `has_forbidden_tag`<br>**O que foi verificado:** *Verifica a presença de uma tag HTML proibida.*<br>**Parâmetros:** <sub>`tag`: `script`</sub> |
| Corrigir (Penalidade) | `project_structure` | **Teste:** `check_dir_exists`<br>**O que foi verificado:** *Verifica se um diretório específico existe no envio.*<br>**Parâmetros:** <sub>`dir_path`: `imgs`</sub> |

---
> Continue praticando e melhorando seu código. Cada desafio é uma oportunidade de aprender! 🚀
