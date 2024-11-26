# Literally Linear Model Chatbot (LLMChatbot)

So, suppose we use nonlinear LLM (chatGPT) to help us coding the LLMChatbot, I think that would be funny.

## Idea

So, instead of using deep learning, why don't we first create the embedding using `CountVectorizer` (which, should be linear enough) along with PCA. Then train the logistic regression (which is linear, if you say this is not linear then you don't know GLM) to predict the next token.
