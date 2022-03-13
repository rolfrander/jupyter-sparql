FROM jupyter/minimal-notebook:b418b67c225b

USER root

USER ${NB_UID}
RUN pip install sparqlkernel
RUN jupyter sparqlkernel install --user jovyan
