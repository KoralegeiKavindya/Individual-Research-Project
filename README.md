<h1>🌞 Final Year Research Project - 2025</h1>
<h2> A Deep Learning Approach to Climate-Driven Power Generation Forecasting for Renewable Energy in Sri Lanka </h2>

<h2>📌 Project Overview</h2>

<p>
This project presents a deep learning-based framework for forecasting solar power generation using climate data, developed with a focus on the Sri Lankan energy landscape. 
The study explores and compares four time-series forecasting models: 
<strong>CNN</strong>, <strong>LSTM</strong>, <strong>standard Transformer</strong>, and a 
<strong>novel modified Transformer architecture</strong>. All models are trained and evaluated using a high-resolution, one-year, hourly dataset collected from the Baruthankanda Solar Power Plant in Hambantota.
</p>

<p>
The goal is to accurately predict hourly solar power output using only climatic variables such as solar irradiance and temperature, without relying on historical power data while also trying to have a balance between the accuracy and computational complexity. 
The modified Transformer architecture incorporates <strong>1-D convolutional layers</strong> in place of traditional fully connected layers within the encoder, enabling the model to better capture localized temporal patterns.
</p>

<h2>📁 Repository Contents</h2>

<ul>
  <li><code>notebooks/</code>: 
    <ul>
      <li><code>CNN_Model.ipynb</code>: Analysis and forecasting using the CNN model</li>
      <li><code>LSTM_Model.ipynb</code>: Analysis and forecasting using the LSTM model</li>
      <li><code>Transformer_Model.ipynb</code>: Analysis and forecasting using the standard Transformer</li>
      <li><code>Novel_Transformer_Model.ipynb</code>: Forecasting with the proposed modified Transformer architecture</li>
    </ul>
     <p>Each notebook includes all essential steps: data loading, preprocessing, feature selection and engineering, model training, testing, and performance evaluation.</p>
  </li>
</ul>

<h2>📊 Dataset</h2>

<p>
The dataset used in this project was provided by the 
<strong>Sri Lanka Sustainable Energy Authority (SLSEA)</strong>. 
It includes hourly records of various climate variables. 
Due to data availability constraints with wind and hydropower, the project focuses exclusively on solar forecasting.
</p>

<h2>📈 Evaluation Metrics</h2>

<p>
The forecasting models are evaluated using the following metrics:
</p>

<ul>
  <li><strong>RMSE</strong> (Root Mean Squared Error)</li>
  <li><strong>MAE</strong> (Mean Absolute Error)</li>
  <li><strong>MBE</strong> (Mean Bias Error)</li>
  <li><strong>R² Score</strong> (Coefficient of Determination)</li>
</ul>


