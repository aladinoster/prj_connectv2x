**| [Overview](#overview) | [Reproducibility](#reproducibility) | [License](#license) | [Contact](#contact) |**

# Connected Vehicles 

## Overview

Project on connected vehicles

### Base functions 

All functionalities are implemented in the following package [connectv2x](https://github.com/aladinoster/connectv2x)

## Reproducibility

Download this repository

```{bash}
git clone https://github.com/aladinoster/prj_connectv2x.git
```

Be sure to get [conda](https://www.anaconda.com/distribution/), then:

```{bash}
mkdir 01_v2x
conda env create -f=environment.yaml -p 01_v2x
conda activate path/to/folder/01_v2x
jupyter labextension install jupyterlab_bokeh
```

## License

The code here contained is licensed under [MIT License](LICENSE)

## Contact 

If you run into problems or bugs, please let us know by [creating an issue](https://github.com/aladinoster/prj_connectv2x/issues/new) an issue in this repository.