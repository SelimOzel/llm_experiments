# llm_experiments

Models here [1] are important as they are generated to accomodate latest changes in llama.cpp. To use simply do the following:
```
git clone llama.cpp
Download model. Copy paste under models.
cd llama.cpp
make
./main -m models/Wizard-Vicuna-7B-Uncensored.ggmlv3.q5_0.bin --color -c 2048 --temp 0.7 --repeat_penalty 1.1 -n -1 -p "Write a Skyrim book for my bro. Make sure its contents are similar to books written in the game Skyrim."
```

[1](https://huggingface.co/TheBloke/Wizard-Vicuna-7B-Uncensored-GGML)
