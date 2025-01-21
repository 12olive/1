---
icon: hand-pointer
---

# Interactive blocks交互式块

点我展开点除了你可以编写的默认 Markdown 之外，GitBook 还有许多开箱即用的交互式块可供你使用。您可以通过在编辑器中按 / 来查找交互式块 。

<figure><img src="https://gitbookio.github.io/onboarding-template-images/interactive-hero.png" alt=""><figcaption></figcaption></figure>

### Tabs

{% tabs %}
{% tab title="First tab" %}
每个选项卡都像一个迷你页面 — 它可以包含多个其他类型的其他块。因此，您可以将代码块、图像、集成块等添加到同一选项卡块中的各个选项卡中。
{% endtab %}

{% tab title="Second tab" %}
添加图像、嵌入内容、代码块等。

```javascript
const handleFetchEvent = async (request, context) => {
    return new Response({message: "Hello World"});
};
```
{% endtab %}
{% endtabs %}

### Expandable sections可展开的部分

<details>

<summary></summary>

Expandable blocks are helpful in condensing what could otherwise be a lengthy paragraph. They are also great in step-by-step guides and FAQs.

可展开的块有助于压缩原本可能很长的段落。它们在分步指南和常见问题解答中也很棒。

</details>

### Drawings

<img alt="" class="gitbook-drawing">

### Embedded content

{% embed url="https://www.youtube.com/watch?v=YILlrDYzAm4" %}

{% hint style="info" %}
GitBook supports thousands of embedded websites out-of-the-box, simply by GitBook 支持数以千计的开箱即用的嵌入式网站，只需粘贴它们的链接即可。请随时查看[哪些是原生支持的](https://iframely.com)。
{% endhint %}

