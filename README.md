# Food-Ordering-WebApp
Pull the code to your local machine. 
Download and install git bash from here : https://git-scm.com/downloads 
Go to https://nodejs.org/en/ and download the stable version of nodejs. Install it on your local machine. Do customize the installation path and install it in the same folder where the code is pulled. 

Download mongodb from here : https://www.mongodb.org/ and install. 
You can install mongodb anywhere and not necessarily in the same folder where nodejs was installed. 
Once installed, create a directory named "data" in the folder where mongodb is installed and then create the directory "db" isnide "data" directory.

Open git bash and navigate to the directory where code is pulled on your local machine Install the following dependencies

- npm install mongojs
- npm install body-parser

Once all dependencies are installed, type "node server" in the git bash window; you should see the follwoing message :
- Server running on port 3000

If instead of this message any other error came regarding package not installed, no need to panic. Just copy the name of the package and follow the same process by typing :
- npm install package-name

Once all packages are installed you should see the required message.

After that go to the browser and type localhost:3000

Now you can use the web app as an operation team user or as a customer
