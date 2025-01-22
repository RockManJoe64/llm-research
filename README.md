# llm-research

Collection of Jupyter notebooks where I investigate playing around with local LLMs

## Running on MacOS

When running the `ollama-llama3.2.ipnyb` notebook, do the following to setup your environment.

1. Ensure you have installed the latest version of Python 3. You can install via homebrew

```bash
brew install python
```

2. Clone this repo and navigate to the directory
3. Create a python virtualenv and install the necessary lang-chain modules

```bash
python3 -m venv venv
source venv/bin/activate
pip3 -v install langchain langchain-community langchain-ollama ollama --quiet
```

4. Install and run Jupyter lab

```bash
pip3 -v install jupyterlab
jupyter lab
```

5. Execute the notebook in Jupyter! Expected output:

```
The sky appears blue because of a phenomenon called Rayleigh scattering, named after the British physicist Lord Rayleigh, who first described it in the late 19th century.

Here's what happens:

1. **Sunlight enters Earth's atmosphere**: When sunlight enters our atmosphere, it encounters tiny molecules of gases such as nitrogen (N2) and oxygen (O2).
2. **Scattering occurs**: These gas molecules scatter the light in all directions, but they scatter shorter (blue) wavelengths more than longer (red) wavelengths.
3. **Blue light is scattered**: The blue light is dispersed throughout the atmosphere, reaching our eyes from all directions.
4. **Our eyes perceive the color**: When we look up at a clear sky on a sunny day, our eyes detect the scattered blue light and interpret it as the color blue.

Other factors can affect the appearance of the sky, such as:

* **Atmospheric conditions**: Dust, pollution, and water vapor in the air can scatter light differently, changing the apparent color of the sky.
* **Time of day**: The sun's position in the sky affects the amount of direct sunlight that reaches our eyes, which can alter the appearance of the sky.
* **Weather conditions**: Clouds, fog, or haze can reduce the intensity of the blue light and change the sky's color.

So, to summarize, the sky appears blue because of Rayleigh scattering, where shorter (blue) wavelengths of light are scattered by gas molecules in the atmosphere, reaching our eyes from all directions.
```

