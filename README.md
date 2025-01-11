This project implements a sentiment analysis system capable of analyzing Turkish customer reviews from the e-commerce platform Hepsiburada. Utilizing a dataset of 250,000 reviews, the system classifies sentiments as positive or negative, addressing the challenges posed by the Turkish language's linguistic structure. A GRU-based deep learning model is employed, featuring four stacked GRU layers and a 50-dimensional embedding layer to capture sequential dependencies and contextual meaning. The data preprocessing pipeline includes tokenization and padding to standardize input lengths, ensuring robust handling of variable-length text data. Achieving a test accuracy of 95.12%, the model demonstrates strong performance in real-world scenarios. Additionally, a user-friendly interface developed with Tkinter enables users to perform sentiment analysis interactively and in real time. The system was trained over eight epochs with a batch size of 128, using the Adam optimizer for efficient convergence. While the system effectively classifies reviews, its accuracy can be limited by ambiguous or mixed sentiment texts. Future enhancements will focus on expanding the dataset to include diverse sources, implementing attention mechanisms for improved interpretability, and extending the model to handle multi-class sentiment analysis for more granular insights.

You can access the dataset from here: https://drive.google.com/file/d/1Tjzaj-gFsnhs7p384sEpMzNjN7ZCQaGI/view?usp=sharing

Here are the application visuals and usage instructions:

<img src="https://github.com/user-attachments/assets/ad8c758a-334f-4fc5-bb6a-a8c5737ba597" alt="image1" width="570" height="820">

<img src="https://github.com/user-attachments/assets/394533ab-6436-48e1-b99e-51b1b2a96845" alt="image1" width="600" height="500">
