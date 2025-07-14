# THUDM/cogvlm2-llama3-caption

HuggingFace model: THUDM/cogvlm2-llama3-caption

This is a mirror of the [THUDM/cogvlm2-llama3-caption](https://huggingface.co/THUDM/cogvlm2-llama3-caption) repository from HuggingFace.

**Note**: This repository contains metadata and configuration files only. The actual model files are stored on HuggingFace due to their large size.

## Model Information

### Architecture

- **Architecture**: CogVLMVideoForCausalLM
- **Vocabulary Size**: 128,256
- **Hidden Size**: 4,096
- **Number of Layers**: 32
- **Attention Heads**: 32

### Model Files

This repository contains metadata about the model files. The actual model files are stored on HuggingFace.

| File | Size | Details |
|------|------|---------|
| [model-00001-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00001-of-00006.safetensors) | 4GB | 74 tensors |
| [model-00002-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00002-of-00006.safetensors) | 4GB | 91 tensors |
| [model-00003-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00003-of-00006.safetensors) | 4GB | 89 tensors |
| [model-00004-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00004-of-00006.safetensors) | 4GB | 438 tensors |
| [model-00005-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00005-of-00006.safetensors) | 3GB | 336 tensors |
| [model-00006-of-00006.safetensors](https://huggingface.co/THUDM/cogvlm2-llama3-caption/blob/main/model-00006-of-00006.safetensors) | 1002MB | 1 tensors |

**Total files**: 6

### Tensor Details

Sample tensors from safetensors files:

**model-00001-of-00006.safetensors**:
    - model.embed_tokens.weight: shape=[128256,4096], dtype=BF16
    - model.layers.0.input_layernorm.weight: shape=[4096], dtype=BF16
    - model.layers.0.mlp.language_mlp.down_proj.weight: shape=[4096,14336], dtype=BF16
    - model.layers.0.mlp.language_mlp.gate_proj.weight: shape=[14336,4096], dtype=BF16
    - model.layers.0.mlp.language_mlp.up_proj.weight: shape=[14336,4096], dtype=BF16

**model-00002-of-00006.safetensors**:
    - model.layers.10.input_layernorm.weight: shape=[4096], dtype=BF16
    - model.layers.10.mlp.language_mlp.down_proj.weight: shape=[4096,14336], dtype=BF16
    - model.layers.10.mlp.language_mlp.gate_proj.weight: shape=[14336,4096], dtype=BF16
    - model.layers.10.mlp.language_mlp.up_proj.weight: shape=[14336,4096], dtype=BF16
    - model.layers.10.post_attention_layernorm.weight: shape=[4096], dtype=BF16

**model-00003-of-00006.safetensors**:
    - model.layers.20.input_layernorm.weight: shape=[4096], dtype=BF16
    - model.layers.20.mlp.language_mlp.down_proj.weight: shape=[4096,14336], dtype=BF16
    - model.layers.20.mlp.language_mlp.up_proj.weight: shape=[14336,4096], dtype=BF16
    - model.layers.20.post_attention_layernorm.weight: shape=[4096], dtype=BF16
    - model.layers.21.input_layernorm.weight: shape=[4096], dtype=BF16

**model-00004-of-00006.safetensors**:
    - model.layers.31.input_layernorm.weight: shape=[4096], dtype=BF16
    - model.layers.31.mlp.language_mlp.down_proj.weight: shape=[4096,14336], dtype=BF16
    - model.layers.31.post_attention_layernorm.weight: shape=[4096], dtype=BF16
    - model.norm.weight: shape=[4096], dtype=BF16
    - model.vision.boi: shape=[1,1,4096], dtype=BF16

**model-00005-of-00006.safetensors**:
    - model.vision.conv.bias: shape=[1792], dtype=BF16
    - model.vision.conv.weight: shape=[1792,1792,2,2], dtype=BF16
    - model.vision.linear_proj.dense_4h_to_h.weight: shape=[4096,14336], dtype=BF16
    - model.vision.linear_proj.dense_h_to_4h.weight: shape=[14336,4096], dtype=BF16
    - model.vision.linear_proj.gate_proj.weight: shape=[14336,4096], dtype=BF16

**model-00006-of-00006.safetensors**:
    - lm_head.weight: shape=[128256,4096], dtype=BF16

## Usage

To use this model, visit the original HuggingFace repository:
- [THUDM/cogvlm2-llama3-caption](https://huggingface.co/THUDM/cogvlm2-llama3-caption)

## Additional Information

This mirror was created to provide easy access to model metadata and configuration files. For the actual model weights and full functionality, please visit the original repository on HuggingFace.

**Generated**: 2025-07-14
