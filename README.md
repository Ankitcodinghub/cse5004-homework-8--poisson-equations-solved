# cse5004-homework-8--poisson-equations-solved
**TO GET THIS SOLUTION VISIT:** [CSE5004 Homework 8- Poisson equations Solved](https://www.ankitcodinghub.com/product/cse5004-scientific-computation-with-python-solved-8/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115384&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE5004 Homework 8- Poisson equations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
HW8. Poisson equations

Two-dimensional Poisson equation is written as

∇2u(x,y) = f(x,y) for (x,y) ∈ Ω

and on the boundary ∂Ω = ∂ΩD∪ ∂ΩN

u(x,y) = g(x,y) on ∂ΩD and ∂u/∂n = h(x,y) on ∂ΩN

Note that n is the normal to the boundary, ∂ΩD is the Dirichlet boundary, and ∂ΩN is the Neumann boundary.

1. (Iterative Poisson solver) Let’s consider the Poisson equation in the square domain [0,1] × [0,1] with homogenous boundary conditions u = 0 at all boundaries and f(x,y) = sin(πx)sin(πy).

2. (Linearity) Let’s consider a following Poisson equation

∇2u(x,y) = f1(x,y) + f2(x,y) for (x,y) ∈ Ω

and u(x,y) = 0 on the boundary ∂Ω of the square domain Ω ≡ [0,1] × [0,1].

(1) Find u(x,y), the solution of Poisson equation, ∇2u(x,y) = f1(x,y) + f2(x,y) using Gauss-Seidel SOR. The forcing functions are defined as

f1(x,y) = sin(πx)sin(πy)

f2(x,y) = exp(−100.0((x − 0.5)2 + (y − 0.5)2))

(2) Find u2(x,y) the solution of Poisson equation, ∇2u2(x,y) = f2(x,y) using Gauss-Seidel SOR.

(3) Discuss the solution u(x,y) by comparing with the solutions u2(x,y) and u1(x,y) that is obtained in Problem 1.
