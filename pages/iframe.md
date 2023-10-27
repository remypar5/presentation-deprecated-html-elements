---
layout: two-cols-header
---
# The `<iframe>` Inline Frame Element

<blockqoute cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe">
    <p>The &lt;iframe&gt; HTML element represents a nested browsing context, embedding another HTML page into the current one.</p>
    <footer>&mdash;<cite>MDN</cite></footer>
</blockqoute>

::left::
<v-click>

According to <abbr title="Mozilla Developer Network">MDN</abbr> `<iframe>` is not deprecated

![Screenshot of MDN indicating the iframe element is not deprecated](/images/iframe.png)
</v-click>

<style>
img {
    @apply shadow-lg;
}
</style>

---

# Why do people think it is?

<v-clicks class="mt-8">

- `<frame>` and `<frameset>` _are_ deprecated<br>
  ![Screenshot of MDN indicating the frame element is deprecated](/images/deprecated-frame.png)
  ![Screenshot of MDN indicating the frameset element is deprecated](/images/deprecated-frameset.png)
- Security issues
</v-clicks>

<v-click>

## The Portal Element
(experimental)

<blockqoute cite="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/portal">
    <p>The &lt;portal&gt; HTML element enables the embedding of another HTML page into the current one for the purposes of allowing smoother navigation into new pages.</p>
    <footer>&mdash;<cite>MDN</cite></footer>
</blockqoute>

</v-click>


<style>
img {
    @apply shadow-lg;
    @apply inline;

}
img + img {
    @apply ms-8
}
</style>

<!--
# Security issues
- Mention the new `<portal>` tag
-->

---
transition: slide-left
---

# Use case

<div v-click>

Content from a different domain:

- Youtube/vimeo
- Tiktok/Instagram
- Tweets
</div>

<div v-click>

Result or compilation of various separate sources

- MDN/W3Schools Playground
- Codepen (or similar)
</div>
