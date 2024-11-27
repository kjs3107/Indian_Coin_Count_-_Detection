
# Indian Coin Count Detection

This project aims to detect and count Indian coins using computer vision techniques. The system processes an image of Indian coins, detects the coins, and identifies their denomination. The project uses image processing algorithms to accurately detect and classify coins such as ₹1, ₹2, ₹5, ₹10, and others.

## Features

- **Coin Detection**: Detects coins in a given image using image processing techniques.
- **Denomination Recognition**: Identifies different denominations of Indian coins (₹1, ₹2, ₹5, ₹10).
- **Count Calculation**: Automatically counts the number of coins for each denomination in the image.
- **User-Friendly Interface**: Upload an image for coin detection and get the result instantly.

## Technologies Used

- **OpenCV**: For image processing and coin detection.
- **Python**: The primary programming language used for the implementation.
- **NumPy**: For numerical operations and handling arrays.
- **TensorFlow/Keras** (optional, if used): For deep learning-based classification (if applicable).

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/indian-coin-count-detection.git

   Usage
Prepare an image containing Indian coins that you want to analyze.

Run the detection script:

bash
Copy code
python detect_coins.py --image path_to_your_image
The script will output the total count of coins for each denomination found in the image.

Example output:

makefile
Copy code
Detected Coins:
₹1: 5
₹2: 3
₹5: 2
₹10: 1
Total Count: 11 Coins
Results
This project offers an accurate coin detection and counting mechanism even for images where coins may overlap or be partially visible.

Contributing
Contributions are welcome! If you'd like to contribute, feel free to fork the repository and submit a pull request with your improvements.

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
