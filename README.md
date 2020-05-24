# Betacoronavirus_localBLAST_jpynb
A tutorial to launch local Blast+ from Jupyter Notebook and compare sequences of SARS-nCoV-2 Spike protein gene to databases. 
Written by Katharina Wollenberg Valero 2020 as an educational resource for undergraduate students.
A friendly nod to https://github.com/davelunt, whose tutorial I couldn't get to work.

### Setting up the Jupyter Notebook via docker and cloning the github repository
On your computer, make sure `Docker desktop` is running by checking the "show hidden icons" menu at the bottom right of your toolbar
Open a command line terminal and make sure no docker images are running with `docker ps`. If there is still a running image, terminate it with `docker stop XXXXX` where XXX is the ID of the image as seen in the `docker ps` output.   
Check whether you still have the Jupyter Notebook docker image installed with `docker images`. If not, pull it with `docker pull jupyter/datascience-notebook`. But it should still be on your machine. 
Run the image with `docker run -t --rm --name ds -p 8888:8888 jupyter/datascience-notebook`.
Open a browser window and enter `localhost:8888`. In the Jupyter Hub start page, enter the `token` which you can copy from your terminal window. 
Now that you have started Jupyter Hub, clone this repository via the `clone or download` button. Open a terminal in Jupyter Notebook and enter `git clone https://github.com/cybokat/Betacoronavirus_localBLAST_jpynb.git`. The notebook as well as some files should appear in the main directory of Jupyter Hub. Open the Jupyter Notebook and follow the instructions within. 
