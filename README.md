# YetAnotherWeb3App
I'm thinking kind of like an open source language model on the block chain where tokens are awarded for training

1. Distributed training; https://arxiv.org/abs/2301.11913
2. Can rent small scale GPUs with decent bandwidth; https://cloud.vast.ai/create/
3. In reward for updating weights, people will get "points".
   -  I'm not sure if this is worth anything?
   -  Maybe people will pay money for points to advance the capabilities of the model?
   -  Need to really think about this part; are we assigning some kind of ownership, or is just for the love of the game?
4. Will have a complete log of every node in the model and what data has passed through it
5. Maybe some ability to prune nodes, with their removal logged and their history saved in separate archives. Will always be recoverable
6. Maybe using something like IPFS? https://ipfs.tech/

Limitations:
1. I can't really change the architecture. This seems like a big problem. 
2. Maybe make the architecture somewhat flexible? Based on basic conversation with chatGPT, it's not a big issue and modern frameworks allow for flexible models with transfer learning https://chat.openai.com/share/db4c0a88-90ae-4c36-bc2b-69759d801cc2
