# GPT2

this is me learning GPT2 from Karpathy with lots of comments just to make sure I don't forget

we're implementing the 124M parameter model with 12 layers and 768 dimensions.

we'll refer the [GPT3 paper](https://arxiv.org/abs/2005.14165) as it has more details than the [GPT2 paper](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf).

let's start with loading the [gpt-2](https://github.com/openai/gpt-2) weights and try to sample some tokens from it.

the original code gpt-2 code is written in tensorflow and we want to use pytorch for obvious reasons :P

so to load these weights we can use huggingface transformers [openai-community/gpt2](https://huggingface.co/openai-community/gpt2) implementation.

but we need to write our own GPT2 class from scratch so that we understand the details.



