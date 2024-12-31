<script lang="js">
import '../app.css'

const { header, children } = $props()
</script>

<h1>Title</h1>

<ul>
  <li><a href="/">Home</a></li>
  <li><a href="/about">About</a></li>
</ul>

<p>Custom header({!!header})</p>
<p>header:{@render header?.()}</p>

<p>---</p>

<!-- <slot></slot> -->
{@render children()}



