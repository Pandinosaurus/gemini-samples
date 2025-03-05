# Google DeepMind Models Samples, Snippets and Guides

This repository contains personal tiny samples, snippets and guides showcasing cool experiments and implementations using Google DeepMind Gemini models.

## Examples

- [Gemini with OpenAI SDK](examples/gemini-with-openai-sdk.ipynb) - Use Gemini models with the OpenAI SDK
- [Gemini with Google Search](examples/gemini-google-search.ipynb) - Enable Google Search integration for up-to-date information
- [Structured Outputs](examples/gemini-structured-outputs.ipynb) - Generate structured JSON outputs using Pydantic
- [Meta Prompts](examples/gemini-meta-prompt-structured-outputs.ipynb) - Generate JSON schemas dynamically using meta prompts
- [Audio Transcription](examples/gemini-transcribe-with-timestamps.ipynb) - Transcribe audio with precise timestamps
- [Function Calling Guide](guide/function-calling.ipynb) - Comprehensive guide on implementing function calling

## Repository Structure
```
├── examples/
│   └── gemini-with-openai-sdk.ipynb
├── guides/
│   └── function-calling.ipynb
├── LICENSE
└── README.md
```

## How to Use

1. **Clone the repository:**
    ```bash
    git clone https://github.com/philschmid/gemini-samples.git
    ```

2. **Set up environment variables:**
   Create a `.env` file in the root directory:
   ```
   GEMINI_API_KEY=your_api_key_here
   ```

3. **Explore the examples:** Browse the sample notebooks to find code related to different DeepMind models and experiments.

4. **Run and modify:** Experiment with the code, tweak parameters, and integrate the snippets into your own projects.

## Contributing

Contributions are welcome! If you have additional examples or improvements, please feel free to open a pull request or create an issue.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.