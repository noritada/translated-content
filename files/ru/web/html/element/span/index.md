---
title: <span>
slug: Web/HTML/Element/span
tags:
  - Element
  - HTML
  - Web
  - Веб
  - Потоковый контент
  - Справка
  - Элемент
translation_of: Web/HTML/Element/span
---
{{HTMLRef}}

**HTML-элемент `<span>`** является основным строковым контейнером для фразового контента, который, по существу, ничего не представляет. Он может использоваться для группировки элементов в целях стилизации (использование атрибутов {{htmlattrxref("class")}} или {{htmlattrxref("id")}}) или потому, что они имеет общие значения атрибутов, например {{htmlattrxref("lang")}}. Он должен быть использован только когда нет другого подходящего по семантике элемента. `<span>` очень похож на элемент {{HTMLElement("div")}}, но {{HTMLElement("div")}} является [блочным](/ru/docs/Web/HTML/Block-level_elements) элементом, в то время как `<span>` является [строчным](/ru/docs/Web/HTML/Строчные_Элементы).

{{EmbedInteractiveExample("pages/tabbed/span.html", "tabbed-shorter")}}

| [Категории контента](/ru/docs/Web/Guide/HTML/Content_categories) | [Потоковый контент](/ru/docs/Web/Guide/HTML/Content_categories#Потоковый_контент), [фразовый контент](/ru/docs/Web/Guide/HTML/Content_categories#Phrasing_content).                                                    |
| ---------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Разрешённое содержимое                                           | [Фразовый контент](/ru/docs/Web/Guide/HTML/Content_categories#Phrasing_content).                                                                                                                                       |
| Пропуск тега                                                     | Ни одного; Оба тега, открывающий и закрывающий, являются обязательными.                                                                                                                                                |
| Разрешённые родительские элементы                                | Любой элемент, который разрешает [фразовый](/ru/docs/Web/Guide/HTML/Content_categories#Phrasing_content) или [потоковый](/ru/docs/Web/Guide/HTML/Content_categories#Потоковый_контент) контент в качестве содержимого. |
| Разрешённые роли ARIA                                            | Любые                                                                                                                                                                                                                  |
| DOM-интерфейс                                                    | {{domxref("HTMLSpanElement")}} (до {{glossary("HTML5")}}, интерфейсом был {{domxref("HTMLElement")}})                                                                                       |

## Атрибуты

К этому элементу применимы только [глобальные атрибуты](/ru/docs/Web/HTML/Общие_атрибуты).

## Пример 1

### HTML

```html
<p><span>Какой-нибудь текст</span></p>
```

### Результат

{{EmbedLiveSample('Пример_1')}}

## Пример 2

### HTML

```html
<li><span>
    <a href="portfolio.html" target="_blank">Посмотреть моё портфолио</a>
</span></li>
```

### CSS

```css
li span {
  background: gold;
 }
```

### Результат

{{EmbedLiveSample('Пример_2')}}

## Спецификации

{{Specifications}}

## Поддержка браузерами

{{Compat}}

## Смотрите также

- HTML-элемент {{HTMLElement("div")}}
