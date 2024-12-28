# PhysioPlay: Enhancing Clinical Skills through AI Simulation

PhysioPlay is an innovative AI-powered solution designed to help budding physiotherapists practice their diagnostic skills and logical reasoning with patient persona simulations. The application combines gamified learning, real-time feedback, and case-based scenarios to build confidence and provide hands-on exposure without real-world risks.

## Key Features
- **Interactive AI-Driven Simulations**: Real-world patient scenarios with guided diagnostic interactions.
- **Gamified Reward System**: Build motivation through performance-based rewards.
- **Affordable and Accessible**: Bridging the gap between theoretical knowledge and clinical application for students and professionals alike.
- **Multiple Physiotherapy Domains**: Including orthopedics, neurology, pediatrics, and more.

## Steps to Set Up and Run PhysioPlay

### Prerequisites
1. Install Python (3.8 or higher).
2. Install Streamlit and additional dependencies.

### Clone the Repository
```bash
$ git clone https://github.com/your-repo-link/PhysioPlay.git
$ cd PhysioPlay
```

### Setting Up the Environment
1. **Install Required Libraries**:
   ```bash
   $ pip install -r requirements.txt
   ```

2. **Prepare Case Studies**:
   - Place your PDF case studies in the `data/` directory.
   - Ensure the files are properly named and relevant.

### Running the Application

#### 1. Backend Server
- **Location**: Refer to the `BASIC_LANGCHAIN.py` file.
- **Command**:
  ```bash
  $ python BASIC_LANGCHAIN.py
  ```

#### 2. Streamlit Interface
- **Location**: Refer to the `6.py` file.
- **Command**:
  ```bash
  $ streamlit run 6.py
  ```

### Accessing the Application
1. Open your browser.
2. Visit the URL displayed in the terminal (usually `http://localhost:8501`).

## Contribution
We welcome contributions to enhance PhysioPlay further. For major changes, please open an issue first to discuss your ideas.


