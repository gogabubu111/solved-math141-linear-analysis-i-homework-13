Download Link: https://assignmentchef.com/product/solved-math141-linear-analysis-i-homework-13
<br>
<ol>

 <li>Find all eigenvectors and eigenvalues of the matrix. Write 1-3 sentences that interpret</li>

</ol>

these geometrically—in other words, what do the eigenvectors and eigenvalues tell you about the transformation geometrically (in terms of stretch factors and stretch directions)?

<ol start="2">

 <li>Construct an example for each of the following, or explain why such an example does not exist:

  <ul>

   <li>a 2×2 matrix that is invertible but not diagonalizable</li>

   <li>a 2×2 non-diagonal matrix that is diagonalizable but not invertible</li>

  </ul></li>

 <li>(<em>Strang </em><em>5.2 #11</em>) If all eigenvalues of <em>A </em>are 1, 1, and 2, which of the following are certain to be true? Give a reason if true or a counterexample if false.

  <ul>

   <li><em>A </em>is invertible.</li>

   <li><em>A </em>is diagonalizable.</li>

   <li><em>A </em>is not diagonalizable.</li>

  </ul></li>

 <li>(<em>Strang </em><em>5.2 #12</em>) Suppose the only eigenvectors of <em>A </em>are multiples of, which of the following are certain to be true? Give a reason if true or a counterexample if false.

  <ul>

   <li><em>A </em>is not invertible.</li>

   <li><em>A </em>has a repeated eigenvalue.</li>

   <li><em>A </em>is not diagonalizable.</li>

  </ul></li>

 <li>(<em>Strang </em><em>5.1 #18</em>) Suppose a 3×3 matrix <em>A </em>has eigenvalues 0, 3, and 5 with associated eigenvectors <em>~u</em>, <em>~v</em>, and <em>w~ </em>respectively.

  <ul>

   <li>Since the eigenvalues of <em>A </em>are all distinct, the set {<em>~u,~v,w~</em>} is .</li>

   <li>Write down a basis for the nullspace <em>N</em>(<em>A</em>) and the column space <em>C</em>(<em>A</em>).</li>

   <li>Find one particular solution to <em>A~x </em>= <em>~v </em>+ <em>w~</em>. Find all solutions to <em>A~x </em>= <em>~v </em>+ <em>w~</em>.</li>

   <li>Explain why <em>A~x </em>= <em>~u </em>does not have a solution. (Hint: If there is a solution, then is in <em>C</em>(<em>A</em>). Explain why that is impossible.)</li>

   <li>Is <em>A </em>invertible? Why or why not?</li>

  </ul></li>

 <li>Let <em>A </em>be an <em>n</em>-by-<em>n </em> Suppose <em>A~u </em>= 2<em>~u </em>and <em>A~v </em>= 5<em>~v </em>for nonzero vectors <em>~u </em>and <em>~v</em>. Complete the following proof that {<em>~u,~v</em>} is linearly independent.</li>

</ol>

Proof: In order for {<em>~u,~v</em>} to be linearly independent, we need to show that

<em>the only solution to the vector equation </em><em>x~u </em>+ <em>y~v </em>= <em><sup>~</sup></em>0 <em>is the trivial one.</em>

Note that in this equation, <em>~u </em>and <em>~v </em>are known vectors, while <em>x </em>and <em>y </em>are unknown scalars. Now assume that <em>x </em>= <em>a </em>and <em>y </em>= <em>b </em>is some solution to the above equation. That is

<em>.                                                                                       </em>(1)

MATH 141: Linear Analysis I                                              Homework 13                                                                               <em>Fall 2019</em>

Multiply both sides of equation (1) by matrix <em>A </em>from the left. Show your calculation details to explain why the following has to be true as well

2<em>a~u </em>+5<em>b~v </em>= <em>~</em>0<em>.                                                                                  </em>(2)

Explain in detail how combing vectors equations (1) and (2) leads to the conclusion that <em>a </em>= 0 = <em>b</em>. Therefore, the only solution to <em>x~u </em>+ <em>y~v </em>= <em><sup>~</sup></em>0 is the trivial solution.

<ol start="7">

 <li>In one of the reflection questions, you saw that if <em>A </em>is 2×2 matrix then the product of its eigenvalues is equal to det(<em>A</em>) and the sum is equal to trace(<em>A</em>). The following shows that both claims still hold true for n×n matrices.</li>

</ol>

Suppose that <em>λ</em><sub>1</sub><em>,λ</em><sub>2</sub><em>,…,λ<sub>n </sub></em>are the <em>n </em>eigenvalues of an n×n matrix <em>A</em>. <em>λ<sub>i</sub></em>’s are the roots of the polynomial det(<em>A </em>− <em>λI</em>), which means that we have a factorization

det(<em>A </em>− <em>λI</em>) = (<em>λ</em><sub>1 </sub>− <em>λ</em>)(<em>λ</em><sub>2 </sub>− <em>λ</em>)···(<em>λ<sub>n </sub></em>− <em>λ</em>)                                                                (3)

<ul>

 <li>(<em>Strang </em><em>5.1 #8</em>) By making a clever choice of the value for <em>λ </em>in equation (3), show that det(<em>A</em>) is equal to the product of eigenvalues.</li>

 <li>(<em>Strang </em><em>5.1 #9</em>) Show that trace(<em>A</em>) is equal to the sum of eigenvalues in three steps. First, find the coefficient of (−<em>λ</em>)<em><sup>n</sup></em><sup>−1 </sup>on the righthand side of equation (3). Next, find all terms on the righthand side of the following that involves (−<em>λ</em>)<em><sup>n</sup></em><sup>−1</sup></li>

</ul>

<em> ,</em>

where <em>a<sub>ij </sub></em>are the entries of <em>A</em>. Add up all those terms to find the coefficient of (−<em>λ</em>)<em><sup>n</sup></em><sup>−1</sup>. Lastly, compare the coefficient of (−<em>λ</em>)<em><sup>n</sup></em><sup>−1 </sup>found in these two different ways.