FROM jupyter/base-notebook
RUN pip install pandas sklearn matplotlib seaborn
ENTRYPOINT ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root", "--NotebookApp.token=Zsani"]