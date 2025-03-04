# Local AI Assistant Structure

├── .env.example             # Environment template
├── requirements.txt         # Python dependencies
├── local_assistant.py       # Main application
├── config/
│   ├── context_rules.yaml   # Custom response guidelines
│   └── models.yaml          # Configured Ollama models
├── memory/
│   └── chat_history.json    # Conversation storage
├── tests/
│   ├── test_basic.py        # Core functionality tests
│   └── test_memory.py       # Memory persistence tests
└── docs/
    └── SETUP.md             # Installation instructions
