# Evaluation-of-LLM-application-using-Langsmith
This project is a Streamlit-based evaluation tool that integrates with LangSmith for automated evaluation of LLM applications.<br> The app allows users to:<br>
- Upload an LLM app script (.py file) and a ground truth dataset (.csv file).
- Automatically upload the ground truth as a dataset into LangSmith.
- Run evaluations of the LLM app against the dataset using custom-defined metrics, including:
  - Answer Hallucination – checks if the model produces fabricated or unsupported answers.
  - Question Relevance to Document – evaluates whether the user’s question is relevant to the retrieved document(s).
  - Answer Accuracy – measures correctness of the model’s response against the ground truth.
- Select the desired metric(s) and view the evaluation score along with a direct evaluation URL in LangSmith for deeper insights.<br>

This tool provides a simple and interactive way to benchmark LLM applications, making it easier to track quality, identify weaknesses, and ensure reliable outputs.
