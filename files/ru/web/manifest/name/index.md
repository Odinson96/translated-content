---
title: name
slug: Web/Manifest/name
tags:
  - Manifest
  - Web
  - name
translation_of: Web/Manifest/name
---

{{QuickLinksWithSubpages('/ru/docs/Web/Manifest')}}

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Type</th>
      <td><code>String</code></td>
    </tr>
    <tr>
      <th scope="row">Mandatory</th>
      <td>Yes</td>
    </tr>
    <tr>
      <th scope="row">Example</th>
      <td>
        <pre class="brush: json no-line-numbers">
"name": "Awesome application"</pre>
      </td>
    </tr>
  </tbody>
</table>

_`name`_ - это строка, которая представляет имя веб-приложения, как оно обычно отображается пользователю (например, среди списка других приложений или в качестве метки для значка). `name` поддерживает направленность, что означает, что оно может отображаться слева направо или справа налево в зависимости от значений свойств манифеста [`dir`](./dir) и [`lang`](./lang).

## Примеры

Простое `name` на языке слева направо:

```json
"name": "Потрясающее приложение"
```

`name` справа налево на арабском:

```json
"dir": "rtl",
"lang": "ar",
"name": "!أنا من التطبيق"
```

## Specification

| Specification                                                    | Status                       | Comment             | Feedback                                                                         |
| ---------------------------------------------------------------- | ---------------------------- | ------------------- | -------------------------------------------------------------------------------- |
| {{SpecName('Manifest', '#name-member', 'name')}} | {{Spec2('Manifest')}} | Initial definition. | [Web App Manifest Working Group drafts](https://github.com/w3c/manifest/issues/) |

## Browser compatibility

{{Compat}}
