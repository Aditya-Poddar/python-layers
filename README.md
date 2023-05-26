
# Pandas Lambda Function Layers for Python 3.10 Version

### Easy method : Dowload the <a href="https://drive.google.com/file/d/1Z4kLq4hH7xbSpi5lRCXEn3sOQNmi9yKn/view?usp=share_link">Python.Zip</a> file from the link and upload in lambda function and enjoy the AWS Lambda Service seamless. <a href="https://drive.google.com/file/d/1Z4kLq4hH7xbSpi5lRCXEn3sOQNmi9yKn/view?usp=share_link">Download Link</a>

# Steps to create a your own custom pandas layer:

## Step1: Download the pandas library depending upon operating system.
https://files.pythonhosted.org/packages/a3/40/eca46f6af07a83ea3b8706586b2d8a28c01bdccee789d24f2ccc5e148b28/pandas-2.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl

### Also downloading the dependency of pandas library i.e Numpy
https://files.pythonhosted.org/packages/eb/10/2c3c672034d860bcca50b65d656e24c4e2ace9fb452fdd81da78cb7418a1/numpy-1.24.3-pp38-pypy38_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
##### (Optional) Links to find pnadas libarary for another operating system and python version. https://pypi.org/project/pandas/#files


## Step2: Download the pytz library file.
https://files.pythonhosted.org/packages/7f/99/ad6bd37e748257dd70d6f85d916cafe79c0b0f5e2e95b11f7fbc82bf3110/pytz-2023.3-py2.py3-none-any.whl

##### (Optional) To find library file for others version. https://pypi.org/project/pytz/#files

## Step3: Check wheel is installed in your system or not. If not install it.
```sh
pip install wheel
```

#### If giving error like that update the pip persion.
- `[notice] A new release of pip is available: 23.0.1 -> 23.1.2`
- `[notice] To update, run: python.exe -m pip install --upgrade pip`
```sh
 python.exe -m pip install --upgrade pip
 ```

## Step4: Unpack the library
```sh
wheel unpack .\pandas-2.0.1-cp310-cp310-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
wheel unpack .\pytz-2023.3-py2.py3-none-any.whl 
wheel unpack .\numpy-1.24.3-pp38-pypy38_pp73-manylinux_2_17_x86_64.manylinux2014_x86_64.whl
```

It will create folder with specific library name.

## Step5: Creata folder name as python
copy the files from the specific library folder and paste into pythohn folder.

## Step6: Zip the python folder.

## Step7: Go the Amazon Management Consol and choose Lambda.
  - 1.Click on Layers
  - 2.Now Create a new layer.
  - 3.Give the name of layer and specify the Compatiable runtime and architecture and choose pton zip file to upload file which is zipped earlier.
