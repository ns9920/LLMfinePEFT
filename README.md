<div>
    <h1>Efficient Fine-Tuned Question Answering Model with Peft</h1>
    <p>This repository contains a fine-tuned question answering model based on BERT (Bidirectional Encoder Representations from Transformers) architecture, specifically fine-tuned for question answering tasks. The model utilizes "deepset/bert-base-cased-squad2" which is optimized for handling complex question formats and extracting answers from longer contexts.</p>
    <h2>Squad Dataset</h2>
    <p>The Squad dataset was used for fine-tuning purposes, with a limited dataset of 1000 data inputs. This approach was undertaken primarily for learning purposes to demonstrate the capabilities of the model and the effectiveness of the fine-tuning process.</p> 
    <h2>Why this model?</h2>
    <ul>
        <li>Fine-Tuned for Question Answering Tasks: The model is fine-tuned specifically for question answering tasks, making it well-suited for tasks like extracting answers from given contexts.</li>
        <li>Utilizes BERT Architecture: BERT is a proven model for various NLP tasks, including QA. By leveraging the BERT architecture, this model inherits its robustness and performance.</li>
        <li>Trained on SQuAD2 Dataset: The model is fine-tuned on the SQuAD2 dataset, allowing it to handle challenging question formats and context understanding.</li>
        <li>Consideration of Letter Case: The "cased" attribute indicates that the model considers the case of letters during processing, potentially enhancing its ability to capture the intended meaning of words.</li>
    </ul>  
    <h2>PEFT</h2>
    <p>The peft.LoraConfig helps in fine-tuning large language models more efficiently by reducing their size and improving their performance. It achieves this by using LoRA, which breaks down the model into smaller, more manageable components while providing configuration options for balancing efficiency and accuracy.</p>   
    <h2>Training Results</h2>
    <p>These results demonstrate the effectiveness of fine-tuning the model with peft.LoraConfig, even with a limited dataset. Despite using only 1000 data inputs for training, the model achieves promising performance metrics, showcasing its potential for further development and application.</p>
    <ul>
        <li>Global Step: 1000</li>
        <li>Training Loss: 1.86</li>
        <li>Training Runtime: ~163 seconds</li>
        <li>Training Steps per Second: 6.135</li>
        <li>Training Samples per Second: 12.27</li>
        <li>Training Steps per Second: 6.135</li>
        <li>Total FLOPs: 524.41 trillion</li>
        <li>Epochs: 2.0</li>
    </ul>
    <h2>Getting Started</h2>
    <ol>
        <li>Clone the repository:
            <pre><code>git clone https://github.com/ns9920/LLMfinePEFT.git</code></pre>
        </li>
        <li>Navigate to the project directory:
            <pre><code>cd LLMfinePEFT</code></pre>
        </li>
        <li>Load the trained model using the provided scripts or integrate it into your NLP pipeline.</li>
        <li>Fine-tune the model further based on your specific dataset and requirements, if necessary</li>
    </ol>
    <h2>Contributing</h2>
    <p>Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.</p>
    <h2>Acknowledgments</h2>
    <p>Special thanks to the creators of BERT, SQuAD2 dataset, and peft.LoraConfig for their valuable contributions to the NLP community.</p>
</div>
