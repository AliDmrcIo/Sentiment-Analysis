This project implements a sentiment analysis system capable of analyzing Turkish customer reviews from the e-commerce platform Hepsiburada. Utilizing a dataset of 250,000 reviews, the system classifies sentiments as positive or negative, addressing the challenges posed by the Turkish language's linguistic structure. A GRU-based deep learning model is employed, featuring four stacked GRU layers and a 50-dimensional embedding layer to capture sequential dependencies and contextual meaning. The data preprocessing pipeline includes tokenization and padding to standardize input lengths, ensuring robust handling of variable-length text data. Achieving a test accuracy of 95.12%, the model demonstrates strong performance in real-world scenarios. Additionally, a user-friendly interface developed with Tkinter enables users to perform sentiment analysis interactively and in real time. The system was trained over eight epochs with a batch size of 128, using the Adam optimizer for efficient convergence. While the system effectively classifies reviews, its accuracy can be limited by ambiguous or mixed sentiment texts. Future enhancements will focus on expanding the dataset to include diverse sources, implementing attention mechanisms for improved interpretability, and extending the model to handle multi-class sentiment analysis for more granular insights.

You can access the dataset from here: https://drive.google.com/file/d/1Tjzaj-gFsnhs7p384sEpMzNjN7ZCQaGI/view?usp=sharing

Here are the application visuals and usage instructions:

<img src="https://github.com/user-attachments/assets/394533ab-6436-48e1-b99e-51b1b2a96845" alt="image1" width="250" height="250">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/61b465d2-2fcb-4f64-9642-542f9d869b33" alt="image2" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/cc9a4ac9-c48e-46c0-a64b-fe5cfa17a9f4" alt="image2" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/c512a3de-5cdf-4141-b367-fa1055c6ba93" alt="image3" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/a292f31f-54b5-4e16-84cb-3ac8a2c4dd9b" alt="image4" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/bb050d3c-47a7-4556-84b3-a3bc5c8c3b6e" alt="image5" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/8f10b208-be4d-4bdb-bebd-bf7499c26d9b" alt="image6" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/da43d933-a0e5-4772-a4df-88c249e9bd69" alt="image7" width="250" height="500">
<img src="https://github.com/AliDmrcIo/ZinciriKirma/assets/110434358/0d820950-1984-4e7a-89fc-765fe3b8549f" alt="image8" width="250" height="500">

