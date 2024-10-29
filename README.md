# Data Scientist
#### Technical Skills: Python, Tensorflow, Pytorch, NLP, Computer vision, Google Cloud platform, VertexAI

### Education
- Preparatory cycle for engineering studies in Physics and Chemistry | Institut préparatoire aux études d'ingénieur de Bizerte 
- Computer Engineering | Ecole Sup Privée d'Ingénierie et de Technologies ESPRIT

## Projects

### Chatbot Assistant Broadcast domain
Develop a sophisticated chatbot AI assistant designed to listen in on conversations between support staff and customers, guiding and assisting the supporter in resolving customer issues. This system utilizes Retrieval Augmented Generation (RAG) with parent document retrieval for enhanced information access. Additionally, it incorporates a memory workflow involving two language models (LLMs): the first LLM analyzes input while reviewing conversation history to generate a new input based on past interactions. The second LLM then takes the output of the first, along with contextual data from the RAG, to formulate responses drawing on previous conversations, without relying on external knowledge. \n  
**Technologies**: GCP, Vertex AI, LangChain, Gemini 1.5-Pro, AssemblyAI.

### Chatbot Assistant Project Management
Develop a chatbot assistant for the Project Management Body of Knowledge (PMBOK) book. The workflow begins with preprocessing the book’s figures and tables, converting them to text using LlamaParse. This text is then chunked and processed to build a knowledge graph, using GroqAPI’s "LLama 3.2" model, which extracts nodes and relationships, complete with attributes like definitions and synonyms. The resulting graph is stored in Neo4j. Finally, GraphRAG and prompt engineering techniques are applied to respond to user questions, drawing on relevant context from the graph.
**Technologies**: NLP,Llamaindex, Langchain, GraphRAG, Llama3.2, Neo4j.\n 

### Automated Dental Radiograph Interpretation and Reporting System
The project aims to develop an AI-driven system to analyze dental panoramic radiographs, identify tooth anomalies, classify their severity, and generate a comprehensive report. The workflow begins by training FastRCNN and YOLOv11 models to detect each of the 32 teeth as individual classes. Next, a fusion model combines YOLOv11 and DINO Swin to detect anomalies across four classes. The outputs from these models, structured as a JSON file, are then processed by GPT to produce the final report, presented to users through a Softr interface.
**Technologies**: GCP, Vertex AI pipelines, Computervision.\n 

### Car penalty automation
Automates car penalty management for Swiss Premium Negoce by employing Surya OCR for text extraction from images, followed by fine-tuning with LORA Mistral AI to ensure accurate extraction of relevant data in XML format, This streamlined process enhances efficiency and accuracy in determining penalty liability.\n 
**Technologies**: OCR, LORA, LLM.

### Object Detection Using Adaptive Mask R-CNN in Optical Remote Sensing Images
Enhancing object detection in optical remote sensing images through the utilization of Adaptive Mask R-CNN. Our approach involved fine-tuning Mask R-CNN using PyTorch on satellite imagery to achieve precise image segmentation and object detection. Despite the given data consisting solely of bounding boxes for object classes and corresponding images, we implemented a novel process. We leveraged transformers, specifically SAM-ViT-Huge, to process these bounding boxes, generating masks for each object. These masks were then fed into Mask R-CNN for training.


## Certifications
**Building Transformer-Based Natural Language Processing Applications @ Nvidia** [Show credential](https://learn.nvidia.com/certificates?id=ahaye6feRYeSQh06u6mn8g)

**Google Advanced Data Analytics @ Google** [Show credential](https://www.coursera.org/account/accomplishments/professional-cert/SQMNADXE4MRZ)

**AI Fundamentals Certificate @ DataCamp** [Show credential](https://www.datacamp.com/skill-verification/AIF0027935450689)

**Convolutional Neural Networks in TensorFlow** @ DeepLearning.AI [Show credential](https://www.coursera.org/account/accomplishments/certificate/KLF7Z2MU6WGN)

**Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning** @ DeepLearning.AI [Show credential](https://www.coursera.org/account/accomplishments/certificate/RR84ZBJ5V72U)
