Download Link: https://assignmentchef.com/product/solved-cse6363-project-4-svm-and-decision-tree
<br>
<h1>Support Vector Machines</h1>

<ol>

 <li>Consider the following linearly separable training data set:</li>

</ol>

<table width="160">

 <tbody>

  <tr>

   <td width="54"><em>D </em>= {</td>

   <td width="55">((1<em>,</em>2)<em>,</em></td>

   <td width="43">−1)<em>,</em></td>

   <td width="7"> </td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="55">((2<em>,</em>3)<em>,</em></td>

   <td width="43">1)<em>,</em></td>

   <td width="7"> </td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="55">((2<em>,</em>1)<em>,</em></td>

   <td width="43">−1)<em>,</em></td>

   <td width="7"> </td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="55">((3<em>,</em>4)<em>,</em></td>

   <td width="43">1)<em>,</em></td>

   <td width="7"> </td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="55">((1<em>,</em>3)<em>,</em></td>

   <td width="43">−1)<em>,</em></td>

   <td width="7"> </td>

  </tr>

  <tr>

   <td width="54"> </td>

   <td width="55">((4<em>,</em>4)<em>,</em></td>

   <td width="43">1)</td>

   <td width="7">}</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Formulate the optimization function as well as the constraints for the corresponding linear max-imum margin optimization problem without a regularization term. Also show the corresponding Lagrangian as well as the Lagrangian Dual for this problem.</li>

 <li>Use a SVM solver (e.g. MatLab’s <em>fitcsvm </em>function or Pythons sklearn.svm from the scikit-learn toolbox) to learn the linear SVM parameters for this problem. Show the resulting decision boundary and identify the support vectors in this problem.</li>

</ol>

<h1>Decision Trees</h1>

<ol start="2">

 <li>Consider the problem where we want to predict whether a balloon was inflated from a set of discrete attributes representing experiments with a person. The attributes are color (2 possible values), size (2 possible values), activity (2 possible values), and person’s age (2 possible values). Data is given in the files as a comma separated list {<em>c,s,a,p,i</em>} where the first entry is the color (YELLOW or PURPLE), the second is the size (SMALL or LARGE), the third is the activity (STRETCH or DIP), the fourth entry is the persons’s age (CHILD or ADULT), and the last is the class to be predicted, i.e. whether it was inflated or not, (T or N). There is a training and a test data set for this problem.</li>

 <li>Show the construction of a 2 level decision tree using minimum Entropy as the construction criterionon the training data set. You should include the entropy calculations and the construction decisions for each node you include in the 2-level tree.</li>

 <li>Apply the tree from part <em>a</em>) to the test data set and compare the classification accuracy on this test set with the one on the training set. Does the result indicate overfitting ?</li>

</ol>