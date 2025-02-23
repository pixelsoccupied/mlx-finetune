# mlx-finetune
Finetune on Apple Silicon


## Reference
- [LORA cli](https://github.com/ml-explore/mlx-examples/blob/main/llms/mlx_lm/LORA.md
)

## Run
```shell
 mlx_lm.lora --train --model mistralai/Mistral-7B-Instruct-v0.3 --iters 100 -c lora-config.yaml --test
```