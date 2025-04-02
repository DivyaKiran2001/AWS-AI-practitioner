# AWS AI Practitioner

## Domain 1

### 1. Amazon Rekognition

Amazon Rekognition is an AWS service for computer vision that enables extracting information and insights from images and videos.

#### Common Use Cases:
- **Content Moderation** - Detect inappropriate content.
- **Verify Identity** - Online identity verification.
- **Streaming Media Analysis** - Analyze media content in real-time.

### 2. Amazon Lex (AI Chatbot)

Amazon Lex is an AWS service used to build and deploy conversational AI interfaces.

#### Common Use Cases:
- **Self-Service Voice Assistants and Chatbots** - Automated customer interactions.
- **Application/Transaction Bots** - Assist with transactions and app workflows.

### 3. Amazon Bedrock

Amazon Bedrock is a fully managed service by AWS that enables developers to build and scale generative AI applications using foundation models (FMs) from leading AI model providers.

#### **Foundation Model:**
A large pre-trained AI model.

#### **Generative AI Use Cases:**
1. Text Generation
2. Image and Video Generation
3. Code Generation
4. Embeddings (Image or Document Search using Similarity Search)

---

## Domain 2

### 1. AWS Trainium
AWS Trainium is an AWS service used for training foundation models.

### 2. AWS Inferentia
AWS Inferentia is an AWS service used for deploying AI models efficiently.

### 3. Amazon SageMaker JumpStart
Amazon SageMaker JumpStart is a feature of Amazon SageMaker that helps developers and data scientists build, train, and deploy machine learning (ML) models at scale.

### 4. Amazon Q
Amazon Q is a fully managed, machine-learning-powered service providing real-time and interactive querying over large-scale datasets.

#### **Amazon Q Service Types:**
- **Amazon Q Business** - AI Assistant (Summarization, content creation, etc.)
- **Amazon Q Developer** - Coding Assistant
- **Amazon Q Connect**
- **Amazon Q QuickSight & Supply Chain**

### 5. PartyRock
PartyRock is a free playground for building generative AI applications.

#### **Amazon Q Business (ChatGPT with Enterprise Controls)**
A fully managed, generative AI-powered assistant that can:
- Generate content
- Summarize data
- Chat with enterprise data (e.g., S3, Salesforce)
- Assign tasks via plugins (e.g., JIRA)

#### **Amazon Q Developer**
A generative AI-powered assistant for software development that assists with:
- Coding and Testing
- Upgrading Applications
- Diagnosing Errors

### 6. Amazon Bedrock (Serverless)
Amazon Bedrock is a fully managed service allowing developers to build and scale generative AI applications using foundation models.

#### **Amazon Bedrock Pricing:**
- Based on the number of API requests and tokens.

#### **Use Cases:**
- Text Summarization, Code Generation, and other Generative AI applications
- Fully serverless
- AWS manages the infrastructure, hosting, and underlying complexities.

### **Architecture of Amazon Bedrock:**
1. **Internet**
2. **VPC Interface Endpoints**
3. **AWS Bedrock Service Account**
   - **Runtime Inference**: Routes API requests to the correct model endpoint.
   - **Base Model**

### **Amazon Bedrock Guardrails**
Amazon Bedrock Guardrails help implement safeguards for generative AI applications.

### **Amazon Bedrock Agents**
Enable generative AI apps to execute multi-step tasks across company systems and data sources.

**Example:** Processing insurance claims.

### **Amazon Bedrock Knowledge Bases**
AWS-managed service that allows customers to build RAG applications without requiring custom integrations.

### **Amazon Generative AI App - PartyRock**
A playground powered by Amazon Bedrock for building generative AI applications.

- No coding or AI/ML experience required.
- No AWS account needed.

### **Amazon SageMaker JumpStart Use Cases:**
1. Text Summarization, Code Generation, and other Generative AI use cases.
2. Infrastructure provisioning to deploy and fine-tune foundation models.
   - Open-source models
   - Proprietary models
3. Amazon SageMaker JumpStart provides access to foundation models deployed within a customer VPC.

### **AWS SageMaker JumpStart Service Offerings in Generative AI**
- **Fine-tuning**
- **Model Choices**
- **AWS Managed Features:**
  - **Scalability** - Autoscaling
  - **Availability** - Multi-AZ
  - **Monitoring** - CloudWatch

### **AWS EC2 Trainium**
- A type of EC2 instance with a purpose-built ML chip by AWS for deep learning models.
- Reduces training time for LLMs, including 100B+ parameter models.

### **AWS Inferentia2**
- Optimized for deploying LLMs and diffusion models for inferencing (output generation).
