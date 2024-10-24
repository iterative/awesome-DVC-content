# Awesome DVC Content
A repository containing links to the best and most up-to-date DVC/DataChain related content

<details markdown='1'><summary> 🏗️ Iterative Tool Repositories
</summary>

  [DVC](https://github.com/iterative/)

  [DataChain](https://github.com/iterative/DataChain)

  [CML](https://github.com/iterative/CML)

  [DVC VS Code Extension](https://github.com/iterative/vscode-dvc)
  
</details>

<details markdown='1'><summary>✍🏼 DataChain Blog
</summary> 
  
  [As GenAI Fever Fades - Time to Prioritize Robust Engineering Over Overblown Promises]( https://datachain.ai/blog/robust-engineering-over-overblown-promises) - The data stack generation is determined by a blend of emerging technologies and the applications they enable. We are now entering a new phase of data stack development, characterized by the adoption of foundational models, generative processes, faster time-to-value, and reduced data demands.
  
  [Scalable PDF Document Processing with DataChain and Unstructured.io](https://datachain.ai/blog/datachain-unstructured-pdf-processing) - The open source versions of DataChain and Unstructured.io can work together to scale PDF document processing. In this tutorial you will learn the steps to accomplish this including, how to create and save the DataChain, defining the UDF, and how DataChain versioning works.
  
  [Post-modern AI Data Stack](https://datachain.ai/blog/post-modern-ai-data-stack) - The data stack generation is determined by a blend of emerging technologies and the applications they enable. We are now entering a new phase of data stack development, characterized by the adoption of foundational models, generative processes, faster time-to-value, and reduced data demands.
  
  [You Do the Math: Fine Tuning Multimodal Models (CLIP) to Match Cartoon Images to Joke Captions](https://datachain.ai/blog/multimodal-clip-fine-tuning) - This tutorial shows how to fine tune multimodal models like CLIP to match images to text captions, using cartoons and their joke captions from The New Yorker caption contest.
  We tested the structured output capabilities of Google Gemini Pro, Anthropic Claude, and OpenAI GPT. In their best-performing configurations, all three models can generate structured outputs on a scale of thousands of JSON objects. However, the API capabilities vary significantly in the effort required to prompt the models to produce JSONs and in their ability to adhere to the suggested data model layouts
  
  [Announcing DataChain](https://datachain.ai/blog/datachain-release) - We are introducing DataChain - a new open-source tool that greatly complements DVC to data preparation and dataset curation via local ML models and LLM API calls.
  
  [Dataset Factory - A Toolchain for Generative Computer Vision Datasets](https://datachain.ai/blog/dvcx-dataset-factory-paper) - Data-Centric AI brings new challenges with cost and scale of data curation. Our latest tool DataChain solves these challenges where traditional MLOps tools fall short. This research paper discusses our approach.
  
  </details>

<details markdown='1'><summary>✍🏼DVC Blog
</summary> 
  
  [Tutorial: Scalable and Distributed ML Workflows with DVC and Ray (Part 1)](https://datachain.ai/blog/dvc-ray) - Training Models at scale require advanced tools that manage complexity while ensuring efficiency. This tutorial introduces you to integrating DVC with Ray, turning them into your go-to toolkit for creating automated, scalable, and distributed ML pipelines.
  
  [Tutorial: Scalable and Distributed ML Workflows with DVC and Ray on AWS (Part 2)](https://datachain.ai/blog/dvc-ray-part-2) - In part 2 of the tutorial on DVC with Ray.io, you will learn how to set up a Ray Cluster on AWS to run cloud-based distributed computing with focus on managing increased complexity and leveraging cloud infrastructure to maximize the efficiency and performance of your ML experiments.

  [Running DVC on a SLURM Cluster](https://datachain.ai/blog/dvc-slurm-cluster-exscientia) - For many ML projects, there comes a point when local development hits the wall and we need to scale up the underlying compute resources. Maybe the dataset grows too large for your primary workstation or the deep learning model requires several high-end GPUs. This should be a routine transition for ML developers, and one to which they shouldn’t have to give much thought. In this blog post, we’ll explain our approach to remote DVC experiments on a SLURM cluster and share some code to get you started with the same.

  [Tutorial: Automate Data Validation and Model Monitoring Pipelines with DVC and Evidently](https://datachain.ai/blog/automate-data-validation-and-model-monitoring-with-evidently-and-dvc) - Imagine you're in charge of weekly batch scoring jobs in a retail setting, where accurately predicting customer behavior is crucial. The challenge? Ensuring your machine learning models remain precise and efficient as time progresses, and verifying that your data consistently reflects the real-world scenario. This tutorial will equip you with the skills to use DVC and Evidently, transforming them into powerful allies for automating data validation and model monitoring pipelines. Tailored for Data Scientists, ML Engineers, MLOps professionals, and Team Leads, this guide offers a streamlined approach to boost and sustain your model's performance in the ever-evolving business landscape.

  [Integrating DVC and Git LFS via libgit2 filters](https://datachain.ai/blog/dvc-git-lfs) - Learn how the latest DVC release (version 3.31.0) now supports reading Git LFS objects, allowing users to import files from platforms like Hugging Face without additional dependencies. The implementation utilizes the Dulwich and pygit2 libraries, providing compatibility with Git LFS within DVC and enhancing its capabilities in managing datasets across Git repositories.

  [Leveraging LLMs in Chatbots: The DVC Approach](https://datachain.ai/blog/leveraging-llms-in-chatbots-the-dvc-approach) - This post explores how the Data Version Control (DVC) tool can enhance the efficiency and organization in designing LLM applications, using a Retrieval-Augmented Generation (RAG) chatbot as an example. This chatbot uses the RAG approach for its computational efficiency, provides cited sources for its answers, and leverages DVC features such as rollback capability, preventing redundant computations, and visual representation through a Directed Acyclic Graph (DAG).

  [Fine-Tuning Large Language Models with a Production-Grade Pipeline](https://datachain.ai/blog/finetune-llm-pipeline-dvc-skypilot) - In this post, we’ll walk through an end-to-end production ML pipeline for fine-tuning large language models using several key technologies: DVC for reproducible pipelines and efficient dataset versioning, SkyPilot for launching cloud compute resources on demand, HuggingFace Transformers and other libraries for efficient transformer model training, and quantization techniques like PEFT and QLoRA for reduced precision and memory usage.

  [The DVC 3.0 Stack: Beyond the Command Line](https://datachain.ai/blog/dvc-3.0-ml-experiments-data-versioning) - DVC has brought engineering best practices to the ML and data world, making model development more standardized and reproducible. Now we want to make it work when the command line isn't the right fit, and it's easier to work in code, an IDE, or on the web. This doesn't mean we forgot about DVC fundamentals — data versioning is the core of what we do.
  
  
  </details>


<details markdown='1'><summary>🎥 DataChain Videos 
</summary> 
    
  [Fine-tuning Multimodal Models (CLIP) with DataChain to Match Joke Captions to Images](https://youtu.be/KipLiOy7O54) - Learn how to fine-tune multimodal models like CLIP using DataChain in this comprehensive tutorial. Technical Product Manager, Dave Berenbaum walks you through: ingesting and processing image and text data, joining datasets using DataChain, calculating image-text similarities with CLIP, fine-tuning CLIP on custom datasets, and evaluating model performance before and after fine-tuning
  
  [Scalable PDF Processing with DataChain and Unstructured.io](https://youtu.be/yjzcPCSYKEo) - In this video, Tibor Mach demonstrates how to efficiently process large collections of documents using DataChain and Unstructured.io, two powerful open-source Python libraries. Learn how to clean text, create chunks, and generate vector embeddings for 10 to 1 million documents in just 65 lines of code!
  
  [Data Versioning in Generative AI: A Pathway to Cost Effective ML + Demo](https://youtu.be/Y9cEDSKGRlg) - Dmitry Petrov, CEO of Iterative, and creator of DVC, will present the challenges of data management in the GenAI era. He will discuss some of the key learnings from the last five years from our Community using DVC in the AI environment. This has led us to build DVCx, which offers extended capabilities to DVC, and a path forward to provide cost-effective data versioning of all the unstructured data of Generative AI (images, text, video, audio, multi-modal, etc). Dmitry will give a live demo of the new features of the tool!

  [Subscribe to our YouTube Channel](https://www.youtube.com/@dvcorg8370/videos)

</details>

<details markdown='1'><summary>🎥 DVC Videos
</summary> 
  
  [GitOps Best Practices: DVC Studio Model Registry for ML Development](https://youtu.be/T7MBFpnSr9Q) - Do you have a lot of models that you need to keep track of, monitor their states and share with your team? Jelle Bouwman, gives and in-depth tutorial on how to do just that with the DVC Studio Model Registry.  What makes the DVC Studio Model Registry special is its GitOps approach.  All model versions and their stages are tracked with commits and Git tags, merging your machine learning process with the best practices in software engineering.

  [DVC +  Git LFS for Seamless Hugging Face Model and Data Versioning](https://youtu.be/CHJYVmBrPdg) - Peter Rowlands, member of the DVC Core Team of engineers, shows of the new integration he built with Git LFS.  This integration enables any files stored with Git LFS to know easily be imported with DVC and versioned and tracked with DVC.  He shows the difference in how it worked with Hugging Face models and datasets before and after the release of 3.30  when the feature was added.  Now there's nothing holding you back from being able to reproduce all the great work you are doing with Hugging Face models and datasets and any other Git LFS stored files!

  [Applying GitOps Principles at Every Step of an E2E MLOps Project - A Workshop](https://youtu.be/2slmdfd73Rc) - With the emergence of IaC (infrastructure as code) tools, we have seen GitOps become an increasingly popular DevOps pattern that facilitates automation, reproducibility, and security. While hugely beneficial, applying the same principles in MLOps is not straightforward due to the specific aspects of the field such as the need to work with large amounts of data and the experimental nature of ML development. In this workshop, Tibor Mach will shows how we can bridge these gaps by using tools such as DVC. Step by step, he'll help you create an end-to-end MLOps pipeline that is centered around the Git repository as its single source of truth.

  [How to Turn Your IDE into a Machine Learning Experimentation Platform with the DVC ext for VS Code](https://youtu.be/6KtIRVfr61E) - Tapa Dipti Sitaula gives a tutorial on how to get started with the DVC Extension for VS Code.  She takes you through step by step from installing the plug-in to running, modifying, queueing, and viewing the results of your experiments in the experiment table and visualizing with plots.

  [Transforming a Jupyter Notebook into a Reproducible Pipeline for ML Experiments](https://youtu.be/sDhpIZQXe-w) - Rob De Wit's latest talk on transforming a Jupyter Notebook into a Reproducible Pipeline with DVC was presented at PyCon USA 2023.  In this project, he creates Pokemon Sprites with Stable Diffusion and LoRA in the Jupyter Notebook and then moves then sets up the stages from the notebook into a DVC pipeline to run experiments.  Finally, he shows a quick overview of the DVC Extension for VS Code. 

  [Best MLOps Practices for Building End-to-End Machine Learning Computer Vision Projects](https://youtu.be/E26IaD7bNXg) - In this workshop with DataTalks Club, we’ll build an end-to-end Computer Vision system using MLOps tools DVC, CML, the DVC extension for VS Code, and Iterative Studio along with Fast AI, nvtop and Docker.

  [Subscribe to our YouTube Channel](https://www.youtube.com/@dvcorg8370/videos)


</details>


<details markdown='1'><summary>📰 Newsletters
</summary> 
  Our newsletters contain the latest in content from the team, what we're looking at in the industry, and a list of recent content produced by our fantastic community!  
  
  [Subscribe to the email newsletter](https://dvc.us10.list-manage.com/subscribe?u=a08bf93caae4063c4e6a351f6&id=24c0ecc49a)

  [Subscribe to the LinkedIn version](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7066535890772242432)

  ---

  [October 2024 DVC Pulse](https://mailchi.mp/2bfbec7a31c4/october-24-newsletter)

  [August 2024 DVC Pulse](https://mailchi.mp/776bcdf24789/august-24-newsletter)

  [June 2024 DVC Pulse](https://mailchi.mp/1eaa3be8da82/june-24)

  [May 2024 DVC Pulse](https://mailchi.mp/8aab124f7224/may-24)

  [April 2024 DVC Pulse](https://mailchi.mp/5a03ec411585/april-24)

  [February 2024 Newsletter](https://mailchi.mp/b8dff9b5eead/february-24)

  [January 2024 Newsletter](https://mailchi.mp/d5cecb2320cf/january-2024)

  [December 2023 Newsletter](https://mailchi.mp/cdc1ac146bc4/december23)

  [November 2023 Newsletter](https://mailchi.mp/65a73d280db4/november23)

  [Subscribe to the email newsletter](https://dvc.us10.list-manage.com/subscribe?u=a08bf93caae4063c4e6a351f6&id=24c0ecc49a)

  [Subscribe to the LinkedIn version](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7066535890772242432)
  

</details>

<details markdown='1'><summary>🫶🏻 Community Member Use Case Videos
</summary> 

  [Building Ethical AI: Leveraging DVC for Transparency and Trust in LLM Applications](https://youtube.com/live/Q1vBxzkrJec?feature=share) - In an era where AI technologies are pervasive, ensuring their ethical deployment is paramount. Join Beth Rudden, CEO of Bast AI and renowned ethical AI leader, as she explores the critical role of transparency and trust in AI development.

  [Achieving Production Level Performance in RAG with DSPy, Parea, and DVC](https://youtube.com/live/RBeZ2nXz7wA?feature=share) - RAG PoCs are easy but production-level performance is hard. Jointly optimizing retrieval and generation is a time-consuming process with backtracking the best solution being even harder. What if you could focus solely on defining the architecture of your RAG pipeline? Joschka Braun shows us how to iterate on RAG apps with DSPy, DVC & Parea.

  [Panel Discussion on Regulation and the Imperative for Reproducibility and Standardization in AI/ML](https://youtube.com/live/eHf4hgZ2BGo?feature=share) - Join us for a thought-provoking and insightful virtual gathering as we delve into questions surrounding the Regulation of AI/ML and the need for Reproducibility and Standardization of processes in light of those regulations.  Our panelists, Alexander Hasha, Estefania Baretto Ojeda, and Charles Vardeman hail from the worlds of Finance and Banking, Drug Discovery, and Academia, areas at the forefront of navigating the regulation of AI/ML. They will share their perspectives on these issues through the lens of their experience in their industries.  

  [Expert Insights on Developing Safe, Secure, And Trustworthy AI](https://youtube.com/live/awTeSmaYyCo?feature=share)  - Charles Vardeman joins us from the University of Notre Dame where he is a Computational Scientist in the Center for Research Computing and a Research Assistant Professor of Computer Science Engineering. He will share with us his team's Trusted AI (TAI) lessons learned two years into the course of their US Federally funded TAI research projects. The team created a framework for Trustworthy AI that automates setup so that developers and decision-makers can focus their efforts on strategy and innovation instead of wrangling the complexities of setting up such a system. This framework covers, Privacy, Sustainability, Accountability, Explainability, Safety and robustness, and Fairness issues at every part of the operational environment. It leverages GitOps and a Data-centric approach as foundational components to automate and streamline the development pipeline and achieve Trustworthy AI.
  
 [Great Practices for Retrieval Augmented Generation in Production](https://youtu.be/vZTvzEuOhMk) - While it has recently become widely accessible to develop a Proof-Of-Concept for Retrieval Augmented Generation (RAG) using OpenAI and one of the various open-source contributions on the topic, transitioning to a production-ready pipeline presents its own set of challenges. In this talk, Noé Achache will share great practices for building a RAG product based on his experience developing Hikari, a bot utilized by hundreds of individuals within the Theodo Group, which continuously ingests documents from the group, such as those from Notion or HubSpot. These practices include (but are not limited to) using a Directed Acyclic Graph (DAG) for continuous document ingestion (e.g., with Airflow), iterating on prompts, chunks, models, and more (e.g., with DVC), as well as understanding when, why, and how to switch to open-source models.

 [How to Choose a Vector Database](https://youtube.com/live/aX_hdQEintc) - Noé Achache of Theodo - Data & AI joins us to present How to Choose a Vector Database in 2023.  Noé explores the evolving landscape of vector databases in the context of rising interest in LLMs and Generative AI. He offers a comparison of various vector databases, advising readers on choosing between integrated vector search tools like PGVector and knn search for existing databases versus dedicated vector databases such as Pinecone, Qdrant, Weaviate, Milvus, and ChromaDB, for cost and latency concerns.

 [MLOps: The Strategic Compass for AI-Driven Enterprises](https://youtu.be/AdmtbwOyTS0) - As AI continues to reshape industries, the challenge lies in efficiently deploying and scaling these solutions. MLOps, the fusion of Machine Learning and operational practices, offers a strategic guide for AI-driven enterprises. Drawing from over a decade of experience, we’ll share industry insights on applying MLOps, contrasting the theory with its practical application. In this talk, Diego Kiedanski of TryoLabs discusses the challenges they’ve faced, the lessons learned, and the issues they are yet to resolve. He also highlights MLOps’ role in translating AI’s potential into business results and discusses the critical human element, touching on both technical and organizational changes required for successful implementation.

 [ZnTrack: DVC Machine Learning Pipelines in Python and Jupyter Notebooks](https://youtu.be/7ZgBydEPHwA) - Fabian Zills, PhD Student at the University of Stuttgart, presents on ZNTrack, a way to create, run, and benchmark DVC Pipelines in Python.

[Data Versioning: Towards Reproducibility in Machine Learning](https://youtu.be/P5Eqyl38buk) - Nicolás Eiris, Machine Learning Engineer at Tryolabs, presents the "Data Versioning: Towards Reproducibility in Machine Learning" tutorial at the May 2022 Embedded Vision Summit.

[From Notebook to Pipeline in No time with LineaPy and DVC](https://youtu.be/tA5olYLjHPA) - Community member Thomas Fraunholz presents how to use LineaPy to transform your notebook into a reproducible pipeline with DVC at PyCon/PyData Berlin.  

[How to Use DVC for Applications in ML Drug Discovery Pipelines|(https://youtu.be/XPawEJRGr9c) - Community member Estefania Barreto-Ojeda shares how they use DVC at Cyclica for Applications in ML Drug Discovery Pipelines.  This talk was originally given  @PyDataTV   NYC in the Fall of 2022.

[Zero to MLOps Hero: How to be more awesome through open source](https://youtu.be/0RJUnD9nHnw) - Matt Squire of Fuzzy Labs joined us sharing his view on open-source MLOps tools. Matt breaks down the tool space into categories of SaaS platforms, fully open source, and partly open source tools. He describes how they define open source and why they think open source is the best choice in the MLOps space, which includes its traits of being flexible, ownable, cost-effective, and agile.

[Continuous Machine Learning at Billie: Using CML for training financial data](https://youtu.be/0MDrweODzw8) - Gennaro Tedesco shows us how he has built CML into his MLOps workflows at Billie.io to automate processes and save time processing their financial data. In addition, he created a plug-in to use DVC from within neovim. If you're a neovim lover, checkout the repo here and join us at the Meetup: https://github.com/gennaro-tedesco/nvim-dvc

[How to use DVC, PyCaret, and FastAPI for Machine Learning Workflow](https://youtu.be/FGrSQcEvg9E) - In this video, Tezan Sahu will show you how to use DVC, PyCaret and FastAPI to create a machine learning workflow that covers data and model versioning, experimentation with ML models and deployment of models as web APIs.

[Continuous Computer Vision with DVC, CML, and DeepChecks at DeepXHub.com](https://youtu.be/GEpmbgR9dLo) - Dmytro Filatov, CEO of DeepXHub presents Continous Computer Vision with DVC, CML and DeepChecks.  This presentation is a great example of a real-life use case in computer vision using DVC, CML, and DeepChecks.  Dmytro reviews the major pain points of what life was like for his team before using DVC and CML and the gains that they have received since using the tools.

[Designing a Model Registry with Legacy Systems Using DVC and GTO with Francecso Calcavecchia](https://youtu.be/OqLS3dKer_E) - Francesco has contributed a ton to GTO ([https://iterative.ai/gto](https://iterative.ai/gto)), one of the components of our [MLEM.ai](http://mlem.ai/) tool to help create a model registry and then easily package and deploy your models for production, all while tracking everything with Git.

[Running Parallel Pipelines with DVC and TPI by Sami Jawhar](https://youtu.be/X3M1UfMn2Kk) - Community champion Sami Jawhar joins us to present how he solved running parallel pipelines with DVC and TPI in his work for Kernel (https://kernel.com).  Sami gives an overview of the problem he was trying to solve (a vast amount of data and the need for parallel processing) and the context and constraints under which he operates.  If you are working with on-prem constraints this may be a good solution for you to review! He shows the details of his solution, coined "Neuromancer" after the famous sci-fi novel, and answers questions along the way.  We love seeing the ingenuity of our Community members with our tools!

[Collaboration Challenges in ML-Enabled Systems with Nadia Nahar](https://youtu.be/FKdVSNfnD_M) - Nadia Nahar, Software Engineering Ph.D. Student at Carnegie Mellon, discuss with us her recently published work entitled: Collaboration Challenges in Building ML-Enabled Systems: Communication, Documentation, Engineering, and Process (https://arxiv.org/pdf/2110.10234.pdf), in which she and her colleagues interviewed 45 ML practitioners from 28 industries to learn about the challenges they face when building ML-enabled systems. This year-long research received ACM SIGSOFT Distinguished Paper Award in the International Conference on Software Engineering (ICSE) 2022.

</details>

Would you like to see or contribute to some awesome projects that use DVC?  Head to our [Awesome Iterative Projects repo](https://github.com/iterative/awesome-iterative-projects).

[Join our Online Course here!](https://learn.dvc.ai)

Need support help?
[Join our Discord Server](https://discordapp.com/invite/dvwXA2N)
[Join our Discourse forum](https://discuss.dvc.org/)
[Email us!](support@dvc.org)

 

 

 

 </details>
