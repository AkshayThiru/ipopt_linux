# ipopt_linux
repo for automating download of IPOPT binaries for google colab notebooks

example to set up IPOPT with pyomo:
```
import sys
IN_COLAB = 'google.colab' in sys.modules
if IN_COLAB:
  !pip install -q pyomo
  !wget -N -q "https://github.com/thomasfork/ipopt_linux/raw/main/ipopt-linux64.zip"
  !unzip -o -q ipopt-linux64
```

a complete example is provided in the file colab_example.ipynb
