# llama-32-from-scratch

environment for the project https://huggingface.co/rasbt/llama-3.2-from-scratch

refer to the [main application](src/generate_example.py) for the source code

# installation

```shell
# create conda environment
make env-init

# install dependencies
make env-create
```

# run

```shell
# run src/generate_example.py
make run
```

or

```shell
# run Bash with-in conda environment
make env-shell

# run the program
python generate_example.py
```
