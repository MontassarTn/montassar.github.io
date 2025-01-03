# Machine learning Engineer
#### Technical Skills: Python, Tensorflow, Pytorch, NLP, Computer vision, Google Cloud platform, VertexAI

### Education
- Preparatory cycle for engineering studies in Physics and Chemistry | Institut préparatoire aux études d'ingénieur de Bizerte 
- Computer Engineering | Ecole Sup Privée d'Ingénierie et de Technologies ESPRIT

### Professional Experience 
- Freelancer Machine learning Engineer at Adopt-AI : Present

## Projects

### Chatbot Assistant Broadcast domain [Link Video](https://www.youtube.com/watch?v=3xhqRF668u4)
Develop a sophisticated chatbot AI assistant designed to listen in on conversations between support staff and customers, guiding and assisting the supporter in resolving customer issues. This system utilizes Retrieval Augmented Generation (RAG) with parent document retrieval for enhanced information access. Additionally, it incorporates a memory workflow involving two language models (LLMs): the first LLM analyzes input while reviewing conversation history to generate a new input based on past interactions. The second LLM then takes the output of the first, along with contextual data from the RAG, to formulate responses drawing on previous conversations, without relying on external knowledge. <br>
**Technologies**: GCP, Vertex AI, LangChain, Gemini 1.5-Pro, AssemblyAI.

### Chatbot Assistant Project Management domain [Link Video](https://www.youtube.com/watch?v=iJQSa4qwFJk)
Develop a chatbot assistant for the Project Management Body of Knowledge (PMBOK) book. The workflow begins with preprocessing the book’s figures and tables, converting them to text using LlamaParse. This text is then chunked and processed to build a knowledge graph, using GroqAPI’s "LLama 3.2" model, which extracts nodes and relationships, complete with attributes like definitions and synonyms. The resulting graph is stored in Neo4j. Finally, GraphRAG and prompt engineering techniques are applied to respond to user questions, drawing on relevant context from the graph. <br>
**Technologies**: NLP, Llamaindex, Langchain, GraphRAG, Llama3.2, Neo4j.

### Automated Dental Radiograph Interpretation and Reporting System [Link Video](https://www.youtube.com/watch?v=iT92X2xBneA)
The project aims to develop an AI-driven system to analyze dental panoramic radiographs, identify tooth anomalies, classify their severity, and generate a comprehensive report. The workflow begins by training Dino with RESNET backbone model to detect each of the 32 teeth as individual classes. Next, a fusion model combines YOLOv11 and DINO Swin to detect anomalies across four classes. The outputs from these models, structured as a JSON file, are then processed by GPT to produce the final report, presented to users through a Softr interface. <br>
**Technologies**: GCP, Vertex AI, Cloud run, GPT, Computervision.

### Automated Newsletter Generation Using AI Agents [Link Video](https://www.youtube.com/watch?v=Zh1YDAcvi3M)
This project automates newsletter creation on any topic by using AI agents and semantic search to gather, summarize, and organize content into an HTML newsletter. Starting with the EXA Semantic Search Engine to find relevant web content, the Crew AI Agents (Researcher, Editor, and HTML Generator) each handle specific tasks—researching articles, refining summaries, and compiling them into an HTML format. Supported by tools for fetching and comparing articles, and using Gloq and Llama 3.1 (70b) APIs, this system seamlessly streamlines newsletter generation from research to final layout. <br> 
**Technologies**: EXA, CrewAI, LLM.

### Car penalty automation [Link Video](https://www.youtube.com/watch?v=pmaIApRVV6Q)
Automates car penalty management for Swiss Premium Negoce by employing Surya OCR for text extraction from images, followed by fine-tuning with LORA Mistral AI to ensure accurate extraction of relevant data in XML format, This streamlined process enhances efficiency and accuracy in determining penalty liability. <br>
**Technologies**: OCR, LORA, LLM.

### Object Detection Using Adaptive Mask R-CNN in Optical Remote Sensing Images
Enhancing object detection in optical remote sensing images through the utilization of Adaptive Mask R-CNN. Our approach involved fine-tuning Mask R-CNN using PyTorch on satellite imagery to achieve precise image segmentation and object detection. Despite the given data consisting solely of bounding boxes for object classes and corresponding images, we implemented a novel process. We leveraged transformers, specifically SAM-ViT-Huge, to process these bounding boxes, generating masks for each object. These masks were then fed into Mask R-CNN for training.

### AI-Generated vs Human Text Classification
Fine-tuned the DeBERTaV3 model to classify AI-generated versus human-written text, using stratified Kaggle datasets split by labels (0 for human, 1 for AI). My process included preprocessing text into tokenized sequences with padding masks, building data pipelines via TensorFlow’s tf.data API, and implementing a learning rate scheduler with gradual decay. The Keras-based model, with DeBERTaV3 as the backbone, trained over three epochs to optimize accuracy. The resulting model effectively identifies text origin, distinguishing between human and AI-generated content.

## Certifications
**Natural Language Processing @ DeepLearning.AI** [Show credential](https://www.coursera.org/account/accomplishments/specialization/U4522SV4CUJC)

**Building Transformer-Based Natural Language Processing Applications @ Nvidia** [Show credential](https://learn.nvidia.com/certificates?id=ahaye6feRYeSQh06u6mn8g)

**Google Advanced Data Analytics @ Google** [Show credential](https://www.coursera.org/account/accomplishments/professional-cert/SQMNADXE4MRZ)

**AI Fundamentals Certificate @ DataCamp** [Show credential](https://www.datacamp.com/skill-verification/AIF0027935450689)

**Convolutional Neural Networks in TensorFlow** @ DeepLearning.AI [Show credential](https://www.coursera.org/account/accomplishments/certificate/KLF7Z2MU6WGN)

**Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning** @ DeepLearning.AI [Show credential](https://www.coursera.org/account/accomplishments/certificate/RR84ZBJ5V72U)
