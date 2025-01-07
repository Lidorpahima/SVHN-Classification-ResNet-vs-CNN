<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>📊 SVHN Classification: ResNet50 vs Custom CNN</h1>
    <p>
        This repository compares the performance of a pre-trained <strong>ResNet50</strong> model using transfer learning
        against a custom-built <strong>CNN</strong> for classifying numbers in the <strong>SVHN dataset</strong>.
    </p>
    <h2>🌟 Key Highlights:</h2>
    <ul>
        <li><strong>Dataset:</strong> Street View House Numbers (SVHN)</li>
        <li><strong>Models Compared:</strong>
            <ul>
                <li>Pre-trained ResNet50 (transfer learning)</li>
                <li>Custom CNN (<a href="https://github.com/Lidorpahima/Street_View_House_Numbers_Machine_Learning.git" target="_blank">available here</a> 🖱️)</li>
            </ul>
        </li>
        <li><strong>Metrics:</strong> Accuracy, loss, precision, recall, and F1-score</li>
        <li><strong>Challenges:</strong> Class imbalance, particularly for class <code>9</code></li>
        <li><strong>Implementation:</strong> PyTorch with data augmentation, weighted loss, and fine-tuning</li>
    </ul>
    <h2>🏆 Results:</h2>
    <ul>
        <li><strong>ResNet50:</strong>
            <ul>
                <li><strong>Accuracy:</strong> 94.23% 🎯</li>
                <li><strong>Test Loss:</strong> 0.2124</li>
                <li><strong>Training Time:</strong> ~2 hours on GPU 🕒</li>
            </ul>
        </li>
        <li><strong>Custom CNN:</strong>
            <ul>
                <li><strong>Accuracy:</strong> 91.18% ✅</li>
                <li><strong>Test Loss:</strong> 0.3093</li>
                <li><strong>Training Time:</strong> ~30 minutes ⚡</li>
            </ul>
        </li>
    </ul>
    <h2>🔍 Conclusions:</h2>
    <ul>
        <li><strong>ResNet50 Advantages:</strong> Higher accuracy and better performance, especially in complex classes.</li>
        <li><strong>Custom CNN Advantages:</strong> Faster training and reasonable accuracy, ideal for quick iterations.</li>
        <li><strong>Class 9 Challenges:</strong> Both models struggled with class <code>9</code>, likely due to fewer samples or visual similarity to other digits.</li>
        <li><strong>Improvement Opportunities:</strong> Weighted loss helped slightly, but better data balance or advanced augmentations could further improve performance.</li>
    </ul>
    <h2>📂 Repository Contents:</h2>
    <ul>
        <li><strong>code/</strong>: Python scripts for training, validation, and testing the models.</li>
        <li><strong>data/</strong>: Instructions for downloading and preparing the SVHN dataset.</li>
        <li><strong>results/</strong>: Plots, confusion matrices, and model evaluation reports.</li>
        <li><strong>models/</strong>: Pre-trained and final models saved for reuse.</li>
    </ul>
    <h2>🚀 Getting Started:</h2>
    <p>Clone this repository and follow the instructions in the README to run the experiments.</p>
    <pre>
        <code>
git clone https://github.com/Lidorpahima/SVHN-Classification-ResNet-vs-CNN.git
cd SVHN-Classification-ResNet-vs-CNN
        </code>
    </pre>
    <h2>🔗 Additional Resources:</h2>
    <ul>
        <li><a href="https://github.com/Lidorpahima/Street_View_House_Numbers_Machine_Learning.git" target="_blank">Custom CNN Implementation 🚀</a></li>
        <li><a href="http://ufldl.stanford.edu/housenumbers/" target="_blank">SVHN Dataset 🌐</a></li>
    </ul>
    <p>🎉 Feel free to fork this repository, star ⭐ it, or contribute by submitting pull requests!</p>
</body>
</html>
