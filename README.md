<body>
    <h1>Climate Change Tweet Sentiment Predictor Project</h1>
    <p>This project aims to analyze public sentiment on climate change through Twitter data, classifying tweets into four distinct categories: News, Pro (supportive of climate change efforts), Neutral, and Anti (opposed to climate change efforts). Utilizing the "Twitter Climate Change Sentiment Dataset" from Kaggle, which encompasses over 40,000 tweets spanning from April 27, 2015, to February 21, 2018, this analysis provides insights into public opinion dynamics over time regarding global warming and related environmental issues.</p>
    <h2>Key Features:</h2>
    <ul>
        <li><strong>Sentiment Classification</strong>: Tweets are categorized into News, Pro, Neutral, or Anti, offering a comprehensive view of public sentiment on climate change.</li>
        <li><strong>Rich Dataset</strong>: Analysis is based on a publicly available dataset containing over 40,000 tweets, ensuring a broad and diverse basis for sentiment analysis.</li>
        <li><strong>Iterative Model Improvement</strong>: Starting from a Naïve Bayes baseline model to sophisticated neural network architectures like DistilBERT, the project iteratively enhanced accuracy and efficiency through various optimization techniques.</li>
    </ul>
    <h2>Development Process:</h2>
    <p>The project underwent several iterations to enhance performance and accuracy:</p>
    <ul>
        <li>Initial use of a <strong>Naïve Bayes model</strong> provided a baseline accuracy of 0.66.</li>
        <li>Introduction of the <strong>Universal Sentence Encoder (USE)</strong> for more meaningful text representations.</li>
        <li>Implementation of <strong>undersampling</strong> and <strong>class weights</strong> to balance and leverage the dataset fully.</li>
        <li><strong>Early stopping</strong> was employed to combat overfitting, and the <strong>BERT tokenizer</strong> was initially used for fine-tuning.</li>
        <li>Due to hardware constraints, switched to <strong>DistilBERT</strong>, a lighter BERT version, optimizing training speed without significant loss in performance.</li>
        <li>Fine-tuning and adjustments, including token size optimization, culminated in a model achieving a <strong>prediction accuracy of 0.78</strong>.</li>
    </ul>
    <h2>Technologies Used:</h2>
    <ul>
        <li><strong>TensorFlow & Keras</strong>: For building and training the neural network models.</li>
        <li><strong>Transformers by Hugging Face</strong>: Utilizing DistilBERT for efficient language understanding.</li>
        <li><strong>Pandas & Numpy</strong>: For data manipulation and analysis.</li>
        <li><strong>Sklearn</strong>: For initial model training and evaluation metrics.</li>
    </ul>
    <h2>Project Outcome:</h2>
    <p>- The final model demonstrates a significant improvement in the ability to accurately classify tweets, with a notable accuracy of 0.78.</p>
    <p>- The project highlights the effectiveness of modern NLP techniques and models in processing and analyzing social media data for sentiment analysis.</p>
    <h2>About the Developer:</h2>
    <p>This project reflects my commitment to leveraging advanced machine learning and natural language processing techniques to extract meaningful insights from large datasets. It showcases my ability to iterate on model development effectively, optimize performance, and apply cutting-edge AI technologies to real-world problems.</p>
</body>
