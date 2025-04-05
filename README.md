# Basic Implementation of Encoder of Attention Transformer (Attention Is All You Need)

📄Paper link: Attention Is All You Need (arXiv:1706.03762)

📂 This Repo Includes

     ✅ Encoder implementation in PyTorch with explanations of critical concepts.
          
     🏘️ A dataset on which a recommendation program was built.
          
     🤖 An apartment recommendation program using a custom Encoder built from scratch in PyTorch.


🔧 Encoder Implementation in PyTorch
    Key components covered:
    
     ✨ Residual Connections
      
     🌀 Positional Encoding
      
     🧠 Self-Attention and Multi-Head Attention
   
     📏 Why dot product of query and key vectors can get large and how to scale them properly

🏠 Dataset and Recommendation Program

   * The dataset consists of apartment listings with various columns.
   
   * For building the recommendation system, I primarily used the TopFacilities and PropertyName columns.
   
   * The model leverages the Attention Mechanism to capture relationships between facilities, creating a vector representation for each apartment by averaging the       
   embeddings of its facilities.
   
   * I used cosine similarity to find the most similar apartments and torch.topk() to retrieve the top-k most similar listings to the apartment a user is viewing.


   

        
