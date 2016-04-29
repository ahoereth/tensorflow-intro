# TensorFlow Introduction

This introduction to TensorFlow was part of the *Concepts and Applications to Neural Networks* (CANN) course at the Institute of Cognitive Science at the University of Osnabrück in the summer term 2016.

## TensorFlow Installation

For full up-to-date instructions checkout [tensorflow.org](https://tensorflow.org). This here is no more than a quick start guide.

TensorFlow currently (version 0.8.x) is **not available for Windows**. There are some hacky ways to get it running, but those are not in the scope of this intro -- sorry.

  * Install [Python 3.x.x](https://www.python.org/downloads/). It is probably available in your favorite package manager.
  * Depending on your system, run the following command(s):
    * Linux: (the `pip3` command probably needs root/`sudo`)
      
      ```sh
      $ curl https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp34-cp34m-linux_x86_64.whl -o tensorflow-0.8.0-py3-none-any.whl
      $ pip3 install --upgrade tensorflow-0.8.0-py3-none-any.whl
      ```
      
    * Mac OS X:
    
      ```sh
      $ pip3 install --upgrade https://storage.googleapis.com/tensorflow/mac/tensorflow-0.8.0-py3-none-any.whl
      ```
      
  * You are good to go!
