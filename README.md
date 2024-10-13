This project leverages a machine learning model trained on the DermaNet dataset to classify skin diseases. The model is integrated with a Telegram bot, offering a familiar and user-friendly interface for users to interact with. Key steps involved in this project:

Dataset & Model Training:

The dataset is sourced from Kaggle.
The model is trained using a subset of skin diseases for faster results, or the entire dataset for more comprehensive coverage. The model architecture and training process are based on this Kaggle notebook.
Telegram Bot Integration:

After training, the model is saved locally.
The path to the trained model is specified in the telegram_bot_interface.py script.
A bot is created on Telegram, and the API key is integrated into the script for real-time interaction.
User Interface:

Users can send images of skin conditions to the bot.
The bot processes the image, feeds it to the trained ML model, and returns the predicted skin disease along with relevant information.
This setup allows for a practical application of machine learning in healthcare, making diagnosis assistance more accessible and convenient for users.
