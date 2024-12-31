<script lang="js">
import '../app.css'

const { header, children } = $props()
</script>

<h1>Title</h1>

<ul>
  <li><a href="/">Home</a></li>
  <li><a href="/about">About</a></li>
</ul>

<p>{ !!header }</p>
{@render header?.()}

---<br>

<!-- <slot></slot> -->
{@render children()}



