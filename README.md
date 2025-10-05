# 🍽️ Food Delivery Time Predictor# 🍽️ Food Delivery Time Predictor

A machine learning web application built with Streamlit that predicts food delivery times based on various factors such as distance, weather conditions, traffic density, and delivery person details.A machine learning web application built with Streamlit that predicts food delivery times based on various factors such as distance, weather conditions, traffic density, and delivery person details.



## 🚀 Live Demo## 🚀 Live Demo



**🌐 [Access the Live App](https://bumal-sathsara-food-delivery-time-prediction.streamlit.app/predictor)** 



## ✨ Features## ✨ Features



- **🎨 Modern UI Design**: Clean, professional interface with gradient backgrounds- **🎨 Modern UI Design**: Clean, professional interface with gradient backgrounds

- **📱 Responsive Layout**: Optimized for different screen sizes- **📱 Responsive Layout**: Optimized for different screen sizes

- **🔮 Real-time Predictions**: Get instant delivery time estimates- **🔮 Real-time Predictions**: Get instant delivery time estimates

- **📊 Multi-page Navigation**: Separate home and predictor pages- **📊 Multi-page Navigation**: Separate home and predictor pages

- **🧠 Smart Predictions**: ML model considers 11 different factors- **🧠 Smart Predictions**: ML model considers 11 different factors

- **⚡ Fast Performance**: Optimized for quick load times- **⚡ Fast Performance**: Optimized for quick load times



### Input Parameters### Input Parameters

- 📍 **Distance** (km)- 📍 **Distance** (km)

- 👤 **Delivery person** age and ratings- 👤 **Delivery person** age and ratings

- ⏰ **Order to pickup** time- ⏰ **Order to pickup** time

- 🚚 **Multiple deliveries** handled by rider- 🚚 **Multiple deliveries** handled by rider

- 🚦 **Road traffic** density (low/medium/jam)- 🚦 **Road traffic** density (low/medium/jam)

- 🌤️ **Weather conditions** (sunny/stormy/fog/windy/sandstorms)- 🌤️ **Weather conditions** (sunny/stormy/fog/windy/sandstorms)

- 🍕 **Order type** (meal/snack/drinks)- 🍕 **Order type** (meal/snack/drinks)

- 🏍️ **Vehicle type** (motorcycle/scooter)- 🏍️ **Vehicle type** (motorcycle/scooter)

- 🎉 **Festival** status (yes/no)- 🎉 **Festival** status (yes/no)

- 🏙️ **City type** (urban/semi-urban/metropolitan)- 🏙️ **City type** (urban/semi-urban/metropolitan)



## 🛠️ Installation & Setup## 🛠️ Installation & Setup



### Prerequisites### Prerequisites

- Python 3.8 or higher- Python 3.8 or higher

- pip (Python package manager)- pip (Python package manager)

- Git- Git



### Local Development Setup### Local Development Setup



1. **Clone the repository**1. **Clone the repository**

   ```bash   ```bash

   git clone https://github.com/your-username/food-delivery-time-prediction.git   git clone https://github.com/your-username/food-delivery-time-prediction.git

   cd food-delivery-time-prediction   cd food-delivery-time-prediction

   ```   ```



2. **Create a virtual environment**2. **Create a virtual environment**

   ```bash   ```bash

   python -m venv venv   python -m venv venv

   ```   ```



3. **Activate the virtual environment**3. **Activate the virtual environment**

   - **Windows (PowerShell):**   - **Windows (PowerShell):**

     ```powershell     ```powershell

     .\venv\Scripts\Activate.ps1     .\venv\Scripts\Activate.ps1

     ```     ```

   - **Windows (Command Prompt):**   - **Windows (Command Prompt):**

     ```cmd     ```cmd

     venv\Scripts\activate     venv\Scripts\activate

     ```     ```

   - **macOS/Linux:**   - **macOS/Linux:**

     ```bash     ```bash

     source venv/bin/activate     source venv/bin/activate

     ```     ```



4. **Install dependencies**4. **Install dependencies**

   ```bash   ```bash

   pip install -r requirements.txt   pip install -r requirements.txt

   ```   ```



5. **Run the application**5. **Run the application**

   ```bash   ```bash

   streamlit run app.py   streamlit run app.py

   ```   ```



6. **Open your browser** and navigate to `http://localhost:8501`6. **Open your browser** and navigate to `http://localhost:8501`



## 🚀 Deployment## 🚀 Deployment



This app is deployed on **Streamlit Community Cloud**. To deploy your own version:This app is deployed on **Streamlit Community Cloud**. To deploy your own version:



1. **Push to GitHub** (public repository required)1. **Push to GitHub** (public repository required)

2. **Visit** [share.streamlit.io](https://share.streamlit.io)2. **Visit** [share.streamlit.io](https://share.streamlit.io)

3. **Connect** your GitHub repository3. **Connect** your GitHub repository

4. **Set main file** to `app.py`4. **Set main file** to `app.py`

5. **Deploy!** 🎉5. **Deploy!** 🎉



For detailed deployment instructions, see `DEPLOYMENT.md`.For detailed deployment instructions, see `DEPLOYMENT.md`.



## 📊 Model Information## 📊 Model Information



- **Algorithm**: Random Forest Regressor- **Algorithm**: Random Forest Regressor

- **Framework**: Scikit-learn pipeline with preprocessing- **Framework**: Scikit-learn pipeline with preprocessing

- **Features**: 11 input parameters- **Features**: 11 input parameters

- **Output**: Delivery time in minutes- **Output**: Delivery time in minutes

- **Performance**: Optimized for real-world delivery scenarios- **Performance**: Optimized for real-world delivery scenarios



### Model Pipeline### Model Pipeline

- **Preprocessing**: Feature scaling and encoding for categorical variables- **Preprocessing**: Feature scaling and encoding for categorical variables

- **Training**: Trained on historical delivery data- **Training**: Trained on historical delivery data

- **Validation**: Cross-validated for robust performance- **Validation**: Cross-validated for robust performance



## 🗂️ Project Structure## 🗂️ Project Structure



``````

food-delivery-time-prediction/food-delivery-time-prediction/

││

├── 📄 app.py                    # Main Streamlit application (Homepage)├── 📄 app.py                    # Main Streamlit application (Homepage)

├── 📁 pages/                    # Streamlit pages directory├── 📁 pages/                    # Streamlit pages directory

│   └── 📄 predictor.py          # Prediction page with ML model│   └── 📄 predictor.py          # Prediction page with ML model

├── 📁 images/                   # Static images├── 📁 images/                   # Static images

│   └── 🖼️ food_delivery.jpg     # Hero image for homepage│   └── 🖼️ food_delivery.jpg     # Hero image for homepage

├── 🤖 rf_pipeline.pkl           # Pre-trained Random Forest model├── 🤖 rf_pipeline.pkl           # Pre-trained Random Forest model

├── 📋 requirements.txt          # Python dependencies├── 📋 requirements.txt          # Python dependencies

├── 📖 README.md                 # Project documentation (this file)├── 📖 README.md                 # Project documentation (this file)

├── 🚀 DEPLOYMENT.md             # Deployment instructions├── 🚀 DEPLOYMENT.md             # Deployment instructions

├── 🙈 .gitignore               # Git ignore rules├── 🙈 .gitignore               # Git ignore rules

├── 📁 .git/                    # Git repository data├── 📁 .git/                    # Git repository data

├── 📁 .qodo/                   # Qodo configuration├── 📁 .qodo/                   # Qodo configuration

└── 📁 venv/                    # Virtual environment (local only)└── 📁 venv/                    # Virtual environment (local only)

``````



## 🔧 Troubleshooting## 🔧 Troubleshooting



### Common Issues### Common Issues



#### Scikit-learn Version Mismatch#### Scikit-learn Version Mismatch

```bash```bash

# Solution: Use exact versions# Solution: Use exact versions

pip install scikit-learn==1.6.1 joblib==1.5.2pip install scikit-learn==1.6.1 joblib==1.5.2

``````



#### Model Loading Errors#### Model Loading Errors

- Ensure `rf_pipeline.pkl` is in the root directory- Ensure `rf_pipeline.pkl` is in the root directory

- Check file permissions and integrity- Check file permissions and integrity

- Verify all dependencies are installed- Verify all dependencies are installed



#### Streamlit Navigation Issues#### Streamlit Navigation Issues

- Ensure `pages/` directory structure is correct- Ensure `pages/` directory structure is correct

- Verify `predictor.py` is in the `pages/` folder- Verify `predictor.py` is in the `pages/` folder

- Check that `st.switch_page()` paths are correct- Check that `st.switch_page()` paths are correct



#### Virtual Environment Issues#### Virtual Environment Issues

```bash```bash

# Deactivate and recreate if needed# Deactivate and recreate if needed

deactivatedeactivate

rm -rf venv  # or rmdir /s venv on Windowsrm -rf venv  # or rmdir /s venv on Windows

python -m venv venvpython -m venv venv

``````



## 🤝 Contributing## 🤝 Contributing



1. **Fork** the repository1. **Fork** the repository

2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)

3. **Commit** your changes (`git commit -m 'Add amazing feature'`)3. **Commit** your changes (`git commit -m 'Add amazing feature'`)

4. **Push** to the branch (`git push origin feature/amazing-feature`)4. **Push** to the branch (`git push origin feature/amazing-feature`)

5. **Open** a Pull Request5. **Open** a Pull Request



## 📄 License## 📄 License



This project is open source and available under the [MIT License](LICENSE).This project is open source and available under the [MIT License](LICENSE).



## 🙏 Acknowledgments## 🙏 Acknowledgments



- **Streamlit** for the amazing web app framework- **Streamlit** for the amazing web app framework

- **Scikit-learn** for machine learning capabilities- **Scikit-learn** for machine learning capabilities

- **Python community** for the excellent ecosystem- **Python community** for the excellent ecosystem



## 📞 Contact## 📞 Contact



**Project Link**: https://github.com/Bumal-Sathsara/food-delivery-time-prediction



**Live Demo**: https://bumal-sathsara-food-delivery-time-prediction.streamlit.app/predictor



------



⭐ **Star this repository** if you found it helpful!⭐ **Star this repository** if you found it helpful!