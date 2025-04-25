# cs6210-assignment-2-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs6210-assignment-2-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93100&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6210 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
<div class="kksr-stars">
    
<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
    
<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">
            

<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>
                

<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Note: Please use Matlab, or a public domain approximation to it in this assignment. The code must compile on one of the lab machines with your instructions. Document your code thoroughly!

</div>
</div>
<div class="layoutArea">
<div class="column">
1.

</div>
<div class="column">
This is practical example of a small but real-life-type ill-conditioned problem The flow of water through two very different materials gives this system of linear equations :

−𝐻1 −2 1 h1 0 1 −2 1 h2 01−21 h3

⋮1⋱⋱⋱⋮ 0 =∆𝑥2 1 −(1+𝑎) 𝑎 h𝑖

0⋮ ⋱⋱⋱⋮

</div>
</div>
<div class="layoutArea">
<div class="column">
The coefficient a can be very small indeed a = 1.0e-7 giving an ill-conditioned matrix.

Use ∆𝑥 = 1 .If 𝐻1 = 8 𝑎𝑛𝑑 𝐻𝑟 = 4 Solve the system of equations for n= 161, where a = 1.0, a = 1.0e-5, a = 1.0e-10 and a = 1.0e-15. Use iterative refinement to check and improve your answer if possible. Compute the estimated condition number using the matlab condition number estimator. How does the condition number vary with the value of a

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2. (i) The web page has a zip file with a multigrid solver that solves the problem

</div>
</div>
<div class="layoutArea">
<div class="column">
2u2u (sin(88x)sin(72y),(x,y)[0,1]x[0,1]withsolutionand x2 y2

and (zero) boundary conditions given by u (x, y)  (sin(88 x)  sin(72 y) true (88)2 (72)2

Investigate how large a mesh this this can run on (mine failed at 16Kx16K) and time the code to verify the linear complexity of multiugrid. Note the accuracy achieved.

Modify the program given on the web page Laplace2D.m which uses the Jacobi method

</div>
</div>
<div class="layoutArea">
<div class="column">
2u  2u  0,(x, y)[0,1]x[0,1] with solution and to solve x2 y2

</div>
<div class="column">
to solve

</div>
</div>
<div class="layoutArea">
<div class="column">
boundary conditions given by u

</div>
<div class="column">
true

</div>
<div class="column">
(x, y)  sin( x)e( y)

</div>
</div>
<div class="layoutArea">
<div class="column">
the above (multigrid problem) using the Jacobi method and the red-black Gauss Seidel method. Try and achieve the accuracy of the multigrid method and compare performance if possible by modifying the program to include the convergence test given in the lecture notes with an infinity norm and a user-supplied tolerance, Tol

</div>
</div>
</div>
