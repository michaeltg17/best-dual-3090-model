# Best model for dual 3090

Great for coding agents like OpenCode, Cline...

Just run the docker compose. vllm will download the model and start the server.

### Extra info
You can tweak the --gpu-memory-utilization 0.91 and set it to 0.92, 0.93 on so, depending on whether you use one 3090 for screen or not.
I use one for screen so 0.91 was for me the max one I could get without vllm refusing to start.
