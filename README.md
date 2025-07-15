# 🥗 NutriCheck

**NutriCheck** is an AI-powered ingredient analysis tool that helps users make healthier food choices by providing detailed insights into product ingredients and suggesting safer alternatives.

---

## 🧠 About the Project

NutriCheck leverages cutting-edge technologies including **OCR**, **LangChain with LLaMA**, and **Streamlit** to:
- Extract ingredient lists from product images or text
- Analyze health impacts of each ingredient
- Compare ingredient quantities with recommended safety limits
- Suggest healthier alternatives
- Generate detailed reports to support informed decisions

---

## 🚀 Features

- 🧾 OCR-based ingredient extraction
- 🧠 AI-powered health impact analysis
- 📊 Safety limit comparison
- 🥦 Healthy alternative suggestions
- 📄 Interactive reports via Streamlit

---

## 🗂️ Project Structure

- `ingredient_analysis/` – Core logic for ingredient evaluation
- `ingredient_analysis_app/` – Streamlit app interface
- `media/analysis_images/` – Sample images for testing
- `medical_history/` – User health data integration
- `templates/` & `staticfiles/` – Web UI components
- `requirements.txt` – Python dependencies
- `PROJECT-REQUIREMENT-DOCUMENT.txt` – Project scope and goals

---

## 🛠️ Tech Stack

- **Python**, **Streamlit**, **LangChain**, **OCR**
- Frontend: **HTML**, **CSS**, **JavaScript**
- Others: **PowerShell**, **Roff**

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/kamblesarvesh178/NutriCheck.git
   ```
2. Set up the environment:
   ```bash
   cd NutriCheck
   python -m venv myenv
   source myenv/bin/activate  # or myenv\\Scripts\\activate on Windows
   pip install -r requirements.txt
   ```
3. Run the app:
   ```bash
   streamlit run ingredient_analysis_app/app.py
   ```

---

## 🙌 Contributing

Contributions are welcome! Feel free to fork the repo, create new features, or improve existing ones. Submit a pull request with your changes.

---

## 📧 Contact

Created by **Sarvesh Kamble**  
For questions or suggestions, reach out via GitHub.
