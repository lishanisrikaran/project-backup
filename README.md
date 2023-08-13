# project-3

![image](https://github.com/lishanisrikaran/project-backup/assets/126973634/3c64b36c-ad38-4cea-a856-640677d10d2c)


The datasets used are available in geojson and json format, to access please follow the below steps:

1) If not already installed, open up your git bash terminal and type the following -
	<pip install flask>
	<pip install requests>
	<pip install jsonify>

2) Navigate to the file path where you want to clone this project's repository in git bash. Once done, type <git clone https://github.com/lishanisrikaran/project-3.git>.

3) Choose the directory which is two level inwards by typing <cd project-3/app> into your git bash terminal. 

4) Type <python -m venv .venv.>

4) Open up a new Anaconda Prompt terminal, cd into the directory which contains the file 'app_solution' and type the folowing:
	<.venv\Scripts\activate>
	<flask --app app_solution run>

5) Copy and paste the server link into your browser and you will then be shown each route of every raw data set used in this project. 


Due to cross-origin resource sharing restrictions, to gain visability of all visualisations within the index.html file, you will need to open this from within a python HTTP server, instructions below:

1) Navigate into the 'project-3' directory in your terminal. 

2) Type <python -m http.server>
