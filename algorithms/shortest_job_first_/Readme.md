# Shortest Job First

Here, the matrix showing the round trip service time of all the UAVs is used first.<br><br>
We first find out the total time required if all the UAVs are sent to every battle cluster. We maintian a new array to keep a note of the time required for every battle cluster.<br><br>
Now, we sort the new array (which is keeping note of the time required) to have the battle cluster taking the shortest time being executed first.<br><br>
The loop goes on untill all the battle clusters have been addressed.<br><br>
The custom order of addressing the battle clusters have also been provided in the output.
