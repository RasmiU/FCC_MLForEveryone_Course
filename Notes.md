### What is machine learning?
- ML is a subdomain of computer science that focuses on algorithms which help a computer learn from data without explicit programming.

### Types of ML:
- Supervised learning: Uses labeled inputs (meaning the input has a corresponding output label) to train models and learn outputs.
- Unsupervised learning: Uses unlabeled data to learn about patterns in data -> Finding structure in unlabeled data.
- Reinforcement learning: Agent learning in interactive environment based on rewards and penalties.

### Supervised learning
- Feature vector (inputs) -> MODEL -> Output (prediction)
- Features:
  - Qualitative:
    - categorical data (finite number of categories or groups). Ex: Gender types, nationalities.
    - Nominal data (no inherent order).
      - One-Hot encoding:
        - One Hot Encoding is a method for converting categorical variables into a binary format. It creates new columns for each category where 1 means the category is present and 0 means it is not. If we were to assign numerical values (e.g., Male = 0, Female = 1) the model might mistakenly interpret this as a ranking and lead to biased predictions. One Hot Encoding eliminates this risk by treating each category independently. (Source: GeeksForGeeks)
    - Ordinal data (have inherent order). Ex: stages of human life, rating (bad, good, great, etc.).
      - Could used Label encoding:  assigns a unique integer to each category in the data. (Source: GeeksForGeeks) 
