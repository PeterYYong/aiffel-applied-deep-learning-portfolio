# GPT-Style Language Modeling on Movie Dialogue

> **Category:** AIFFEL training project  
> **Curriculum unit:** AIFFEL Research Program / MainQuest / Quest01  
> **Artifact:** [`gpt-style-dialogue-language-model.ipynb`](gpt-style-dialogue-language-model.ipynb)

## Project scope

This notebook explores decoder-only Transformer language modeling with the Cornell Movie-Dialogs Corpus. It loads up to 50,000 dialogue pairs, applies English-text cleaning and subword tokenization, and retains 42,376 sequences after length filtering.

The implementation covers positional encoding, scaled dot-product attention, multi-head attention, causal masking, a 12-layer GPT-style decoder, masked language-model loss, checkpointing, and temperature-based token sampling. Stored outputs show an executed training run and example generations.

## Verified status

- The notebook contains an implemented and substantially executed educational workflow.
- The planned 50-epoch run was interrupted at approximately epoch 17; one additional epoch was subsequently run.
- The model is implemented from scratch in TensorFlow and is **GPT-style**; it is not a pretrained GPT model.

## Limitations

- **Prompt-conditioning defect:** `decoder_inference(sentence)` preprocesses the supplied sentence but does not use it to initialize or condition generation. Output starts from the start token alone. The stored artifact is therefore not a functioning prompt-conditioned chatbot.
- The generated samples are visibly incoherent, and no held-out perplexity, BLEU, or human evaluation is provided.
- The training pipeline uses shifted answer sequences rather than learning an explicit question-to-answer mapping.
- The original README did not identify the coder or reviewer; authorship and peer-review provenance are not independently verified here.
- This repository documents coursework, not a production-ready language system or independent research result.
