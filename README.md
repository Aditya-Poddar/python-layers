
# Python Layers

## Steps to create a custom pandas layer:

### Step1: Download the pandas library depending upon operating system.
https://files.pythonhosted.org/packages/a3/40/eca46f6af07a83ea3b8706586b2d8a28c01bdccee789d24f2ccc5e148b28/pandas-2.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl

### Step2: Download the pytz library file.
https://files.pythonhosted.org/packages/7f/99/ad6bd37e748257dd70d6f85d916cafe79c0b0f5e2e95b11f7fbc82bf3110/pytz-2023.3-py2.py3-none-any.whl

### Step3: Check wheel is installed in your system or not. If not install it.
 pip install wheel

### Step4: Unpack the library
wheel unpack library_name

It will create folder with specific library name.

### Step5: Creata folder name as python
copy the files from the specific library folder and paste into pythohn folder.

### Step6: Zip the python folder.

### Step7: Go the Amazon Management Consol and choose Lambda.
  - 1.Click on Layers
  - 2.Now Create a new layer.
  - 3.Give the name of layer and specify the Compatiable runtime and architecture and choose pton zip file to upload file which is zipped earlier.