# Local ChatGPT with thinking UI

This project leverages Qwen3:4B and Streamlit to create a 100% locally running mini-ChatGPT app.

## Installation and setup

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   # pull the Qwen3:4B model
   ollama pull qwen3:4b 
   ```


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama
   ```

**Run the app**:

   Run the streamlit app as follows:
   ```bash
   streamlit run app.py -w
   ```

**DEMO**:
<img width="1913" height="978" alt="image" src="https://github.com/user-attachments/assets/5a2e66b3-91db-44df-b9df-227e856d5ad6" />
<img width="1913" height="992" alt="Screenshot 2026-02-27 144212" src="https://github.com/user-attachments/assets/77f606c0-e446-483f-91d7-130230b5c994" />


---

---

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
