<h1>Zen Browser Tweaks</h1>
<p>This document outlines a set of practical configuration adjustments for Zen Browser using the <code>about:config</code> interface. </p>

> **⚠️ Note:** Descriptions were generated with the assistance of AI.

<h2>Accessing Configuration</h2>
<ol>
  <li>Open Zen Browser</li>
  <li>Enter <code>about:config</code> in the URL bar </li>
  <li>Accept the warning</li>
  <li>Search for the preference key  </li>
</ol>

<h2>Configurations</h2>
<ul>
  <li><h3>Disable Zen New-Tab Replacement</h3></li>
  <p>This modification prevents Zen Browser from replacing the default new-tab page with its custom Zen version. Useful if you prefer the browser's original new tab or a custom extension-based new tab.</p>
  <table>
    <tr>
      <td>zen.urlbar.replace-newtab</td>
      <td><code>false</code></td>
    </tr>
  </table>
  
  <li><h3>Reduce Border size around Zen</h3></li>
  <p>This modification reduces the size of the border (padding / separation) around the main browser window. Useful if you want a tighter, more compact layout by default the separation is <code>8</code>.</p>
  <table>
    <tr>
      <td>zen.theme.content-element-separation</td>
      <td><code>number</code> (default 8)</td>
    </tr>
  </table>
</ul>


