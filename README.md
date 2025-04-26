
# 📈 TrendCast

**TrendCast** is a machine learning-powered forecasting tool designed to predict trends in time-series data, such as stock prices or power grid metrics. Built with Python, Jupyter Notebook, and deep learning models, TrendCast provides a simple interface for users to generate accurate forecasts using historical datasets and pre-trained models.

---

## ✨ Features

- 📊 Time-series forecasting using deep learning (Keras/TensorFlow)
- 📈 Pre-trained models for stock price prediction
- 📂 Example datasets for experimentation (e.g., `powergrid.csv`)
- 🌐 Interactive web app interface (Flask)
- 📓 Jupyter Notebook for model exploration and customization

---

## 📚 Table of Contents

- [Features](#-features)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🛠 Installation

Clone the repository:

```bash
git clone https://github.com/SyedAbdurRahman/TrendCast.git
cd TrendCast
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Running the Flask App:

```bash
python app.py
```
The web interface will be available at: [http://localhost:5000](http://localhost:5000)

---

### Experimenting with the Jupyter Notebook:

- Open `main.ipynb` in Jupyter Notebook or JupyterLab to explore and modify the forecasting models.

---

### Using Your Own Data:

- Replace or add your dataset (in CSV format).
- Update the code in `main.ipynb` or the Flask app accordingly to reflect your new data structure.

---

## 📂 Project Structure

| File/Folder           | Description                                |
|------------------------|--------------------------------------------|
| `app.py`               | Flask web application entry point         |
| `main.ipynb`           | Jupyter Notebook for model training/testing |
| `requirements.txt`     | Python dependencies                       |
| `powergrid.csv`        | Example dataset                           |
| `stock_dl_model.h5`    | Pre-trained stock price model             |
| `stock_dl_model_new.h5`| Alternate/updated model                   |
| `static/`, `templates/`| Web app assets and HTML templates         |

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repository, open an issue, or submit a pull request to help improve **TrendCast**.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by [Syed Abdur Rahman](https://github.com/SyedAbdurRahman)

---
