- Download and unzip the BMCS.rar folder

- Anaconda/BMCS suite installation instruction:

  1. In your browser, locate the anaconda package in the repository: https://www.anaconda.com/distribution/#download-section
  2. Click on the version appropriate for your operating system (It is macOS Installer by default!!!)
  3. Download the Python 3.7 version of the Graphical Installer (64-Bit/32-Bit)
  4. Install the anaconda in the preferred destination folder and please do not change advanced options
  5. Find “Anaconda prompt” in start menu in windows, or this folder: \Users\username\AppData\Local\Continuum\anaconda3
  6. To install all required packages, in the Anaconda command prompt enter the following script, press enter, and if it asks to proceed,   type “y” and press enter again

       conda install -c conda-forge mayavi

  7. To install the BMCS suite, stay in the Anaconda command prompt and enter the following script and press enter

       pip install --extra-index-url anaconda.org/rosoba bmcs

  8. Still in the command prompt, type in the suite name “bmcs” and press enter. Upon a successful installation the bmcs launcher window     will appear. If not, go to the Section III Troubleshooting.


 -  Troubleshooting

    1. In the Anaconda prompt, type “ipython” and press enter
    2. Type “import bmcs.api” and press enter
    3. Report the error to saeed.rastegarian@rwth-aachen.de
      
