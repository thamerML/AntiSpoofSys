# AntiSpoofSys

AntiSpoofSys is an AI-powered vehicle gate access system designed to enhance security and efficiency. It leverages advanced machine learning and computer vision techniques to verify vehicles, license plates, and drivers in real-time, ensuring a seamless and secure access experience.

---

## Features

- **License Plate Recognition:**
  - Detects and authenticates license plates, including Saudi-specific formats.
 

- **Vehicle Classification:**
  - Identifies vehicle make and model (e.g., Toyota Camry, Honda Accord, Ford Crown Victoria).

- **Facial Recognition:**
  - Authenticates drivers using advanced facial recognition.


- **Real-Time Performance:**
  - Provides fast and reliable detection and authentication.

- **Hardware Integration:**
  - Compatible with servo motors or gate actuators controlled via Raspberry Pi/Arduino.

---

## Project Overview

### **Technologies Used:**
- **Programming Language:** Python3.9
- **Database:** PostgreSQL
- **Hardware:** ESP32, Servo Motor
- **Machine Learning Models:** Pretrained and retrained for Saudi-specific requirements

### **How It Works:**
1. Captures video input or live stream to detect vehicles, license plates, and faces.
2. Verifies the 3 features against a database.
3. Open the gate for verified entries.

---

## Demo

![AntiSpoofSys Demo](result.gif)



---

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/AntiSpoofSys.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd AntiSpoofSys
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up the Database:**
   - Ensure PostgreSQL is installed and running.
   - Create a database and configure connection settings in `config.py`.

5. **Run the Application:**
   ```bash
   python main.py
   ```

---

## Usage

1. Add known vehicles and drivers to the database.
2. Place the system at the gate and start the application.
3. The gate will open for verified vehicles and drivers.

---

## Contribution

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed explanation.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Contact

For questions or suggestions, feel free to reach out to the project team:
- **Thamer Alghonaim**
- **Faisal Alsultan**
- **Bandar Alwazzan**
