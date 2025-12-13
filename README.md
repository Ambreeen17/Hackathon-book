# Physical AI & Humanoid Robotics — Essentials

A concise textbook with integrated AI assistance for learning Physical AI and Humanoid Robotics concepts.

## Overview

This project provides a comprehensive yet concise educational resource for Physical AI and Humanoid Robotics. It includes:

- 6 focused chapters covering core concepts
- Interactive AI assistance through RAG (Retrieval Augmented Generation)
- Modern Docusaurus-based UI
- Complete capstone project integrating all concepts

## Chapters

1. [Introduction to Physical AI](./docs/intro.md)
2. [Basics of Humanoid Robotics](./docs/humanoid-basics.md)
3. [ROS 2 Fundamentals](./docs/ros2-fundamentals.md)
4. [Digital Twin Simulation (Gazebo + Isaac)](./docs/digital-twin.md)
5. [Vision-Language-Action Systems](./docs/vision-language-action.md)
6. [Capstone: Simple AI-Robot Pipeline](./docs/capstone.md)

## Features

- **AI Integration**: Built-in RAG chatbot that answers questions based only on book content
- **Interactive Elements**: "Select text → Ask AI" functionality
- **Multi-language Support**: English and Urdu translation
- **Modern UI**: Clean, fast Docusaurus interface
- **Lightweight**: Designed for free-tier service compatibility
- **Production Ready**: Clean architecture and safety considerations

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Python 3.8+ (for backend services)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/physical-ai-humanoid-robotics.git
cd physical-ai-humanoid-robotics
```

2. Install Docusaurus dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser to [http://localhost:3000](http://localhost:3000) to view the textbook.

### Backend Services (Optional)

For full AI functionality, you'll need to set up the backend services:

1. Install Python dependencies:
```bash
pip install fastapi uvicorn qdrant-client python-multipart
```

2. Start the FastAPI server:
```bash
uvicorn backend.main:app --reload
```

## Project Structure

```
├── docs/                   # Textbook content
│   ├── intro.md           # Introduction to Physical AI
│   ├── humanoid-basics.md # Basics of Humanoid Robotics
│   ├── ros2-fundamentals.md # ROS 2 Fundamentals
│   ├── digital-twin.md    # Digital Twin Simulation
│   ├── vision-language-action.md # Vision-Language-Action Systems
│   └── capstone.md        # Capstone: Simple AI-Robot Pipeline
├── src/                   # Docusaurus source files
│   ├── components/        # Custom React components
│   ├── css/              # Custom styles
│   └── pages/            # Additional pages
├── static/               # Static assets
├── docusaurus.config.js  # Docusaurus configuration
├── sidebars.js           # Navigation sidebars
└── README.md             # This file
```

## AI Integration

The textbook includes an integrated RAG (Retrieval Augmented Generation) system that allows you to:

- Select text in the textbook and ask AI questions about it
- Get explanations based only on the textbook content
- Receive accurate, context-aware responses

The RAG system is built with:
- Qdrant for vector storage
- FastAPI for backend services
- Neon for database storage

## Contributing

We welcome contributions to improve the textbook content and functionality:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Docusaurus](https://docusaurus.io/)
- AI integration powered by modern RAG techniques
- Inspired by advances in Physical AI and Humanoid Robotics research

## Support

For support, please open an issue in the GitHub repository.# Hackathon-book
# Physical-AI-Humanoid-Robotics-Textbook
