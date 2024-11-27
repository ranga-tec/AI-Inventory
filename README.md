# Inventory Management System with AI Agents (Developing))

An advanced inventory management system that uses AutoGen AI agents to handle complex inventory operations through natural language interactions.

## Features

- Natural language interface for inventory operations
- Integrated AI agents for process automation
- Purchase Order management
- Goods Receipt handling
- Quality Control processes
- Stock management
- Real-time inventory tracking

## Technology Stack

- Python 3.8+
- SQL Server
- AutoGen for AI agents
- Flask for API
- PYODBC for database connectivity

## Setup

1. Create a virtual environment:
```bash
python -m venv env
```

2. Activate the virtual environment:
```bash
# Windows
.\env\Scripts\activate

# Unix/MacOS
source env/bin/activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Configure environment variables:
- Copy `.env.example` to `.env`
- Update database connection string and OpenAI API key

5. Setup database:
- Run the SQL scripts in the `database` folder
- Run test data setup if needed

## Running the Application

1. Start the server:
```bash
python app.py
```

2. For testing with terminal interface:
```bash
python test_chat.py
```

## Project Structure

```
inventory_management_system/
├── agents/                 # AI agent definitions
├── api/                   # API routes
├── core/                  # Core functionality
├── database/             # Database scripts and migrations
├── models/               # Data models
├── services/             # Business logic
├── static/               # Static files
├── templates/            # HTML templates
└── utils/                # Utility functions
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Create a new Pull Request

## License

MIT License - see LICENSE file for details