## The minimum QML with PennyLane (June 2026)
- **Author:** [Jacob Cybulski](https://jacobcybulski.com/) ([LinkedIn](https://www.linkedin.com/in/jacobcybulski/)), *Enquanted*
- **Aims:** To explore the creation and use of quantum machine learning models in PennyLane (PL).
- **Description:** This Quantum Machine Learning (QML) workshop provides an introduction to Quantum Machine Learning using PennyLane, with hands-on exercises and take-home challenges. The workshop includes two simple exercises that cover the fundamental QML concepts, models, and techniques.
- **Preparation:** Before attempting the practical exercises, we recommend to do some preparation first:
  - Download all resources (notes, code and data)
  - Install the recommended Python virtual environment (venv + requirements), see "install" folder
  - Undertake some preliminary exercises and get familiar with:
    - PyTorch, tensors, gradients and neural networks:<br>
      AssemblyAI, “PyTorch Crash Course - Getting Started with Deep Learning”, Jul 2022.<br>
      [https://www.youtube.com/watch?v=OIenNRt2bjg](https://www.youtube.com/watch?v=OIenNRt2bjg) (50 mins)
    - PennyLane, functions, circuits, qnodes and measurements:<br>
      Diego Emilio Serrano, “Basic Introduction to PennyLane”, Feb 2023.<br>
      [https://www.youtube.com/watch?v=MCDHAn-GvA8](https://www.youtube.com/watch?v=MCDHAn-GvA8) (40 mins)
    - PennyLane circuit creation and execution for busy people:<br>
      Isaac De Vlugt, “My first quantum circuit in PennyLane”, Sept 2023<br>
      [https://www.youtube.com/watch?v=uCm027_jvZ0](https://www.youtube.com/watch?v=uCm027_jvZ0) (5 mins)
    - Study two workshop notebooks in the "Explore" section (see table below) (1 hour)
    - You are now ready!
- **Release Date:**
  - _**June, 3 2026:**_ The final versions will be made available 1 day before the workshop
- **Last Update:**
  - _**June, 3 2026:**_ Compatibility updates with recent versions of PennyLane.

### Important notebooks

You can play with these notebooks, enjoy!<br>
Note however that they may be updated at any time!

| Session | File | Description |
| :- | :- | :- |
| *Exercise&nbsp;0* | s00_explore_tiny_model_vN_nD.ipynb | Explains QML principles using PL |
| *Exercise&nbsp;1* | s01_simple_model_vN_nD.ipynb | Creates and tests a very simple quantum model |
| *Other* | requirements.txt | A list of software needed for this workshop (for auto-install with *pip*) |

### Folders
- _**notebooks:**_ all workshop notebooks can be found here
- _**slides:**_ presentation slides in PDF
- _**install:**_ installation instructions
  
### Requirements
- Set up a virtual environment with **venv** or **anaconda** for Python 3.11 and activate it
- Then install all software using **requirements.txt** file (available here):
    - pip install -r \<place-you-saved-it\>/requirements.txt
- Or install by hand by following these instructions:
    - pip install pennylane==0.42.3 pennylane-lightning==0.42.0 (PennyLane)
    - pip install scikit-learn==1.7.2 pandas==2.3.2 (ML)
    - pip install matplotlib==3.10.6 plotly==6.3.0 seaborn==0.13.2 pillow==11.3.0 (plots and images)
    - pip install jupyter==1.1.1 jupyterlab==4.4.7 (running jupyter notebooks)
    - pip install kagglehub==0.3.13 ucimlrepo==0.0.7 (data access)
    - pip install pdflatex (optionally to plot and export some plots and tables to latex)
    - install [PyTorch](https://pytorch.org/get-started/locally/), as per web site instructions, also add:<br>
      pip install torchvision torchaudio torchsummary torcheval torchmetrics

The **requirements.txt** file was tested for installation on 
Ubuntu 22.04-24.04, Windows 11 and MacOS Sequoia 15.3.1 (with M3 procesor).

### License
This project is licensed under the [GNU General Public License v3](./LICENSE).
The GPL v3 license requires attribution for modifications and derivatives, ensuring that users know which versions are changed and to protect the reputations of original authors.