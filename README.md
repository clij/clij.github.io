# CLIJ: GPU-accelerated image processing in Fiji
## Introduction
CLIJ is an OpenCL - ImageJ bridge and a [Fiji](https://fiji.sc/) plugin allowing users with no computer science background to exploit GPU-acceleration for their image processing workflows. Increased efforts were put on documentation, code examples, interoperability, and extensibility.
CLIJ is based on [ClearCL](http://github.com/ClearControl/ClearCL), [Imglib2](https://github.com/imglib), [ImageJ](http://image.net) and [SciJava](https://github.com/SciJava)

**If you use CLIJ, please cite it:**


If you search for support, please open a thread on the [image.sc](https://image.sc) forum.

[![Image.sc forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&url=https%3A%2F%2Fforum.image.sc%2Ftags%2Fclij.json&query=%24.topic_list.tags.0.topic_count&colorB=brightgreen&suffix=%20topics&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tags/clij)


## Overview

* [CLIJ - a quick tour](https://clij.github.io/clij-docs/quickTour)
* Installation
  * [Fiji update site](https://clij.github.io/clij-docs/installationInFiji)
  * [Depending on CLIJ via maven](https://clij.github.io/clij-docs/dependingViaMaven)
* Introduction to CLIJ programming
  * [CLIJ for ImageJ Macro programmers](https://clij.github.io/clij-docs/macro_intro)
  * [CLIJ for Java programmers](https://clij.github.io/clij-docs/api_intro)
  * [ImageJ Jupyter notebooks in Groovy](https://github.com/clij/clij-notebooks/blob/master/clij-intro.ipynb)
  * [Execution from the command line](https://github.com/clij/clij-executable-example)
  * [Release notes](https://github.com/clij/clij/releases)
* Application programming interface (API)
  * [API design principles](https://clij.github.io/clij-docs/api_design_priciples)
  * [ImageJ Macro](https://clij.github.io/clij-docs/reference)
  * [Jython](https://clij.github.io/clij-docs/referenceJython)
  * [Java](https://clij.github.io/clij-docs/referenceJava)
  * [Groovy](https://clij.github.io/clij-docs/referenceGroovy)
* Code examples
  * [ImageJ Macro](https://github.com/clij/clij-docs/tree/master/src/main/macro)
  * [BeanShell](https://github.com/clij/clij-docs/tree/master/src/main/beanshell)
  * [Jython](https://github.com/clij/clij-docs/tree/master/src/main/jython)
  * [JavaScript](https://github.com/clij/clij-docs/tree/master/src/main/javascript)
  * [Groovy](https://github.com/clij/clij-docs/tree/master/src/main/groovy)
  * [Java](https://github.com/clij/clij-docs/tree/master/src/main/java/net/haesleinhuepf/clij/examples)
* Extending CLIJ functionality
  * [Plugin template](https://github.com/clij/clij-plugin-template/)
  * [Example plugin for convolution/deconvolution](https://github.com/clij/clij-custom-convolution-plugin/)
* Troubleshooting
  * [List of tested systems](https://clij.github.io/clij-docs/testedsystems)
  * [Troubleshooting](https://clij.github.io/clij-docs/troubleshooting)
  * [Support](https://image.sc)

## Acknowledgements
Development of CLIJ is a community effort. We would like to thank everybody who helped developing and testing. In particular thanks goes to
Bruno C. Vellutini (MPI CBG),
Curtis Rueden (UW-Madison LOCI),
Damir Krunic (DKFZ),
Daniel J. White (GE),
Gaby G. Martins (IGC),
Siân Culley (LMCB MRC),
Giovanni Cardone (MPI Biochem),
Jan Brocher (Biovoxxel), 
Johannes Girstmair (MPI CBG),
Juergen Gluch (Fraunhofer IKTS),
Kota Miura (Heidelberg),
Laurent Thomas (Acquifer), 
Nico Stuurman (UCSF),
Pavel Tomancak (MPI CBG),
Pradeep Rajasekhar (Monash University),
Tobias Pietzsch (MPI-CBG)


  
