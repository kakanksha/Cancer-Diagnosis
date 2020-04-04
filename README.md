# Cancer-Diagnosis
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.

<h2> Link to kaggle problem </h2>
https://www.kaggle.com/c/msk-redefining-cancer-treatment/

<h2>Business objectives</h2>
<ol>
  <li> No low-latency requirement. </li>
  <li> Interpretability is important.</li>
  <li> Errors can be very costly. </li>
  <li> Probability of a data-point belonging to each class is needed.</li>
  </ol>
  
 <h2> Data Overview </h2>
 <ul>
  <li>Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data</li>
  <li>We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.Both these data files are have a common column called ID</li>
  <li>training_variants (ID , Gene, Variations, Class)</li>
  <li>training_text (ID, Text)</li>
  </ul>
 <h2>Performance Metric</h2>
 <ol>
  <li>Multi class log-loss </li>
  <li>onfusion matrix </li>
  </ol
