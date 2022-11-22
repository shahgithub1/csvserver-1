# Steps to run the csvserver application on your machine

1. Install docker on your machine and run the following command
 
     docker pull infracloudio/csvserver:latest

2. Run the script "gencsv.sh" to generate the inputFile. 

3. Run the following command to make sure that the generated file is readable by other users 

   chmod 744 inputFile

3. Run the docker run command from part-1-cmd file

4. Run " docker ps -a "  and check the container status ( Make sure the container status is UP )

5. The application should be accessible at http://localhost:9393, it should have the 10 entries from inputFile and the welcome note should have an orange color border.


Note - If you using Windows Machine you can try this in WSL-2 or install GNU/Linux (i.e. Ubuntu) in a virtual machine



    
    