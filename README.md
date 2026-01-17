# 🧠 DSA Problem Explainer Bot

An AI-powered web application that explains Data Structures & Algorithms problems in simple, easy-to-understand language. Built with Python, Streamlit, and powered by Google Gemini and Groq APIs.

## 🌟 Features

- **AI-Powered Explanations**: Get detailed breakdowns of any DSA problem
- **Multiple AI Models**: Choose between Google Gemini and Groq (Llama 3.3)
- **Simple Interface**: Clean, intuitive UI built with Streamlit
- **Pre-loaded Examples**: Quick start with common DSA problems
- **Comprehensive Analysis**: Includes approach, complexity, examples, and tips
- **100% Free**: No credit card required for API access

## 🎯 What You Get

For each problem, the bot provides:
1. **Problem Summary** - Simple overview in plain English
2. **Key Concepts** - Data structures and algorithms involved
3. **Approach** - Step-by-step solution strategy
4. **Time & Space Complexity** - Big O notation with explanations
5. **Example Walkthrough** - Concrete example with solution
6. **Tips** - Common pitfalls and edge cases to watch for

## 📋 Prerequisites

- Python 3.8 or higher
- pip (Python package manager)
- A free API key from either:
  - [Google AI Studio](https://aistudio.google.com/app/apikey) (Gemini)
  - [Groq Console](https://console.groq.com) (Recommended - faster!)

## 🛠️ Installation

1. **Install required packages**
```bash
pip install streamlit google-generativeai groq
```

2. **Get your FREE API key**
   - **Option 1 (Groq - Recommended)**: 
     - Visit [Groq Console](https://console.groq.com)
     - Sign up and create an API key
   - **Option 2 (Google Gemini)**:
     - Visit [Google AI Studio](https://aistudio.google.com/app/apikey)
     - Sign in and generate an API key

3. **Run the application**
```bash
streamlit run dsa.py
```

4. **Open in browser**
   - The app will automatically open at `http://localhost:8501`
   - Enter your API key in the sidebar
   - Start explaining DSA problems!

## 💻 Usage

1. **Select API Provider**: Choose between Gemini or Groq
2. **Enter API Key**: Paste your free API key in the sidebar
3. **Choose a Problem**: Select from examples or paste your own
4. **Get Explanation**: Click "Explain Problem" and receive detailed analysis
5. **Learn**: Read through the structured explanation

### Example Problems Included

- Two Sum
- Reverse Linked List
- Valid Parentheses
- Binary Search
- Merge Two Sorted Lists
- Maximum Subarray

## 🏗️ Project Structure

```
dsa-problem-explainer/
│
├── dsa.py                  # Main application file
├── README.md              # Project documentation
└── .gitignore             # Git ignore file
```

## 📦 Dependencies

```
streamlit>=1.28.0
google-generativeai>=0.3.0
groq>=0.4.0
```

## 🔑 API Keys Setup

### Groq (Recommended)
- **Free Tier**: 30 requests/min
- **Speed**: Fastest inference
- **Get Key**: [console.groq.com](https://console.groq.com)

### Google Gemini
- **Free Tier**: 60 requests/min, 1500/day
- **Models**: Multiple Gemini versions
- **Get Key**: [aistudio.google.com](https://aistudio.google.com/app/apikey)

## 🎨 Tech Stack

- **Frontend**: Streamlit
- **AI Models**: 
  - Google Gemini (1.5 Flash/Pro)
  - Groq (Llama 3.3 70B)
- **Language**: Python 3.8+
- **APIs**: Google Generative AI, Groq

## 🐛 Known Issues

- Encoding issues on some Windows systems (use UTF-8 encoding)
- API rate limits on free tiers (switch models if needed)

## 🙏 Acknowledgments

- [Streamlit](https://streamlit.io/) for the amazing web framework
- [Google](https://ai.google.dev/) for Gemini API
- [Groq](https://groq.com/) for lightning-fast inference

