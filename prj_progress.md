### Getting started
- Create a new virtual environment
    - Use `pyenv` if some other version of python is installed (other than 3.11.x)
    - Activate virtual environment and install the necessary modules using `pip install -r requirements.txt`.
    - I have modified `requirements.txt` in such a way that it doesn't install `pytorch` as the default installation of `pytorch` installs with GPU drivers and software support as well.
    - To install `pytorch` only for CPU, run the command mentioned in `installing_torch_cpu_only.txt`.


### Project Progress
- [x] Building model file for those 5 classes
    - [x] Setting up the MSDK (not MaximSDK) environment
- [ ] Running on MAX78000
    - [x] Building the code
    - [x] Running without TFT LCD Display
    - [ ] Running with TFT LCD Display
- [ ] UI generation
    - [ ] Code changes for UI
- [ ] Learning and re-training for unknown subjects (on-chip or off-chip).
