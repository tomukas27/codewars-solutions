### Problem:
<p>Your task is to make two functions, <code>max</code> and <code>min</code> (<code>maximum</code> and <code>minimum</code> in PHP and Python) that take a(n) array/vector of integers <code>list</code> as input and outputs, respectively, the largest and lowest number in that array/vector.</p>
<p>#Examples</p>
<pre><code class="language-cpp">max({<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,<span class="hljs-number">-134</span>,<span class="hljs-number">566</span>}) returns <span class="hljs-number">566</span>
min({<span class="hljs-number">-52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, <span class="hljs-number">-54</span>, <span class="hljs-number">0</span>, <span class="hljs-number">-110</span>}) returns <span class="hljs-number">-110</span>
max({<span class="hljs-number">5</span>}) returns <span class="hljs-number">5</span>
min({<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>}) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-csharp">max({<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,<span class="hljs-number">-134</span>,<span class="hljs-number">566</span>}) returns <span class="hljs-number">566</span>
min({<span class="hljs-number">-52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, <span class="hljs-number">-54</span>, <span class="hljs-number">0</span>, <span class="hljs-number">-110</span>}) returns <span class="hljs-number">-110</span>
max({<span class="hljs-number">5</span>}) returns <span class="hljs-number">5</span>
min({<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>}) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-ruby">max([<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,-<span class="hljs-number">134</span>,<span class="hljs-number">566</span>]) returns <span class="hljs-number">566</span>
min([-<span class="hljs-number">52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, -<span class="hljs-number">54</span>, <span class="hljs-number">0</span>, -<span class="hljs-number">110</span>]) returns -<span class="hljs-number">110</span>
max([<span class="hljs-number">5</span>]) returns <span class="hljs-number">5</span>
min([<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>]) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-python">maximun([<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,<span class="hljs-number">-134</span>,<span class="hljs-number">566</span>]) returns <span class="hljs-number">566</span>
minimun([<span class="hljs-number">-52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, <span class="hljs-number">-54</span>, <span class="hljs-number">0</span>, <span class="hljs-number">-110</span>]) returns <span class="hljs-number">-110</span>
maximun([<span class="hljs-number">5</span>]) returns <span class="hljs-number">5</span>
minimun([<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>]) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-javascript">max([<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,<span class="hljs-number">-134</span>,<span class="hljs-number">566</span>]) returns <span class="hljs-number">566</span>
min([<span class="hljs-number">-52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, <span class="hljs-number">-54</span>, <span class="hljs-number">0</span>, <span class="hljs-number">-110</span>]) returns <span class="hljs-number">-110</span>
max([<span class="hljs-number">5</span>]) returns <span class="hljs-number">5</span>
min([<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>]) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-typescript">max([<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,<span class="hljs-number">-134</span>,<span class="hljs-number">566</span>]) returns <span class="hljs-number">566</span>
min([<span class="hljs-number">-52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, <span class="hljs-number">-54</span>, <span class="hljs-number">0</span>, <span class="hljs-number">-110</span>]) returns <span class="hljs-number">-110</span>
max([<span class="hljs-number">5</span>]) returns <span class="hljs-number">5</span>
min([<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>]) returns <span class="hljs-number">0</span></code></pre>
<pre style="display: none;"><code class="language-java">max({<span class="hljs-number">4</span>,<span class="hljs-number">6</span>,<span class="hljs-number">2</span>,<span class="hljs-number">1</span>,<span class="hljs-number">9</span>,<span class="hljs-number">63</span>,-<span class="hljs-number">134</span>,<span class="hljs-number">566</span>}) returns <span class="hljs-number">566</span>
min({-<span class="hljs-number">52</span>, <span class="hljs-number">56</span>, <span class="hljs-number">30</span>, <span class="hljs-number">29</span>, -<span class="hljs-number">54</span>, <span class="hljs-number">0</span>, -<span class="hljs-number">110</span>}) returns -<span class="hljs-number">110</span>
max({<span class="hljs-number">5</span>}) returns <span class="hljs-number">5</span>
min({<span class="hljs-number">42</span>, <span class="hljs-number">54</span>, <span class="hljs-number">65</span>, <span class="hljs-number">87</span>, <span class="hljs-number">0</span>}) returns <span class="hljs-number">0</span></code></pre>
<p>#Notes</p>
<ul>
<li>You may consider that there will not be any empty arrays/vectors.</li>
</ul>

### Solution