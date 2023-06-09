# **Automatic Bank Form Generation using IVRS**
This project is a system developed using Python that interacts with the user in their native language, in this case, Telugu. The system is designed to generate bank forms automatically based on user inputs. The project is developed as part of a socially relevant initiative to help illiterate people who rely on others to fill out forms in banks.

# **Functionality**
The system uses a camera sensor to scan the QR code on the user's bank passbook, which is then decoded to retrieve the account number of the account. The system then fetches all the user data from the accounts database using that account number.

The system then asks the user whether they want to deposit or withdraw money from their account. The user can reply in their native language, and the system will understand the input. Based on the user's input, the system asks for the amount to be deposited or withdrawn.

Once the user provides the required information, the system generates a bank form that the user can submit to the bank counter.

# **Requirements**
To run this project, you will need:

  Python 3.x
  
  **Packages :**
  
    gtts: gtts is a Python library and CLI tool that uses Google Text-to-Speech engine to convert text to spoken audio. It is used to generate audio responses for the user.

    playsound: playsound is a pure Python, cross-platform audio library used to play audio files. It is used to play the audio generated by the gtts package.

    cv2: cv2 is a Python wrapper for the OpenCV computer vision library. It is used to capture images using the camera sensor.

    numpy: numpy is a Python package for scientific computing with Python. It is used for numerical operations on the images captured using cv2.

    pyzbar: pyzbar is a Python library used to decode QR codes. It is used to decode the QR code on the user's bank passbook.

    speech_recognition: speech_recognition is a Python library for performing speech recognition. It is used to recognize the user's speech input.

    selenium: selenium is a Python library used for automating web browsers. It is used to fill out the form on the bank's website.

    webdriver_manager: webdriver_manager is a Python library used for managing web drivers. It is used to manage the ChromeDriver for Selenium.

    sqlite3: sqlite3 is a Python library used to work with SQLite databases. It is used to fetch the user's data from the accounts database.

    num2words: num2words is a Python library used to convert numbers to words. It is used to convert the amount entered by the user from digits to words.

    word2number: word2number is a Python library used to convert words to numbers. It is used to convert the user's speech input for the amount entered from words to digits.

    translators: translators is a Python library used to translate text from one language to another. It is used to translate the user's speech input from Telugu to English for processing.
    
    
# **Usage**
To run the project, simply execute the main.py file. Make sure you have all the required packages installed beforehand.

# **Conclusion**
In conclusion, the Automatic Bank Form Generation using IVRS is a system developed using Python to interact with users in their native language, Telugu. It is specifically designed for illiterate people who have to rely on others to fill out bank forms. This project allows them to generate bank forms automatically by scanning their passbook, fetching user data using the account number, and asking for deposit or withdrawal inputs. The system then generates a form that can be submitted at the bank counter.

## **Credits**

This project was developed by Jagannadha Rohit Varma Mandhapati as part of Socially Relevant Project at Maharaj Vijayaram Gajapathi Raj College of Enginnering.
