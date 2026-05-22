# HangulTranslationTool
A high-performance offline Korean screen reader and overlay translator using a custom C++ DXGI desktop capture engine and a fine-tuned local PyTorch Transformer pipeline via shared memory IPC
Quick start:
Run the training script to train your local weights
  ```bash
   python train_model.py

Compile the C++ part on your own computer

double click run_me.bat to launch it

has:
's' key input to take a timestamped screenshot with the translations
'~' key to cleanly close the system and terminate processes
