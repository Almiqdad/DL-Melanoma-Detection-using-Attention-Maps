# DL-Melanoma-Detection-using-Attention-Maps

Authors: Ifrah Andleeb, Almiqdad Elzein, Vaibhav Patel, Yasser Alginahi
Listed in the 2024 IEEE 3rd International Conference on Computing and Machine Intelligence proceedings.

## Citation

If you use this repository or find it helpful, please cite our paper:

```bibtex
@inproceedings{andleeb2024melanoma,
  title={Deep Learning-Based Melanoma Detection using Attention Maps},
  author={Andleeb, Ifrah and Elzein, Almiqdad and Patel, Vaibhav and Alginahi, Yasser},
  booktitle={2024 IEEE 3rd International Conference on Computing and Machine Intelligence},
  year={2024},
  publisher={IEEE}
}

### Clone the Repository
First, clone the repo to your local machine using Git:
```bash
git clone [URL of the Git repository]
cd [repository name]
```

### Setting Up a Virtual Environment
It's recommended to run Python projects in a virtual environment to manage dependencies. To set up a virtual environment, run:
```bash
python -m venv venv
```
Activate the virtual environment:
- On Windows: `venv\Scripts\activate`
- On Unix or MacOS: `source venv/bin/activate`

### Install Dependencies
Install all required packages:
```bash
pip install -r requirements.txt
```

### Use your trained model
1. Move your model to `03UIApplication\static\models`
2. Set the name of your model in `app.py` => `MODEL_PATH = "static/models/<your-model>.pt"`

## Running the Application
To run the Flask application, use the following command:
```bash
python app.py
```
