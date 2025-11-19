# AI-DRIVEN-TEA-QUALITY-AND-PRODUCTION-IMPROVEMENTS-IN-MID-COUNTRY-SRI-LANKA 🍃

This project deploys a comprehensive AI system to modernize the entire tea supply chain in Mid-Country Sri Lanka. By integrating advanced machine learning and vision models, the system drives significant improvements in quality, efficiency, and profitability from the leaf to the market.

***

## System Architecture 🏗️

The proposed architecture is centered around four specialized, interconnected AI components:

### 1. Automated Tea Leaf Grading & Inspection 🌿
Uses machine vision and deep learning models to classify leaf quality and freshness in real-time, ensuring consistent adherence to high standards and reducing manual errors and subjectivity.

### 2. AI-Based Detection of Tea Plant Diseases and Treatment Guidance 🐛
A deep learning system analyzes leaf imagery to identify pests, diseases (e.g., blister blight), and invasive species early. It provides instant alerts for timely intervention, reducing crop damage and improving plantation health.

### 3. Predictive Analytics for Crop Yield 📈
ML models analyze historical and environmental data (rainfall, temperature) to generate accurate production forecasts. This allows factories to optimize harvesting schedules and resource allocation.

### 4. Tea Market Demand Forecasting and Smart Auction Planning 💰
Predicts tea auction prices across all elevations (Low, Mid, High) and forecasts the optimal weekly dispatch volumes for Mid-Country factories using advanced time-series models. Includes a smart auction simulation powered by a Multi-Agent System where factories, buyers, and brokers make decisions, compete, and learn strategies across simulations to optimize auction outcomes.

***

## System Overview Diagram 🖼️

![System Overview Diagram](https://github.com/Nipuna3309309/AI-DRIVEN-TEA-QUALITY-AND-PRODUCTION-IMPROVEMENTS-IN-MID-COUNTRY-SRI-LANKA/blob/4f92d085b24fcfeefa7d980dbff24c041ded3166/System%20Overview%20Diagram%20F.png?raw=true)

Figure: High-level architecture integrating AI modules for leaf grading, disease detection and treatment guidance, yield forecasting, and market prediction.

***

## System Methodology 🧠 

The proposed system adopts a modular AI-driven architecture designed to optimize tea cultivation, grading, and production efficiency in Sri Lanka’s mid-country estates. Each component operates independently but integrates through a shared data platform to form a unified intelligent ecosystem.


### 1. Automated Tea Leaf Grading & Quality Inspection  🍃
This module automates the grading of freshly plucked tea leaves using computer vision and deep learning to ensure consistent quality.  
- Data: Farmers capture leaf images under controlled lighting.  
- Preprocessing: Background removal, brightness adjustment, and noise reduction with OpenCV.  
- Model: A CNN or YOLO-based model classifies leaves as tender, mature, coarse, or foreign material.  
- Output: The system generates a quality index and displays results on a real-time dashboard for growers and factories.  

This enables fair grading and encourages better plucking practices across estates.


### 2. AI-Based Disease, Pest & Invasive Species Detection and Treatment Guidance  🐛
This module focuses on early identification and treatment of tea plant health issues through image-based analysis and deep learning models.  

- Preprocessing: Captured leaf images are cleaned, resized, normalized, and augmented to handle lighting and orientation variations.  
- Modeling: CNN or R-CNN architectures detect several leaf diseases such as Blister Blight as well as pest-related issues like Shot Hole Borer.  
- Invasive Species: A CNN-based model identifies harmful weeds such as Lantana camara that compete with tea plants for resources.  
- Guidance: Based on detections, the system recommends appropriate treatments or control measures, including both chemical and eco-friendly options derived from TRI datasets and local estate knowledge.  
- Output: The module provides detected disease or species labels, along with corresponding treatment recommendations, accessible via the web dashboard.  

This component helps maintain healthy plantations by supporting timely, data-driven, and sustainable pest and disease management.


### 3. Predictive Analytics for Crop Yield 🌾
This module forecasts yield outcomes using environmental, climatic, and historical data.  
- Data: Integrates rainfall, soil quality, temperature, and historical production logs.  
- Digitization: Handwritten records are converted via OCR.  
- Model: Combines LSTM/GRU for time-based analysis and Random Forest for static features to predict monthly or annual yield.  
- Output: Dashboards visualize production trends and enable informed decision-making for field management.  

This supports better planning of pruning, labor, and harvesting schedules.


### 4. Tea Market Demand Forecasting and Smart Auction Planning 💰
This module forecasts weekly tea auction prices and optimal dispatch volumes while modeling real auction behavior.
- Data: Utilizes elevation-wise auction prices, factory volumes, weather data, and economic indicators.  
- Simulation: A Multi-Agent System (MAS) models factories, buyers, and brokers, learning and adapting bidding strategies.
- Model:  SARIMAX and ARIMA–Random Forest predict price trends and factory dispatch volumes for Mid-Country tea.  
- Output: Dashboards visualize production trends and enable informed decision-making for field management.
- Visualization: Insights are delivered through interactive dashboards built with Power BI.
  
This helps factories and exporters plan sales strategies and optimize profitability.

***

###  Integration 🌍

All components connect through a central data layer, enabling shared insights across grading, disease detection, yield forecasting, and market analysis. Together, they form an AI-powered, sustainable ecosystem that empowers tea growers and stakeholders to enhance productivity and quality while aligning with market trends.
- 🌱 Enhance tea quality and yield  
- 🧩 Improve operational efficiency  
- 📊 Make informed, data-driven decisions  
- 💼 Align production with real-time market trends  

