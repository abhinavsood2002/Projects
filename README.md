# Past Experience and Projects
Hi everyone, I am Abhinav. This repository serves as a central location to document my experience in different projects I have completed as a part of my work and studies. The repository links provided might not link to the original codebases (some of which are private). Instead appropriate sections of those codebases are collected. 


| Brief Project Description                                             | Type                | Brief Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | My Contributions                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Repository Link |
|-----------------------------------------------------------------------|---------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------|
| Graphical Chain-Based Prompting of LLMs for Creative Writers          | Honours Project     | Traditionally, when interacting with an LLM (Large Language Model), users are presented with a one-on-one chat-like interaction. This imposes restrictions on how users can interact with systems. For example, given how context is usually processed for LLMs, the output of each prompt depends on all previous interactions, even if the conversations are independent. This project investigates whether an alternative interface, one where users chain nodes much like nodes in a graphical programming language, can produce better outcomes for creative writers.                                          | I was responsible for the project idea, literature review, project plan and construction/implementation of the system. A research paper (first-author) based on this work has been submitted to the International Conference on Computational Creativity (ICCC-2024). This project was conducted as part of my Honours Thesis at Monash University under the supervision of Dr. Maria Teresa Llano and Prof. Jon McCormack.                                                                                                                                                                                                                                                            |                 |
| Attribute-Based Latent Space Regularisation with VAE-Diffusion Models | Project at Sensilab | Diffusion Models provide incredible modelling capabilities for Generative Image systems. However, they also demonstrate a lack of fine-precision controllability. This controllability can be important for artists who might want to vary generations from these systems across specific parameters. Text-conditioned diffusion models also fail to provide controllability against precisely defined parameters. In this project, the use of attribute-based latent space regularisation in the DiffuseVAE model was demonstrated to be an effective way to provide fine control of generations across parameters | I was primarily involved in implementing the codebase for the system. This required an understanding of the [DiffuseVAE](https://github.com/kpandey008/DiffuseVAE) and [AR-VAE](https://github.com/ashispati/ar-vae) codebases making key parts of them compatible. Additionally, I constructed heuristics/functions for the 4 parameters across which the 2 datasets involved would be controlled. A research paper(second-author) based on this work has been submitted to IJCAI-2024 - Creativity and Arts Track. My contribution to this project occurred initially under a Summer Vacation Research Scholarship at Monash University. Further work continued in my personal time. |                 |
| Preliminary Implementations for MachineEye and MagneticPoetry         | Project at Sensilab | Artists make creative decisions in the context of their environment. This means their surrounding play an important role in their artistic practice. On the basis of this observation, MachineEye was a project that was meant to investigate whether integrating environmental information like images and sound could help with designing a better LLM framework that could assist artists in their creative practice. However, due to issues with privacy, this was later repurposed into a creativity support tool that used a magnetic poetry set.                                                             | I was involved with the image capture system for the machine eye. This included working with a Raspberry Pi 4 with a Luxonis AI camera that could detect significant events for capture (to prevent data overflow) and send that data to a local server for further processing. For the Magnetic Poetry conversion, I implemented a proof of concept OCR-based system that could detect text from a magnetic poetry set on a board. This was later replaced by the research team at Sensilab for a system that did not require OCR. This work was conducted as part of a Casual Research Assistant position at Sensilab.                                                               |                 |
| Exploring the potential PrivateGPT for Oblique Strategies             | Project at Sensilab | Oblique Strategies are a card-based strategy used to overcome creative blocks that involve randomly selecting cards with instructions encouraging the user to approach their problem unconventionally. This project explored whether [PrivateGPT](https://github.com/zylon-ai/private-gpt/tree/78d1ef44adea1b72235a4cb603bbf0e4d9033d10) could be used to provide more context (through text vector retrieval) to an LLM for possible future work on using LLMs for some form of creativity support tool.                                                                                                           | At the time, we were using Brian Eno's diary to source oblique strategies. I set up experiments that ran on docker containers accessible to other collaborators with different configurations of notes from the diary, different LLMs and different questions to test the feasibility of using the system. PrivateGPT didn't offer official GPU support when the project was being conducted and only mentioned the GPT4ALL llm. Thus, time was also spent reading Github issues to configure Vicuna and other quantized models with PrivateGPT. This project was completed as part of a Casual Research Assistant position at Sensilab.                                               |                 |
| Playing Inflexion: An AI for a Novel 2-player game                    | University Project  | To be Added.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | To be Added.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                 |
