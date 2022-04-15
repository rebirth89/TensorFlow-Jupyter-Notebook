# TensorFlow-Jupyter-Notebook-Sionna
TensorFlow GPU accelerated Jupyter Notebook that is able to run on WSL and any Linux OS.

Installation With Docker
--
1.) Ensure that Docker is installed on your system.

```sudo apt install docker.io```

2.) Ensure that your user is in the Docker group with correct permissions

```sudo usermod -aG docker $USER```

3.)  Pull Docker image to your system.

```docker pull hunari/tensorflow-jupyter-notebook:latest```

4.) Run Docker image on your system.

```docker run -p 8888:8888 hunari/tensorflow-jupyter-notebook:latest```
This will launch the Docker image on port 8888 for the Jupyter Notebook.
 
