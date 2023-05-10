# MT-project
Adjusting Machine Translation Transformer's parameters for different input length texts for the language pair English-Spanish

This study delves into the influence of input sequence lengths on vector representation quality in Machine Translation (MT) models, specifically English-Spanish MT. We postulate that longer sequences could enhance the model’s predictive abilities due to a deeper contextual understanding and greater interdependence among input tokens. We assess this hypothesis using three sub-corpora extracted from the same English-Spanish parallel corpora, categorized by sequence lengths: short (1-3 words), medium (4-10 words), and long (more than 10 words). We also explore the effect of hyperparameter tuning on the model’s performance, aiming to strike a balance between accuracy and practical constraints like training time and computational resources. The findings provide insights into optimizing sequence lengths and parameters in MT models.

The code implementation can be found in the Google Colab Notebook called Model_Default_Parameters.ipynb
