Folder structure
```
Prototype_Image_Classifier/
  imageclassifier.ipynb
  README.md
  .gitignore
  image_dataset/
    train/
```

Put all photos in subfolders based on class in the train folder:

EX. Dog images go into train/dogs whereas Cat images go into train/cats


HOW TO USE:
```bash
pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu126
pip install jupyter scikit-learn pillow numpy joblib gradio
```

Run each notebook block step by step, feature extraction will create .npy files which can be used to skip future extractions using the next codeblock down.
    