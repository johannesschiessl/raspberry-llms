# raspberry-llms
Various experimenters trying to run high-parameter-count models on a Raspberry Pi 5.

# Approach

## (1) Quantization

Model quantization is a method used to shrink the size of large neural networks, such as large language models (LLMs), by reducing the precision of their weights. As the name suggests, large language models are massive, with their size determined by the number of parameters they contain. For instance, GPT-3 boasts 175 billion parameters. The precision of these parameters affects their memory footprint and, consequently, the overall size of the model. Neural networks can be stored using 16-bit or 8-bit floating-point numbers, with 8-bit floats requiring less memory. Quantization focuses on minimizing the memory requirements of LLMs while maintaining a reasonable level of accuracy and performance. 
