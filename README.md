Expects you to have an api key from Google AI Studio

```
export GEMINI_API_KEY=<your_api_key>
```

## Usage

```
gptscript --default-model='gemini-pro from github.com/drpebcak/gemini-proxy' examples/bob.gpt
```

## Development

Run using the following commands

```
python -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
./run.sh
```

```
export OPENAI_BASE_URL=http://127.0.0.1:8000/v1
gptscript --default-model=gemini-pro examples/bob.gpt
```