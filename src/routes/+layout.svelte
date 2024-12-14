<script lang="js">
import '../app.css'

const P = $props()
const { header, children } = P
</script>

<div class="prose">

<ul>
  <li><a href="/">Home</a></li>
  <li><a href="/about">About</a></li>
</ul>

<p>{ !!children }</p>
<p>{ !!header }</p>
{@render header?.()}

<hr>

<pre>{ JSON.stringify(P) }</pre>
<!-- <slot></slot> -->
{@render children()}


</div>
