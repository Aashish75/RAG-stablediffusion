# RAG-stablediffusion

This project combines Retrieval-Augmented Generation (RAG) with Stable Diffusion to enhance text-to-image generation with real-world knowledge. By integrating retrieved factual information into diffusion model prompts, we aim to create more realistic, meaningful, and contextually accurate images.


📌 Key Features

✅ Retrieval-Augmented Generation (RAG): Uses FAISS and Sentence Transformers to retrieve relevant real-world knowledge before image generation.

✅ Stable Diffusion Pipeline: Generates images conditioned on enhanced prompts that include retrieved factual information.

✅ CLIP-Based Evaluation: Assesses the alignment between generated images and text using CLIP similarity scores.

✅ Efficient FAISS Search: Uses semantic search with FAISS to retrieve knowledge from a Wikipedia dataset.

✅ Optimized Prompt Engineering: Enhances diffusion model performance by injecting real-world knowledge.

