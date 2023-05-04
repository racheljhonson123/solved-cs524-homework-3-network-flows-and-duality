Download Link: https://assignmentchef.com/product/solved-cs524-homework-3-network-flows-and-duality
<br>



<ol>

 <li><strong> Car rental. </strong>A small car rental company has a fleet of 94 vehicles distributed among its 10 agencies. The location of every agency is given by its geographical coordinates <em>x </em>and <em>y </em>in a grid based on miles. We assume that the road distance between agencies is approximately 1.3 times the Euclidean distance (as the crow flies). The following table indicates the coordinates of all agencies, the number of cars required the next morning, and the stock of cars in the evening preceding this day.</li>

</ol>

<table width="0">

 <tbody>

  <tr>

   <td width="108">Agency number</td>

   <td width="37">1</td>

   <td width="29">2</td>

   <td width="29">3</td>

   <td width="29">4</td>

   <td width="29">5</td>

   <td width="29">6</td>

   <td width="29">7</td>

   <td width="29">8</td>

   <td width="29">9</td>

   <td width="22">10</td>

  </tr>

  <tr>

   <td width="108"><em>x </em>coordinate</td>

   <td width="37">0</td>

   <td width="29">20</td>

   <td width="29">18</td>

   <td width="29">30</td>

   <td width="29">35</td>

   <td width="29">33</td>

   <td width="29">5</td>

   <td width="29">5</td>

   <td width="29">11</td>

   <td width="22">2</td>

  </tr>

  <tr>

   <td width="108"><em>y </em>coordinate</td>

   <td width="37">0</td>

   <td width="29">20</td>

   <td width="29">10</td>

   <td width="29">12</td>

   <td width="29">0</td>

   <td width="29">25</td>

   <td width="29">27</td>

   <td width="29">10</td>

   <td width="29">0</td>

   <td width="22">15</td>

  </tr>

  <tr>

   <td width="108">Required cars</td>

   <td width="37">10</td>

   <td width="29">6</td>

   <td width="29">8</td>

   <td width="29">11</td>

   <td width="29">9</td>

   <td width="29">7</td>

   <td width="29">15</td>

   <td width="29">7</td>

   <td width="29">9</td>

   <td width="22">12</td>

  </tr>

  <tr>

   <td width="108">Cars present</td>

   <td width="37">8</td>

   <td width="29">13</td>

   <td width="29">4</td>

   <td width="29">8</td>

   <td width="29">12</td>

   <td width="29">2</td>

   <td width="29">14</td>

   <td width="29">11</td>

   <td width="29">15</td>

   <td width="22">7</td>

  </tr>

 </tbody>

</table>

Supposing the cost for transporting a car is $0.50 per mile, determine the movements of cars that allow the company to re-establish the required numbers of cars at all agencies, minimizing the total cost incurred for transport.

<ol start="2">

 <li><strong>[3 points] The chess problem. </strong>A small joinery makes two different sizes of boxwood chess sets. The small set requires 3 hours of machining on a lathe, and the large set requires 2 hours. There are four lathes with skilled operators who each work a 40 hour week, so we have 160 lathe-hours per week. The small chess set requires 1kg of boxwood, and the large set requires 4kg. Unfortunately, boxwood is scarce and only 200 kg per week can be obtained. When sold, each of the large chess sets yields a profit of $8, and one of the small chess set has a profit of $5. The problem is to decide how many sets of each kind should be made each week so as to maximize profit.

  <ol>

   <li>Write out the primal LP. Plot the feasible set and solve the LP graphically. Be sure to label the axes and indicate units. Label the optimal point and find the optimal objective.</li>

   <li>Repeat all the same steps as in part <strong>a) </strong>but for the dual LP this time. Verify that the optimal dual objective is the same as the optimal objective of part <strong>a)</strong>.</li>

  </ol></li>

 <li><strong>[3 points] Stigler’s supplement. </strong>Consider Stigler’s diet problem from Homework 2. To help further lower the cost of your diet, a friend offers to sell you calcium supplements. Each calcium pill contains 500 mg of calcium.

  <ol>

   <li>What is the most you would be willing to pay per pill? <strong>Hint: </strong>use duality!</li>

   <li>Suppose you can buy calcium pills at a cost $0.01 each. What is your new optimal diet? How much money does it save compared to the original optimal diet that didn’t have access to the calcium supplement?</li>

  </ol></li>

</ol>