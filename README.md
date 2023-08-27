## Text Generation using Scriptures of Game of Thrones Book

Kaggle Notebook: https://www.kaggle.com/code/shirshmall/text-generation-nlp

**Project Overview:**
The "Text Generation using Scriptures of Game of Thrones Book" project explores the fascinating realm of natural language processing by leveraging the rich textual content from the "Game of Thrones" book series. The objective is to develop a model that can generate coherent and contextually relevant text, emulating the distinctive narrative style of the renowned series.

**Key Project Steps:**

1. **Data Pre-processing and Feature Extraction:**
   - Performed thorough pre-processing of the textual data from the "Game of Thrones" book series.
   - Applied tokenization techniques to break down the text into smaller meaningful units.
   - Extracted relevant features that serve as inputs for training the text generation model.

2. **Sliding Window Dataset Creation:**
   - Transformed the book's text data into a sliding window dataset using the window method.
   - This approach involves sliding a window of fixed size over the text data, creating input-output pairs for supervised learning.

3. **LSTM and GRU Neural Network Implementation:**
   - Implemented a Text Generation Model utilizing LSTM (Long Short-Term Memory) and GRU (Gated Recurrent Unit) neural network architectures.
   - These recurrent neural networks are well-suited for sequence data and can capture dependencies in text.

4. **Text Generation using Greedy Search Inference Loop:**
   - Developed a simple yet effective greedy search inference loop to predict the next word in the generated text.
   - Trained the model on the prepared dataset to generate new text that maintains context and relevance.

5. **Integration of GPT Model from Hugging Face:**
   - Integrated the GPT (Generative Pre-trained Transformer) model from the Hugging Face Transformers library.
   - GPT is a state-of-the-art language model known for its exceptional text generation capabilities.

**Project Outcome and Insights:**
The project successfully achieved the generation of new text that emulates the writing style of the "Game of Thrones" series. The LSTM and GRU neural networks, along with the incorporated GPT model, demonstrated the potential of machine learning techniques for creating coherent and engaging text. The generated text captures the essence of the original narrative and contributes to the exploration of creative AI applications in the realm of literature.

**Relevance and Significance:**
The project highlights the advancement of natural language processing techniques in enabling machines to understand and generate human-like text. Text generation has far-reaching applications, including content creation, chatbots, and creative writing assistance. Leveraging well-established literature for this project adds a unique dimension by blending modern AI with beloved narratives.
