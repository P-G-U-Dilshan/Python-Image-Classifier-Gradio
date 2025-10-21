# AI-Powered Image Classifier Web App

> **Note:** You can view a summary of this project on my [**LinkedIn Post**]([[https://www.linkedin.com/posts/pgudilshan_artificialintelligence-deeplearning-computervision-activity-7386061973475618817-pqyj?utm_source=share&utm_medium=member_desktop&rcm=ACoAAF-q3BUBsl-DjW0ndOchJC_uNQMSfqYydL0]).

From theory to practice! This is a simple web app that uses a powerful Deep Learning model (Google's Vision Transformer) to identify objects in photos.

I used the Hugging Face `transformers` library to implement the pre-trained model and `Gradio` to create a sleek, interactive web interface in just a few lines of code.

---

## 🛠️ Technologies Used

* **Python**
* **Google's Vision Transformer (ViT):** The Deep Learning model used for classification (specifically, `google/vit-base-patch16-224`).
* **Hugging Face `transformers`:** To download and run the pre-trained model via a simple `pipeline`.
* **Gradio:** To instantly create the user-friendly web UI.
* **PyTorch & Pillow:** As dependencies for the `transformers` library.

---

## 🚀 How It Works

1.  **Load Model:** The app initializes an `image-classification` pipeline from Hugging Face, which downloads and loads the Google ViT model.
2.  **Define Function:** A simple function takes an uploaded image as input.
3.  **Classify:** This function passes the image to the model pipeline, which returns a list of predictions.
4.  **Display:** The predictions are formatted and returned to the `Gradio.Label` component, which neatly displays the Top 3 results (label and confidence score).

---

## 🏃 How to Run It

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/Python-Image-Classifier-Gradio.git](https://github.com/YourUsername/Python-Image-Classifier-Gradio.git)
    cd Python-Image-Classifier-Gradio
    ```

2.  **Install dependencies:**
    ```bash
    pip install gradio transformers torch pillow
    ```

3.  **Run the app:**
    Run the Jupyter Notebook (`.ipynb`) file, or save the code as a `.py` file and run:
    ```bash
    python app.py
    ```
    The app will launch, and you can access it in your browser.

---
### Screenshot

Here is a screenshot of the final application interface:

*(**Pro-Tip:** ඔයාගෙ `image_ebf7f7.png` file එකේ තියෙන app එකේ screenshot එක crop කරලා, ඒක `app-screenshot.png` වගේ නමකින් repository එකට upload කරලා, ඒ file name එක මෙතන `[PASTE_SCREENSHOT_NAME_HERE]` තැනට දාන්න.)*

`![App Screenshot]([PASTE_SCREENSHOT_NAME_HERE])`
