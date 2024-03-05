<h2>Analyzing Correlations Between Training Scores and Effective Dimensions (GED and LED) of QNN</h2>
<p>This notebook delves into the correlations between training scores and the effective dimensions—Global Effective Dimension (GED) and Local Effective Dimension (LED)—of Quantum Neural Networks (QNNs). Through a series of experiments involving various quantum feature maps and ansätze, we assess how the expressivity of QNNs, as quantified by GED and LED, influences their classification accuracy and other performance metrics on toy datasets.</p>

<b>Libraries used:</b>
<ul>
  <li><code>matplotlib.pyplot</code> for plotting and visualizations</li>
  <li><code>numpy</code> for numerical operations</li>
  <li><code>qiskit</code> for quantum computing functionalities</li>
  <li><code>qiskit_machine_learning</code> for quantum machine learning algorithms and neural networks</li>
  <li><code>sklearn.metrics</code> for calculating accuracy, precision, recall, and F1 score</li>
</ul>

<b>Main Components:</b>
<ul>
  <li>Quantum Circuit Construction: Employing <code>ZFeatureMap</code> and <code>RealAmplitudes</code> to create QNNs for classification tasks.</li>
  <li>Model Optimization and Training: Using the COBYLA optimizer to fine-tune QNN parameters for optimal classification performance.</li>
  <li>Effective Dimension Calculation: Determining the GED and LED to evaluate the expressivity and learning capacity of QNN models.</li>
  <li>Performance and Correlation Analysis: Examining the relationship between QNN training scores and effective dimensions.</li>
</ul>

<b>Key Findings and Insights:</b>
<ul>
  <li>Distinct quantum feature maps and ansätze lead to significant variations in QNN performance, emphasizing the need for careful design and optimization.</li>
  <li>Analysis reveals a complex relationship between the effective dimensions of QNNs and their ability to classify accurately, suggesting that higher model expressivity does not always correlate with better performance.</li>
  <li>Effective dimensions—GED and LED—serve as critical indicators of a QNN's capacity to generalize from training to unseen data, offering insights beyond traditional training scores.</li>
</ul>

<b>Conclusion:</b>
<p>Our investigation into the correlations between training scores and effective dimensions of QNNs sheds light on the nuanced dynamics of quantum machine learning models. The findings highlight the importance of considering model expressivity, captured by GED and LED, alongside conventional performance metrics, paving the way for more informed QNN design and application in classification tasks.</p>
