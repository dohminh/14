# Web Application

A modern web application built with Python and Docker.

## Features

- Python-based web application
- Docker containerization
- Database migrations support
- Virtual environment setup

## Prerequisites

- Python 3.x
- Docker and Docker Compose
- Git

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd webapp15
```

2. Set up virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

### Using Docker

1. Build and start the containers:
```bash
docker-compose up --build
```

2. The application will be available at `http://localhost:5000`

### Running Locally

1. Activate the virtual environment:
```bash
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

2. Run the application:
```bash
python main.py
```

## Project Structure

```
webapp15/
├── app/            # Application code
├── migrations/     # Database migrations
├── instance/       # Instance-specific files
├── .venv/          # Virtual environment
├── main.py         # Application entry point
├── Dockerfile      # Docker configuration
├── docker-compose.yml  # Docker Compose configuration
└── requirements.txt    # Python dependencies
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
