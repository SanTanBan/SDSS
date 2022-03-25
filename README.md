#Comparison

I have merged the two programs into a single one so that it may be used for comparison.

Please create a "New Folder" and keep the "Comparison.py" Python Program File and the "Input Data.xlsx" Excel file  into that folder.

Allow the program to run as long as possible. After you terminate the program, you will see the "Comparison Table" in the "New Folder" as well as a new Images Folder is created where the images are captioned accordingly. The "Images" Folder will have multiple folders numbered according to the number of Nodes used.

The more time the program is run, the more number of such folders will be created automatically for comparison.
To change the Number of Nodes to be evaluated for the comparison; line Number 30 may be altered

$$$for num_of_Nodes in range(1,15):$$$
#Here 15 denotes the Number of Nodes which will be considered for both the Formiulation Types. Since in Python range(), upto first 14 Nodes will be considered

$$$for num_of_Nodes in range(10,14):$$$
#This will generate the Comparison Output for Nodes 10 to 13 alongwith the table and Images


For this Comparison the same netowrk is used for all the different vehicle types, i.e. all the Vehicle_Types (which contain 1 Vehicle as per the data from the Paper) is using the same network with Euclidean Distances.
This may be changed in the Program by changing the Input which is commented out presently.
