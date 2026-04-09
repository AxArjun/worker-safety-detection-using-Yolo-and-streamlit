🦺 Worker Safety Detection using YOLO & Streamlit

An AI-powered workplace safety monitoring system that detects whether workers are wearing proper Personal Protective Equipment (PPE) using YOLO (You Only Look Once) and provides an interactive interface via Streamlit.

This project helps automate safety compliance in industries like construction, manufacturing, and mining by identifying violations in real-time.

🚀 Features
🔍 Real-time PPE Detection
Detect helmets, vests, masks, and other safety gear
📷 Multiple Input Sources
Image upload
Video file processing
Live webcam detection
📊 Interactive Dashboard (Streamlit)
Visual results with bounding boxes
Easy-to-use UI
⚠️ Violation Detection
Identifies missing PPE
Highlights unsafe workers
⚡ Fast Inference with YOLO
High accuracy and real-time performance

Similar systems use YOLO models to detect PPE compliance like helmets and vests in real-time workplace monitoring.

🧠 Tech Stack
Python
YOLO (Ultralytics) – Object Detection
OpenCV – Image & Video Processing
Streamlit – Web App Interface
NumPy / Pandas – Data handling
📁 Project Structure
worker-safety-detection/                                      
│                     
├── app.py                # Main Streamlit application                         
├── detect.py             # Detection logic using YOLO                  
├── webcam.py             # Webcam-based detection                 
├── utils/                # Helper functions               
├── models/               # Trained YOLO weights (e.g., ppe.pt)                
├── requirements.txt      # Dependencies                    
└── README.md             # Project documentation             
⚙️ Installation
1. Clone the repository
git clone https://github.com/AxArjun/worker-safety-detection-using-Yolo-and-streamlit.git
cd worker-safety-detection-using-Yolo-and-streamlit
2. Create a virtual environment
python -m venv venv
source venv/bin/activate        # Mac/Linux
venv\Scripts\activate           # Windows
3. Install dependencies
pip install -r requirements.txt
📦 Model Setup
Download or train a YOLO model (e.g., ppe.pt)
Place it inside the models/ directory

YOLO models are widely used for detecting PPE like helmets, masks, and vests in safety applications.

▶️ Usage
Run the Streamlit App
streamlit run app.py
Features inside the app:
Upload image → Detect PPE
Upload video → Frame-by-frame detection
Use webcam → Live monitoring
📸 How It Works
Input image/video/webcam stream
YOLO model processes frames
Detects:
Person
Helmet / No Helmet
Vest / No Vest
Draws bounding boxes:
✅ Green → Safe
❌ Red → Violation
Displays results in Streamlit UI
📊 Example Use Cases
🏗️ Construction site monitoring
🏭 Factory worker compliance
🚧 Industrial safety auditing
🎥 CCTV-based surveillance systems
⚠️ Limitations
Requires good lighting for accurate detection
Performance depends on model quality
Real-time detection may need GPU for best results
🔮 Future Improvements
🚨 Real-time alert system (SMS / Email)
📈 Analytics dashboard for safety reports
🧑‍🤝‍🧑 Worker tracking & ID assignment
☁️ Cloud deployment (AWS / Azure)
📡 Integration with CCTV systems
🤝 Contributing

Contributions are welcome!

Fork the repo
Create a new branch
Commit your changes
Open a Pull Request
📜 License

This project is licensed under the MIT License.

🙌 Acknowledgements
YOLO by Ultralytics
OpenCV community
Streamlit for rapid UI development
📬 Contact

For queries or suggestions, feel free to open an issue or connect via GitHub.
