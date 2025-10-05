# 🍽️ Food Delivery Time Predictor

A machine learning web application built with Streamlit that predicts food delivery times based on various factors such as distance, weather conditions, traffic density, and delivery person details.

## 🚀 Live Demo

**🌐 [Access the Live App](https://bumal-sathsara-food-delivery-time-prediction.streamlit.app/predictor)**

## Video link : https://mysliit-my.sharepoint.com/:v:/g/personal/it22072238_my_sliit_lk/Eb2rTSVhMqVPttM-dJwCFGIBG7cw__3ClDAUX8NGUXSVrg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=be7r4n

## ✨ Features

- **🎨 Modern UI Design**: Clean, professional interface with gradient backgrounds
- **📱 Responsive Layout**: Optimized for different screen sizes
- **🔮 Real-time Predictions**: Get instant delivery time estimates
- **📊 Multi-page Navigation**: Separate home and predictor pages
- **🧠 Smart Predictions**: ML model considers 11 different factors
- **⚡ Fast Performance**: Optimized for quick load times

### Input Parameters
- 📍 **Distance** (km)
- 👤 **Delivery person** age and ratings
- ⏰ **Order to pickup** time
- 🚚 **Multiple deliveries** handled by rider
- 🚦 **Road traffic** density (low/medium/jam)
- 🌤️ **Weather conditions** (sunny/stormy/fog/windy/sandstorms)
- 🍕 **Order type** (meal/snack/drinks)
- 🏍️ **Vehicle type** (motorcycle/scooter)
- 🎉 **Festival** status (yes/no)
- 🏙️ **City type** (urban/semi-urban/metropolitan)

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)
- Git

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Bumal-Sathsara/food-delivery-time-prediction.git
   cd food-delivery-time-prediction
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   ```

3. **Activate the virtual environment**
   - **Windows (PowerShell):**
     ```powershell
     .\venv\Scripts\Activate.ps1
     ```
   - **Windows (Command Prompt):**
     ```cmd
     venv\Scripts\activate
     ```
   - **macOS/Linux:**
     ```bash
     source venv/bin/activate
     ```

4. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application**
   ```bash
   streamlit run app.py
   ```

6. **Open your browser** and navigate to `http://localhost:8501`

## 🚀 Deployment

This app is deployed on **Streamlit Community Cloud**. To deploy your own version:

1. **Push to GitHub** (public repository required)
2. **Visit** [share.streamlit.io](https://share.streamlit.io)
3. **Connect** your GitHub repository
4. **Set main file** to `app.py`
5. **Deploy!** 🎉

For detailed deployment instructions, see `DEPLOYMENT.md`.

## 📊 Model Information

- **Algorithm**: Random Forest Regressor
- **Framework**: Scikit-learn pipeline with preprocessing
- **Features**: 11 input parameters
- **Output**: Delivery time in minutes
- **Performance**: Optimized for real-world delivery scenarios

### Model Pipeline
- **Preprocessing**: Feature scaling and encoding for categorical variables
- **Training**: Trained on historical delivery data
- **Validation**: Cross-validated for robust performance

## 🗂️ Project Structure

```
food-delivery-time-prediction/
│
├── 📄 app.py                    # Main Streamlit application (Homepage)
├── 📁 pages/                    # Streamlit pages directory
│   └── 📄 predictor.py          # Prediction page with ML model
├── 📁 images/                   # Static images
│   └── 🖼️ food_delivery.jpg     # Hero image for homepage
├── 🤖 rf_pipeline.pkl           # Pre-trained Random Forest model
├── 📋 requirements.txt          # Python dependencies
├── 📖 README.md                 # Project documentation (this file)
├── 🚀 DEPLOYMENT.md             # Deployment instructions
├── 🙈 .gitignore               # Git ignore rules
├── 📁 .git/                    # Git repository data
├── 📁 .qodo/                   # Qodo configuration
└── 📁 venv/                    # Virtual environment (local only)
```

## 🔧 Troubleshooting

### Common Issues

#### Scikit-learn Version Mismatch
```bash
# Solution: Use exact versions
pip install scikit-learn==1.6.1 joblib==1.5.2
```

#### Model Loading Errors
- Ensure `rf_pipeline.pkl` is in the root directory
- Check file permissions and integrity
- Verify all dependencies are installed

#### Streamlit Navigation Issues
- Ensure `pages/` directory structure is correct
- Verify `predictor.py` is in the `pages/` folder
- Check that `st.switch_page()` paths are correct

#### Virtual Environment Issues
```bash
# Deactivate and recreate if needed
deactivate
rm -rf venv  # or rmdir /s venv on Windows
python -m venv venv
```

## 🤝 Contributing

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Streamlit** for the amazing web app framework
- **Scikit-learn** for machine learning capabilities
- **Python community** for the excellent ecosystem

## 📞 Contact

**Project Link**: https://github.com/Bumal-Sathsara/food-delivery-time-prediction

**Live Demo**: https://bumal-sathsara-food-delivery-time-prediction.streamlit.app/predictor

---

⭐ **Star this repository** if you found it helpful!
