virtual-world/
|--src/
| |--apis/
| | |--openai/
| | | |--index.ts # Functions for interacting with the OpenAI API
| | | |--gpt3.ts # GPT-3 specific interactions
| | |--chroma/
| | | |--index.ts # Functions for interacting with the Chroma database
| | | |--memory.ts # Functions for managing memory in Chroma
| |--core/
| | |--world/
| | | |--index.ts # Core world functions (e.g., validation, state updates)
| | | |--stateManager.ts # Managing world state
| | | |--actionHandler.ts # Handle and validate user actions
| | | |--responseGenerator.ts # Generating responses using GPT-3
| | |--server/
| | | |--index.ts # Server initialization and setup
| | | |--socketHandler.ts # Managing socket connections for real-time communication
| | |--user/
| | | |--index.ts # User-related functions
| | | |--userManager.ts # Handling user sessions, turns, etc.
| |--config/
| | |--index.ts # Configuration for the server, APIs, etc.
| |--utils/
| | |--index.ts # General utility functions
| |--index.ts # Entry point for the application
|--tests/
| |--unit/
| | |--... # Unit tests
| |--integration/
| | |--... # Integration tests
|--docs/
| |--SPEC.md # Detailed spec for connecting to and interacting with the server
| |--API_DOCUMENTATION.md # API Documentation
|--package.json
|--tsconfig.json
|--README.md
|--.gitignore
