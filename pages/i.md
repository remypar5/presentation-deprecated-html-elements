---
layout: two-cols-header
---

# The &lt;i&gt; ~~italics~~ Idiomatic Text Element

<blockqoute cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/i">
    <p>The &lt;i&gt; HTML element represents a range of text that is set off from the normal text for some reason, such as idiomatic text, technical terms, taxonomical designations, among others. Historically, these have been presented using italicized type, which is the original source of the &lt;i&gt; naming of this element.</p>
    <footer>&mdash;<cite>MDN</cite></footer>
</blockqoute>

::left::
<v-click>

According to <abbr title="Mozilla Developer Network">MDN</abbr> `<i>` is not deprecated

![Screenshot of MDN indicating the b element is not deprecated](/images/i.png)
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

The `<em>` element <span v-click>marks text that has stress emphasis. The &lt;em&gt; element can be nested, with each level of nesting indicating a greater degree of emphasis.</span>

</li>
</ul>

<!--
"Although visually identical, there is a slight distinction"
-->

---
transition: slide-left
---

# Use case
The `<i>` element

```html
<p>
    The term <i>bandwidth</i> describes the measure of how much information can pass through a data connection in a given amount of time.
</p>
```

"The term <i>bandwidth</i> describes the measure of how much information can pass through a data connection in a given amount of time."
