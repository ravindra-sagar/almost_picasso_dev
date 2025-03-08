# What is CLIP?

1. **CLIP** stands for **Contrastive Language-Image Pairs**.
2. It acts as a bridge between the modalities of **Image** and **Text**.
3. A **common vector space** for both text and images is created:
    - **Text** is embedded using a **text transformer**.
    - **Image** is embedded using an **image transformer**.
4. Text and images that denote similar things are **very close to each other** in this vector space.
5. Text and images that denote different things are **far away from each other** in this vector space.