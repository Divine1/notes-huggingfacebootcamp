



# executable code of simple text to image model
```
!pip install huggingface_hub==0.25.2
!pip install transformers==4.30.0 diffusers==0.27.0
from diffusers import AutoPipelineForText2Image
import torch
pipeline = AutoPipelineForText2Image.from_pretrained("dreamlike-art/dreamlike-photoreal-2.0",
                                            torch_dtype=torch.float16, use_safetensors=True).to("cuda")
prompt = "cinematic photo of big bird in paris, 35mm photo, film"
image = pipeline(prompt).images[0]
image
```


