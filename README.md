# machinelearning-assignment-1--linear-regression-solved
**TO GET THIS SOLUTION VISIT:** [MachineLearning Assignment 1 -Linear Regression Solved](https://www.ankitcodinghub.com/product/machinelearning-assignment-1-linear-regression-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;90961&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MachineLearning Assignment 1 -Linear Regression Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
You are given two files train.csv and test.csv containing the ​training data​ and ​testing data respectively. You can download the files from ​here

Each file contains two columns — a feature and a label.

<ol>
<li>Understanding the data and simple curve fitting
<ol>
<li>Plot a feature vs label graph for both the training data and the test data.</li>
<li>Write a code to fit a curve that minimizes ​squared error cost function​ using gradient descent (with learning rate 0.05), as discussed in class, ​on the training set ​while the model takes the following form y = W T Φn(x) , where W ∈ Rn+1 , and
23n 1m(T )2 Φn(x) = [1, x, x , x …, x ].Squarederrorisdefinedas J(W) = 2m ∑ W Φn(x)−y .

i=1

In your experiment, vary n from 1 to 9. In other words, fit 9 different curves

(polynomials of degree 1, 2, …, 9) to the ​training data​, and hence estimate the parameters. Use the estimated W to p​ redict labels on test data​ and measure ​squared error on the test set​, name it as test error.
</li>
</ol>
</li>
<li>Visualization of the fitted curves
<ol>
<li>Draw separate plots of all 9 different curves that you have fit for the training dataset in 1b.</li>
<li>Report squared error on ​both train and test data​ for each value of ​n ​in the form of a plot where along x-axis, vary ​n​ from 1 to 9 and along y-axis, plot both training error and test error. Explain which value of ​n​ is suitable for the dataset that you have, and why.</li>
</ol>
</li>
<li>Regularization
Perform the following regularizations on the curves for which you obtain the minimum and maximum training error from above.

<ol>
<li>Perform Lasso regression on the cost function as follows, vary λ = 0.25, 0.5, 0.75, 1 :
1 m(T )2

J(W) = 2m ∑ W Φn(x)−y +λW

i=1
</li>
<li>Perform Ridge regression on the cost function as follows, vary λ = 0.25, 0.5, 0.75, 1 :
1m(T )2 2 J(W) = 2m ∑ W Φn(x)−y +λW

i=1

Plot both training and test error for the two types of regularization (a) and (b). What differences do you notice between the two kinds of regression? Which one would you prefer for this problem and why?
</li>
</ol>
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
</div>
