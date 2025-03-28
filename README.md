# Dress-Designer-Party

### **Flux-CatVTON Empowered Commercial-Grade Haute Couture Generation: Multimodal Closed-Loop Optimization with DeepSeek-Janus**

![image1](images/image1.png)

      This repository constitutes a proprietary AI-generated application deployed for evening gown and haute couture fashion presentation scenarios, encompassing ComfyUI workflows and external URL integration. The workflow is designed with multi-modal, multi-model collaborative optimization through a multi-level closed-loop architecture:

1. Leveraging LLMs such as DeepSeek-R1 under prompt engineering guidance, achieving hierarchical optimization from inspirational element texts to design concepts, and from scene descriptions to model representations.
2. Implementing cascade generation mechanisms through FLUX.1 model ecosystem components - utilizing Fill models (partial inpainting & image extension) with Redux adapters (image variation & style migration), coordinated with In-Context-LoRA contextual generation models to maintain thematic consistency.
3. Employing Janus-Pro-7B's cross-modal comprehension integrated with Segment Anything Model (SAM) for secondary iterative refinement of garment details and automatic mask segmentation.
4. Incorporating FLUX.1-Turbo-Alpha for multi-stage accelerated diffusion generation throughout the workflow pipeline, combined with CatVTON processing outputs to achieve high-efficiency, high-precision visual transformations.

![image2](images/image2.png)

     The current implementation of CatVTON workflow still requires manual mask annotation (e.g., https://huggingface.co/spaces/xiaozaa/catvton-flux-try-on) for target area specification, which introduces inefficiencies and cognitive discontinuity in proprietary applications. To address these limitations, my workflow strategically integrates In-Context-LoRA with Redux modules to achieve fuzzy-consistent generation of primary garment elements. This dual mechanism ensures:
     Cross-Image Coherence: Maintains structural and stylistic consistency across product variations through latent space alignment; Replaceable Zone Preservation: Embeds predefined replacement zones during initial generation phase for subsequent CatVTON operations; Automation Optimization: Mitigates region recognition errors in automated masking systems when processing heterogeneous object forms

     By implementing this hybrid approach, can effectively decouple the manual mask dependency cycle while maintaining precise control over garment replacement parameters, thereby streamlining the iterative design process from conceptual generation to visual refinement.

![image3](images/image3.png)

This repository will publicly release the complete workflow architecture and prompt engineering framework documentation, including:

1. **Garment Generation Module**
2. **Model Attire Projection System**
3. **Integrated Production Suite**

Privately deployable instances with external access URLs are provided to minimize deployment complexity and training overhead. For implementation details and commercial collaboration inquiries, please contact the project maintainer at [**lingy4251@163.com**](https://mailto:lingy4251@163.com/).

### **agreement**

The code of this warehouse is open source according to Apache-2.0.

---

### **acknowledgement**

Thank you to the all authors of the open source components used in the project.
[AComfyUI_AdvancedRefluxControl](https://github.com/kaibioinfo/ComfyUI_AdvancedRefluxControl)
[In-Context LoRA](https://github.com/ali-vilab/In-Context-LoRA)
[CatVTON](https://github.com/Zheng-Chong/CatVTON/)
[ViewComfy](https://github.com/ViewComfy/ViewComfy)
[comfyui_LLM_party](https://github.com/heshengtao/comfyui_LLM_party)
