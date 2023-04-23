Download Link: https://assignmentchef.com/product/solved-685-621-homework2
<br>
<ol>

 <li><strong>Problem 1</strong>

  <ul>

   <li>Points Total</li>

  </ul></li>

</ol>

CLRS 34.3-2: Show that the ≤<em><sub>P </sub></em>relation is a transitive relation on languages. That is, show that if <em>L</em><sub>1 </sub>≤<em><sub>P </sub>L</em><sub>2 </sub>and <em>L</em><sub>2 </sub>≤<em><sub>P </sub>L</em><sub>3</sub>, then <em>L</em><sub>1 </sub>≤<em><sub>P </sub>L</em>3.

<ol start="2">

 <li><strong>Problem 2</strong>

  <ul>

   <li>Points Total</li>

  </ul></li>

</ol>

Recall the definition of a complete graph <em>K<sub>n </sub></em>is a graph with <em>n </em>vertices such that every vertex is connected to every other vertex. Recall also that a clique is a complete subset of some graph. The <em>graph coloring problem </em>consists of assigning a color to each of the vertices of a graph such that adjacent vertices have different colors and the total number of colors used is minimized. We define the <em>chromatic number </em>of a graph <em>G </em>to be this minimum number of colors required to color graph <em>G</em>. Prove that the chromatic number of a graph <em>G </em>is no less than the size of the maximal clique of <em>G</em>.

<ol start="3">

 <li><strong>Problem 3 </strong><em>Note this is a Collaborative Problem</em></li>

</ol>

30 Points Total

Suppose you’re helping to organize a summer sports camp, and the following problem comes up. The camp is supposed to have at least one counselor who’s skilled at each of the <em>n </em>sports covered by the camp (baseball, volleyball, and so on). They have received job applications from <em>m </em>potential counselors. For each of the <em>n </em>sports, there is some subset of the <em>m </em>applicants qualified in that sport. The question is “For a given number <em>k &lt; m</em>, is is possible to hire at most <em>k </em>of the counselors and have at least one counselor qualified in each of the <em>n</em>-sports?” We’ll call this the <em>Efficient Recruiting Problem</em>. Prove that Efficient Recruiting is <em>NP</em>-complete.

<ol start="4">

 <li><strong>Problem 4 </strong><em>Note this is a Collaborative Problem</em></li>

</ol>

30 Points Total

We start by defining the <em>Independent Set Problem (IS)</em>. Given a graph <em>G </em>= (<em>V,E</em>), we say a set of nodes <em>S </em>⊆ <em>V </em>is <em>independent </em>if no two nodes in <em>S </em>are joined by an edge. The Independent Set Problem, which we denote <em>IS</em>, is the following. Given <em>G</em>, find an independent set that is as large as possible. Stated as a decision problem, <em>IS </em>answers the question: “Does there exist a set <em>S </em>⊆ <em>V </em>such that |<em>S</em>| ≥ <em>k</em>?” Then set <em>k </em>as large as possible. For this problem, you may take as given that <em>IS </em>is <em>NP</em>-complete.

1

Table 1: Customer Tracking Table

<table width="323">

 <tbody>

  <tr>

   <td width="72">Customer</td>

   <td width="73">Detergent</td>

   <td width="42">Beer</td>

   <td width="61">Diapers</td>

   <td width="75">Cat Litter</td>

  </tr>

  <tr>

   <td width="72">Raj</td>

   <td width="73">0</td>

   <td width="42">6</td>

   <td width="61">0</td>

   <td width="75">3</td>

  </tr>

  <tr>

   <td width="72">Alanis</td>

   <td width="73">2</td>

   <td width="42">3</td>

   <td width="61">0</td>

   <td width="75">0</td>

  </tr>

  <tr>

   <td width="72">Chelsea</td>

   <td width="73">0</td>

   <td width="42">0</td>

   <td width="61">0</td>

   <td width="75">7</td>

  </tr>

 </tbody>

</table>

A store trying to analyze the behavior of its customers will often maintain a table A where the rows of the table correspond to the customers and the columns (or fields) correspond to products the store sells. The entry <em>A</em>[<em>i,j</em>] specifies the quantity of product <em>j </em>that has been purchased by customer <em>i</em>. For example, Table 1 shows one such table.

One thing that a store might want to do with this data is the following. Let’s say that a subset <em>S </em>of the customers is <em>diverse </em>if no two of the customers in <em>S </em>have ever bought the same product (i.e., for each product, at most one of the customers in <em>S </em>has ever bought it). A diverse set of customers can be useful, for example, as a target pool for market research.

We can now define the <em>Diverse Subset Problem (DS) </em>as follows: Given an <em>m </em>× <em>n </em>array <em>A </em>as defined above and a number <em>k </em>≤ <em>m</em>, is there a subset of at least <em>k </em>customers that is diverse?

Prove that <em>DS </em>is <em>NP</em>-complete.