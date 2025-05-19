# ULD-Distillation Framework

This repository combines two complementary approaches to LLM model distillation:
- [`llm-recipes`](https://github.com/Nicolas-BZRD/llm-recipes) - Provides model distillation methodology
- [`llm-distillation`](https://github.com/Nicolas-BZRD/llm-distillation) - Offers training dataset acquisition techniques

## Project Structure
model-distillation/
├── llm-recipes/ # Original distillation implementation
├── llm-distillation/ # Original dataset acquisition code
├── merged_examples/ # (Optional) Combined usage examples
└── README.md # This documentation


## About the Components

### llm-recipes
Contains implementations of knowledge distillation techniques for large language models, including:
- Model compression methods
- Teacher-student architectures
- Distillation loss functions

### llm-distillation
Provides tools for acquiring and processing datasets suitable for distillation training:
- Dataset collection pipelines
- Preprocessing utilities
- Quality evaluation metrics

## Usage Recommendation

For optimal results:
1. First use `llm-distillation` to acquire and prepare your training data
2. Then apply distillation techniques from `llm-recipes` using the prepared datasets

## Acknowledgments

This project builds upon the work of:
- Nicolas-BZRD's original [`llm-recipes`](https://github.com/Nicolas-BZRD/llm-recipes)
- Nicolas-BZRD's original [`llm-distillation`](https://github.com/Nicolas-BZRD/llm-distillation)

## License

Please refer to the original licenses in each subdirectory before using this combined work.
