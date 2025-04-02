# Mach

## Installation

### Prerequisites

1. Install Python 3.12 or higher
2. Install `uv` (a fast Python package installer):

```bash
# On macOS using Homebrew
brew install uv

# On Linux/WSL using pip
pip install uv
```

### Setting up the Project

1. Clone the repository:
```bash
git clone git@github.com:RaoFoundation/mach.git
cd mach
```

2. Create a virtual environment using Python 3.12:
```bash
uv venv -p python3.12
```

3. Activate the virtual environment:
```bash
# On macOS/Linux
source .venv/bin/activate

# On Windows
.venv\Scripts\activate
```

4. Install dependencies using uv:
```bash
uv pip install -r requirements.txt
```

### Verifying Installation

After installation, you can verify that everything is working correctly by running:
```bash
python -c "import bittensor; import requests; print('Installation successful!')"
```

## Usage

Run the main application:
```bash
python mach/hello.py