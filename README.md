# ponder-bot
A stateful conversational AI agent utilizing advanced reasoning and dynamic token-budgeted thinking mechanics.

PonderBot is a stateful conversational AI agent built with Python. Leveraging the advanced reasoning and explicit "thinking" capabilities of modern large language models, PonderBot maps out logical steps, evaluates complex reasoning problems, and tracks conversation history seamlessly within a lightweight terminal interface.

Key Engineering Features:

1.Explicit Reasoning (Thinking Mode)**: Configured to manage a token budget for internal reasoning steps, pulling the model's intermediate thoughts alongside final responses. 
2.Stateful Session Memory**: Utilizes low-level SDK chat utilities to maintain complete contextual memory across user turns without manual prompt appending.
3.Production-Ready Security**: Engineered to abstract API credentials strictly through system environment variables, preventing accidental leakages in version control.


 Technical Architecture:
Language: Python 3.10+
Primary SDK: Official Google GenAI Python Library (google-genai)
API Infrastructure: Powered by Gemini 2.5 architecture via Google AI Studio
