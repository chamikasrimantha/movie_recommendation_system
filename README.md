# Movie Recommendation System using h2o wave

The Movie Recommendation System is an application designed to suggest movies to users based on their preferences and viewing history. It employs collaborative filtering techniques to analyze user behavior and generate personalized recommendations.

https://github.com/chamikasrimantha/h2o-wave-app/assets/137622812/acbc43b7-36f5-4859-ae62-0b22b06ed096


## Getting Started

### 1. Check the version of Python, must be Python 3.9+ but recommended to use Python 3.10+ for best experience
``` bash
python3 --version
```

### 2. Clone the repository
``` bash
git clone https://github.com/chamikasrimantha/h2o-wave-app.git
```

### 3. Create a virtual environment
``` bash
python3 -m venv venv
```

### 4. Activate the virtual environment
**Unix/ MacOS**
``` bash
source venv/bin/activate
```

**Windows**
``` bash
.\venv\Scripts\activate
```

### 5. Install the packages
``` bash
python3 -m pip install -U pip
python3 -m pip install -r requirements.txt
```

### 6. Run the application
``` bash
wave run app
```

### 7. View the app:
Point your favorite web browser to http://localhost:10101/

### Testing
Tests are located in ```test.py```. See instructions on [h2o wave docs](https://wave.h2o.ai/docs/browser-testing) to configure tests.

### Others

[h2o wave documentation](https://wave.h2o.ai/docs/getting-started)
