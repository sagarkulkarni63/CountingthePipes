# Tallying The Pipes





Companies manufacture, process, and sell steel pipes. Inventory management of pipes in an outside yard has long been a pain point for companies because of the labor-intensive, visual dependency required to check the number of pipes. A typical case of specifications of pipes and the environment of pipe yard are: 1.66 - 48 inch in diameter, 30-60 feet long, Stacked in 3 - 20 layers depending on Outside Diameter size (but not higher than approx. 10Feet). More than 1 thousand pipes in 1 acre. A tag and/or cap may be attached to the end of the tube. In the case of large diameter pipes, the pipe stacks are often several hundred meters long and the distance between the stacks is often so narrow that it can be difficult to take a picture from the front.





#solution:

Initially we record a place where pipes and rods are usually placed. Then we create an imaginary rectangle shape at the same space through a computer having the software downloaded and creating a maximum rectangle outline where maximum rods/pipes can be stacked. Now we know the total area in the space where all the pipes are stored. 
Before we start identifying or stacking the pipes, we create data for each pipe recognized/stored where it’s color, radius of the rod/pipe and outer shape (if irregular) to be already added in the database so that object identification would be easier and also calculate the face area of the rod/pipe which is the key to calculate the numbers. The difference between the storage outline area and each individual pipe/rod area then is used to calculate the maximum number of pipes that can be added within the outline of a specific pipe/rod type. 
Now when the pipes are being stored, the technology records and captures each pipe and rod that’s being added in the storage space. 
 
![image](https://user-images.githubusercontent.com/57354593/167240920-d63ef774-c011-4252-9b4a-63f54c02b88c.png)

Now create an algorithm using the CV technology where when each pipe/rod is being added, the pipes are being highlighted and then then area accumulated will be added as the pipes are being stacked. Once the pipes are being stacked, the total area unoccupied of the pipes will be removed from the maximum area that the imaginary outline storage space can store. Now we will be able to find the total number of pipes/rods by dividing the area with the approximate area of each pipe/rod in the storage.
Similarly with this process and more of trials and error rectifications, we can improve the precision and speed of the process and also increase the types of pipes with can also be stacked together and giving out the information of an already stacked pipe/rod section and the number of pipes stored.
