```markdown
# HealthCare Chatbot and Skin Disease Prediction App

## Description:

This repository contains code for a HealthCare Chatbot and a Skin Disease Prediction App developed using Streamlit. The HealthCare Chatbot predicts common diseases based on symptoms provided by the user, while the Skin Disease Prediction App predicts whether a skin lesion is melanoma or an allergy based on uploaded images.



## Features:

- HealthCare Chatbot:
  - Predicts common diseases based on symptoms provided by the user.
  - Provides descriptions and precautions for identified diseases.
  - Offers consultations based on symptom severity and duration.

- Skin Disease Prediction App:
  - Allows users to upload images of skin lesions.
  - Predicts whether the lesion is melanoma or an allergy.
  - Utilizes a pre-trained ResNet50 model for prediction.

---

## File Structure:

1. **skinandsymp.py**: Main script responsible for creating the user interface and handling user interactions.
2. **requirements.txt**: Lists all dependencies required for running the project.



## Getting Started:

To run the ChatBot locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/pervaje28megh/skinandsymp.git
   ```

2. Install the required dependencies using the following command:

   ```bash
   pip install -r requirements.txt
   ```

   The `requirements.txt` file might look like:

   ```
   streamlit==1.7.0
   pandas==1.4.0
   numpy==1.21.0
   scikit-learn==0.24.2
   tensorflow==2.8.0
   torch==1.10.0
   torchvision==0.11.1
   ```

   Running `pip freeze > requirements.txt` will create a `requirements.txt` file in your current directory containing a list of all installed packages along with their versions.

3. Setup Environment Variables.

4. Run the `skinandsymp.py` script using Python:

   ```bash
   streamlit run healthcare_chatbot.py
   ```

5. Interact with the ChatBot by typing or using images for skin cancer prediction.



## Contributing:

Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.



## License:

This project is licensed under the [MIT License](LICENSE).

```

