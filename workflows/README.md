# Workflow examples

1. `one_prompt_4_outputs.png`: Change the batch_size parameter in the `Empty Latent Image` node to output multiple images (in this case 4) to get multiple output images for a single prompt.
    - Reference: [u/dr_lm comment in Reddit](https://www.reddit.com/r/comfyui/comments/19eh7hm/comment/kjctlgn/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
2. `hires_fix_upload_image.png`: Upload an image, convert it to the latent space and then run latent upscaling algorithm, using Stable Diffusion V2.1 (12/2022). The results do not look very good though.
3. `inpainting_set_latent_noise_mask.png`: Inpainting with small modifications - only for testing.
    - Reference: [Youtube](https://www.youtube.com/watch?v=g9JXx4ik_rc)
    - Also good for non-inpainting models, such as the SDXL base model. [Reference](https://www.reddit.com/r/comfyui/comments/16uqvfe/how_do_i_change_the_masked_area_more_than_with/)
    - The source code [link](https://github.com/comfyanonymous/ComfyUI/blob/d7897fff2cfd38eac051fbc958a6f944bdf68cc9/nodes.py#L1309).
