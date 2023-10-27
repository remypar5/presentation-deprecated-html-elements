---
layout: two-cols-header
---

# The &lt;b&gt; ~~boldface~~ Bring Attention To Element

<blockqoute cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/b">
    <p>The &lt;b&gt; HTML element is used to draw the reader's attention to the element's contents, which are not otherwise granted special importance. This was formerly known as the Boldface element, and most browsers still draw the text in boldface. However, you should not use &lt;b&gt; for styling text or granting importance. If you wish to create boldface text, you should use the CSS font-weight property. If you wish to indicate an element is of special importance, you should use the &lt;strong&gt; element.</p>
    <footer>&mdash;<cite>MDN</cite></footer>
</blockqoute>

::left::
<v-click>

According to <abbr title="Mozilla Developer Network">MDN</abbr> `<b>` is not deprecated

![Screenshot of MDN indicating the b element is not deprecated](/images/b.png)
</v-click>

<style>
img {
    @apply shadow-lg;
}
</style>

---

# Why do people think it is?

<ul>
    <li>

The `<strong>` element <span v-click>indicates that its contents have strong importance, seriousness, or urgency.</span>

</li>
</ul>

<!--
"Although visually identical, there is a slight distinction"
-->
---
transition: slide-left
---

# Use case
The `<b>` element

```html
<p>
    Bring attention to <b>a word or phrase</b> with the `<b>` element
    <strong>without</strong> making it more significant to the reader.
</p>
```

"Bring attention to <b>a word or phrase</b> with the `<b>` element <strong>without</strong> making it more significant to the reader."
