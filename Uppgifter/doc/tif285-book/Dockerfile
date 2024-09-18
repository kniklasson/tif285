FROM registry.gitlab.com/islandoftex/images/texlive:latest
RUN \
  apt-get update && \
  apt-get install -qy python3-pip && \
  pip install -U \
      jupyter-book \
      jupytext \
      sphinx-proof \
      sphinx-inline-tabs \ 
      sphinx-exercise --break-system-packages && \
  pip install -U \
      emcee \
      corner \
      gpy \
      gpyopt \
      matplotlib \
      numpy \
      tensorflow \
      scikit-learn \
      seaborn \
      pandas \
      scipy --break-system-packages
