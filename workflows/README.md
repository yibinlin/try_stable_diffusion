# Workflow examples

1. `one_prompt_4_outputs.png`: Change the batch_size parameter in the `Empty Latent Image` node to output multiple images (in this case 4) to get multiple output images for a single prompt.
    - Reference: [u/dr_lm comment in Reddit](https://www.reddit.com/r/comfyui/comments/19eh7hm/comment/kjctlgn/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
2. `hires_fix_upload_image.png`: Upload an image, convert it to the latent space and then run latent upscaling algorithm, using Stable Diffusion V2.1 (12/2022). The results do not look very good though.
