# Intent Classification System using Phi-2

This project demonstrates a lightweight intent classification system tailored for customer-agent interactions. The system uses Phi-2, a transformer-based model, to classify queries into predefined intents and provides confidence scores for predictions.

## Predefined Intents
- **Buy**: Queries related to purchasing a service or product.
- **Cancellation**: Requests to cancel subscriptions or services.
- **Complaint**: Issues or dissatisfaction with a product or service.
- **Billing Inquiry**: Questions related to charges or payments.
- **General Information**: Queries for basic information like business hours.

## Features
- **Intent Prediction**: Classifies user queries into one of five intents.
- **Confidence Scores**: Provides probabilities for each prediction.
- **Lightweight Deployment**: Optimized for Google Colab

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Farayabaig/Intent_Classifiication_System.git


## Performance Metrics
The following metrics highlight the performance of the intent classification system:

**1. Overall Accuracy**
- Total Queries: 10
- Correct Predictions: 9
- Accuracy: 90%

**2. Confidence Scores**
- Average Confidence Score: 85.8%
- Lowest Confidence Score: 0.58 (Billing Inquiry)
- Highest Confidence Score: 1.00 (various intents)
  
**3. Latency**
- Average Latency: 4.816 seconds
- Lowest Latency: 0.000 seconds (Cancellation)
- Highest Latency: 6.452 seconds (Buy)
