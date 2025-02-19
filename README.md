# AI-Powered Size Chart Generator

## Overview
The **AI-Powered Size Chart Generator** is a Streamlit-based web application that helps apparel sellers generate accurate size charts for their products. It leverages AI-driven clustering techniques to group similar sizes and enhance user experience.

## Features
- Upload a dataset containing apparel size measurements.
- Perform AI-powered clustering using **MiniBatch KMeans**.
- Compute **cosine similarity** to group similar sizes.
- Interactive **Streamlit UI** for seamless user experience.
- **Visual representations** of size clusters.

## Tech Stack
- **Python**: Backend logic and data processing.
- **Streamlit**: Web application framework.
- **Scikit-Learn**: AI-driven clustering and similarity computations.
- **Pandas & NumPy**: Data manipulation and analysis.
- **Matplotlib & Seaborn**: Data visualization.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/size-chart-generator.git
   cd size-chart-generator
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
1. Upload a dataset in CSV format containing size-related data.
2. Select clustering parameters and run the AI model.
3. View the generated size chart and similarity clusters.
4. Download the processed size chart for use.

