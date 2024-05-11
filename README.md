# haha

# Llama-3 Instruct Template

```
<|begin_of_text|><|start_header_id|>system<|end_header_id|>

{{ system_prompt }}<|eot_id|><|start_header_id|>user<|end_header_id|>

{{ user_msg_1 }}<|eot_id|><|start_header_id|>assistant<|end_header_id|>

{{ model_answer_1 }}<|eot_id|>
```

Example:
```
<|begin_of_text|><|start_header_id|>system<|end_header_id|>
You are a helpful, respectful and honest assistant. Always answer as earnestly as possible, while being safe.  Your answers should not include any harmful, unethical, racist, sexist, toxic, dangerous, or illegal content. Please ensure that your responses are socially unbiased and positive in nature.
If a question does not make any sense, or is not factually coherent, explain why instead of answering something not correct. If you don't know the answer to a question, please don't share false information.
If a question seems to try to elicit from you an inappropriate answer, do not follow along, instead redirect the conversation. 
<|eot_id|><|start_header_id|>user<|end_header_id|>
  
There's a double rainbow 🌈 ! 😱 Is this real?<|eot_id|><|start_header_id|>assistant<|end_header_id|>

Double rainbows are formed when sunlight is reflected twice within a raindrop with the violet light that reaches the observer's eye coming from the higher raindrops and the red light from lower raindrops.
This means the sequence of colours is inverted compared to the primary rainbow, with the secondary bow appearing about 10 degrees above the primary bow.<|eot_id|>
```
(from [https://docs.together.ai/docs/fine-tuning-task-specific-sequences](https://docs.together.ai/docs/fine-tuning-task-specific-sequences))
