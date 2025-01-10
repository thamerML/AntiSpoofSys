# AntiSpoofSys

AntiSpoofSys is an AI-powered vehicle gate access system designed to enhance security and efficiency. It leverages advanced machine learning and computer vision techniques to verify vehicles, license plates, and drivers in real-time, ensuring a seamless and secure access experience.

---

## Features

- **License Plate Recognition:**
  - Detects and authenticates license plates, including Saudi-specific formats.
  - Incorporates anti-spoofing measures to prevent fake plate attempts.

- **Vehicle Classification:**
  - Identifies vehicle types (e.g., sedan, SUV, truck) for customized access rules.

- **Facial Recognition:**
  - Authenticates drivers using advanced facial recognition.
  - Prevents spoofing through photo or video attacks.

- **Real-Time Performance:**
  - Provides fast and reliable detection and authentication.

- **Hardware Integration:**
  - Compatible with servo motors or gate actuators controlled via Raspberry Pi/Arduino.

---

## Project Overview

### **Technologies Used:**
- **Programming Language:** Python
- **Database:** PostgreSQL
- **Hardware:** Raspberry Pi, Arduino, Servo Motor
- **Machine Learning Models:** Pretrained and retrained for Saudi-specific requirements

### **How It Works:**
1. Captures video input to detect vehicles and license plates.
2. Verifies license plates against a database.
3. Identifies and authenticates the driver's face.
4. Opens the gate for verified entries.

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
