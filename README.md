# Visual Grounding with Dual Knowledge Distillation (TCSVT 2024)

Visual grounding is a task that seeks to predict the specific location of an object or region described by a linguistic expression within an image. Despite the recent success, existing methods still suffer from two problems. First, most methods use independently pre-trained unimodal feature encoders for extracting expressive feature embeddings, thus resulting in a significant semantic gap between unimodal embeddings and limiting the effective interaction of visual-linguistic contexts. Second, existing attention-based approaches equipped with the global receptive field have a tendency to neglect the local information present in the images. This limitation restricts the semantic understanding required to distinguish between referred objects and the background, consequently leading to inade- quate localization performance. Inspired by the recent advance in knowledge distillation, in this paper, we propose a DUal knowlEdge disTillation (DUET) method for visual grounding models to bridge the cross-modal semantic gap and improve localization performance simultaneously. Specifically, we utilize the CLIP model as the teacher model to transfer the semantic knowledge to a student model, in which the vision and language modalities are linked into a unified embedding space. Besides, we design a self-distillation method for the student model to acquire localization knowledge by performing the region-level contrastive learning to make the predicted region close to the positive samples. To this end, this work further proposes a Semantics-Location Aware sampling mechanism to generate high-quality self-distillation samples. Extensive experiments on five datasets and ablation studies demonstrate the state-of-the- art performance of DUET and its orthogonality with different student models, thereby making DUET adaptable to a wide range of visual grounding architectures.

# Code 
Coming Soon
