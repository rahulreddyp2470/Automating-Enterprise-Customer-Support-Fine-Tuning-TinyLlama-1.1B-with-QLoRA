# Customer Support LLM Project

This project focuses on fine-tuning the TinyLlama 1.1B model using QLoRA for enterprise customer support applications.

## Instructions on How to Run
1. **Clone the Repository**: Use `git clone https://github.com/rahulreddyp2470/Automating-Enterprise-Customer-Support-Fine-Tuning-TinyLlama-1.1B-with-QLoRA.git`
2. **Install Required Packages**: Navigate to the project directory and run:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Fine-Tuning Script**: Execute the following command:
   ```bash
   python fine_tune.py --config config.yaml
   ```

## Results Information
The results of the fine-tuning will be stored in the `results/` directory. You will find the model checkpoints and evaluation metrics here.