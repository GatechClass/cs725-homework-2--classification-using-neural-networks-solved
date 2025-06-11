# cs725-homework-2--classification-using-neural-networks-solved
**TO GET THIS SOLUTION VISIT:** [CS725 Homework 2- Classification using neural networks Solved](https://mantutor.com/product/cs725-homework-2-classification-using-neural-networks-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115173&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS725 Homework 2- Classification using neural networks Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
![num_epochs=250 learning_rate=0 0005 20230822_11-33-01 training

Setting up

Instructions

For “simple” dataset: python train.py –dataset simple –model simple –num_epochs &lt;num_epochs&gt; –learning_rate &lt;learning_rate&gt; –seed &lt;seed&gt;

For “digits” dataset: python train.py –dataset digits –model digits –num_epochs &lt;num_epochs&gt; –learning_rate &lt;learning_rate&gt; –seed &lt;seed&gt;

The default values for each of these parameters are available in args.py. The seed argument is useful if your model uses random initialization (default PyTorch behavior). With a fixed seed, your experiment will be reproducible. You can fix a seed throughout your experiments for best reproducibility. It is possible that a different seed will give different result but the differences will mostly be minor so you should focus on choosing better hyperparameters and making a better model.

TensorBoard

This assignment uses PyTorch Lightning which allows us to use a far more sophisticated logger called TensorBoard developed originally for the

TensorFlow framework. To view your training logs, you can go into checkpoints/ directory and run tensorboard –logdir ./ to start TensorBoard. You can now view the (live) training progress of all your models by going to http://localhost:6006 in your browser! You can also download the data from here in a CSV for making plots in your report.

Kaggle Submission

You can compete on the Kaggle competition by creating a submission using python make_kaggle_submission.py &lt;path-to-bestdigits-ckpt&gt;. This will create a file called kaggle_upload.csv which you can upload on Kaggle to see results.

Moodle Submission

Once you are done with both the tasks, copy weights corresponding to your best models for each dataset into submission/ directory. Also copy the completed version (implementing both models) of model.py and your observation report (with filename report.pdf) into the same directory. Overall, make sure your submission folder looks as below. This is crucial since the assignment will be autograded: submission/ model.py best_simple.ckpt best_digits.ckpt report.pdf You can get a hint of the accuracy and loss values that autograder will use for grading your submission by running python evaluate_submission.py in this directory itself. The observation report should also contain roll numbers of both students in the team.

Once you are satisfied with the submission, use tar -cvzf &lt;roll1&gt;_&lt;roll2&gt;.tar.gz submission/ to create the final submission. Only the student with lower roll number in the group needs to upload this .tar.gz on Moodle.

Visualizing (Optional)
