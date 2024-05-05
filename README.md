# fintech

Master Science in Fintech - NYU 

This is part of capstone project that  explores the interconnected challenges of socio-economic disparities, financial instability, and health outcomes, particularly within low-income communities. It highlights how entrenched poverty not only perpetuates financial instability but also significantly affects physical and mental health, forming a vicious cycle that hinders socio economic uplift. In response, we introduce the Financial-First Holistic Wellness Chatbot, an innovative solution designed to break this cycle by offering tailored financial advice integrated with health and wellness support through an AI-driven platform. The chatbot leverages advanced machine learning algorithms and natural language processing to provide personalized, context-aware interventions that address the complex needs of users. This study outlines the development process of the chatbot, from conception through implementation, including a detailed analysis of its architectural framework and the integration of AI technologies. This paper argues for a shift towards more holistic and accessible solutions in tackling the poverty trap, emphasizing the role of technology in fostering sustainable socioeconomic development.

#Objective of Building the Prototype
The primary goal of this project is to develop a prototype that demonstrates how generative AI can be utilized to address specific challenges. We have elected to design a chatbot powered by a large language model (LLM) as a proof of concept to explore this potential.

#Options for Customization
Although a powerful pre-trained LLM offers substantial capabilities, it may not fully align with specific requirements straight out of the box. To better tailor the LLM to our needs, we consider several methods of customization:

-Full Fine-tuning: This approach involves adjusting all parameters of the LLM using data specific to our task, ensuring a comprehensive adaptation.

-Parameter-efficient Fine-tuning (PEFT): This method modifies only a subset of parameters, providing a balance between efficiency and performance.

-Prompt Engineering: This technique refines the inputs fed into the model to guide its outputs more effectively.

-Retrieval Augmented Generation (RAG): Combines prompt engineering with database querying, enhancing the contextuality of the model's responses.

#Proposed Architecture
For this prototype, we have chosen to implement both Prompt Engineering and RAG to fine-tune the LLM for our specific use case. This dual approach allows us to evaluate which method better serves our objectives under the following key performance indicators (KPIs): consistency, resource usage, response time, and relevance. Our architecture will enable comprehensive testing and comparison to determine the most effective proof of concept 
