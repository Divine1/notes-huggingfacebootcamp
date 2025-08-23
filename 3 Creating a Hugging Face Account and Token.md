
https://huggingface.co/docs/hub/en/index

https://huggingface.co/docs/hub/en/repositories-next-steps


```
# Make sure hf CLI is installed: pip install -U "huggingface_hub[cli]"
hf download cdivine304/example-model

pip install huggingface_hub

huggingface-cli login
huggingface-cli repo create repo_name --type {model, dataset, space}
```

```
git lfs install
git clone https://huggingface.co/cdivine304/example-model
# If you want to clone without large files - just their pointers
GIT_LFS_SKIP_SMUDGE=1 git clone https://huggingface.co/cdivine304/example-model
```

```
install jupyter lab in laptop.
command: pip install jupyterlab

open jupyter lab in browser
command: jupyter lab

git remote set-url origin https://cdivine304:@huggingface.co/cdivine304/example-model


```
<img width="956" height="466" alt="image" src="https://github.com/user-attachments/assets/59c7f0e0-3b88-4628-b2f9-e8bd14a74f57" />

models over 100MB in size will not work with git. 

<img width="1026" height="571" alt="image" src="https://github.com/user-attachments/assets/601248b0-2fc8-48f2-b268-7555d1137576" />


safe tensors are formats in which neural networks are saved
<img width="714" height="41" alt="image" src="https://github.com/user-attachments/assets/31f63449-5bfc-42ee-90ef-fd0fcbc9e176" />


