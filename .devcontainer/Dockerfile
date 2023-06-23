FROM tensorflow/tensorflow:latest-gpu-jupyter

RUN apt-get update && apt-get upgrade -y

RUN python --version && pip --version

RUN pip install numpy \
    pandas \
    scikit-learn \
    scikit-image \
    pillow \
    imbalanced-learn \
    matplotlib \
    statsmodels \
    seaborn \
    plotly