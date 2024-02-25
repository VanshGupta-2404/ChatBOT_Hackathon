In this project, we have developed a specialized chatbot tailored for Ministry-specific interactions, designed to assist citizens in resolving their common queries. To address the multilingual nature of the provided data, we employed the Google Translate API to translate 60,000 lines of content, handling 1,000 lines per iteration.

To further enhance the model's capabilities given the extensive dataset, we incorporated the Llama model. Specifically, we opted for the GGML model, leveraging its quantization features to efficiently store word vectors. This approach ensures a more streamlined representation of the vast amount of linguistic information.

The implementation of our chatbot utilizes Chainlit, a Python library that serves as an interface for the core execution. This framework facilitates seamless communication and interaction with users, providing a robust foundation for addressing a variety of inquiries with efficiency and accuracy.
