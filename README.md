The surge in digital news content across platforms has underscored the need for automated, 
intelligent classification systems capable of organizing information efficiently and accurately. 
Transformer-based language models, particularly BERT (Bidirectional Encoder 
Representations from Transformers), offer state-of-the-art performance in understanding 
contextual semantics within text, making them highly effective for categorizing news articles 
into multiple predefined classes. A BERT-based architecture is fine-tuned on labeled news data 
to capture deep linguistic features and handle the complexities of natural language. The 
classification workflow includes rigorous preprocessing, tokenization using BERT’s subword 
vocabulary, and the application of a fully connected neural network for multi-class prediction. 
To ensure interpretability and foster trust in model predictions, explanation techniques such as 
SHAP (SHapley Additive exPlanations) and LIME (Local Interpretable Model-agnostic 
Explanations) are integrated, offering granular insights into feature importance and local 
decision boundaries. A lightweight, interactive web interface is implemented using Streamlit, 
enabling users to input news text, receive real-time predictions, and visualize explanation 
outputs seamlessly. This comprehensive pipeline addresses the dual challenge of achieving high 
classification accuracy and maintaining model transparency, making it adaptable for 
deployment in content recommendation, editorial automation, and media monitoring 
environments.
