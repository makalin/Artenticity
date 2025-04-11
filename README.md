# 🎨 **Artenticity** – Crowdsourced AI Art Authenticity Verifier

Artenticity is an AI-powered system designed to verify the authenticity of digital artworks and NFTs by analyzing visual patterns, metadata, and blockchain provenance. Built upon crowdsourced datasets, Artenticity ensures ethical standards and digital ownership integrity in the rapidly evolving NFT and digital art marketplace.

## ✨ **Features**
- **Pattern Analysis:** AI-driven image analysis to detect manipulations or anomalies.
- **Metadata Verification:** Inspects metadata consistency and identifies irregularities.
- **Blockchain Provenance:** Checks and validates ownership history on various blockchains.
- **Crowdsourced Training:** Trained on a continuously updated dataset of genuine and fake artworks contributed by the community.

## 🚀 **Getting Started**

### **Installation**

Clone the repository:

```bash
git clone https://github.com/makalin/Artenticity.git
cd Artenticity
```

Install dependencies:

```bash
pip install -r requirements.txt
```

### **Run the Application**

```bash
python app.py
```

### **Docker Setup**

Alternatively, use Docker for quick setup:

```bash
docker build -t Artenticity .
docker run -p 5000:5000 Artenticity
```

## 📁 **Project Structure**

```plaintext
Artenticity/
├── data/
│   ├── genuine/   # Genuine artwork dataset
│   └── fake/      # Fake artwork dataset
├── models/        # Trained AI models
├── src/
│   ├── analyzer.py   # Image analysis logic
│   ├── blockchain.py # Blockchain provenance verifier
│   ├── metadata.py   # Metadata validation
│   └── utils.py      # Utility functions
├── tests/
│   └── test_analyzer.py # Unit tests
├── requirements.txt
├── Dockerfile
├── .gitignore
└── app.py            # Main application script
```

## 🛠 **Technologies Used**
- Python
- TensorFlow / PyTorch
- OpenCV
- Web3.py (Ethereum & other blockchains)
- Flask (Web API)

## 🤝 **Contributing**

We welcome contributions from the community! Please:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a pull request.

## 📜 **License**

This project is licensed under the MIT License.
