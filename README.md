# ca-experiments
experiments with cellular automata

You'll need the following packages: pytorch, opencv, gtk2, tqdm, numpy and scipy, jupyter. I recommend you to install them using the Anaconda python distribution.

Personally, I use the Miniconda distribution available here: https://conda.io/miniconda.html. To install the packages after miniconda is installed I ran the following commands:

    conda install numpy scipy jupyter tqdm
    conda install gtk2 opencv -c conda-forge
    conda install pytorch -c pytorch

Optionally, if you have an NVIDIA graphics card, you can try to install pytorch with

    conda install pytorch cuda90 cudnn -c pytorch

If you have any questions, don't hesitate to write a message.
