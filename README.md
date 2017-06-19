# Empatica-Ledalab
Function to convert Empatica Connect generated CSV files into Ledalab Type 2 or 3 supported text files with timestamped events.

Note: This function is useless and will not do anything for you if you do not have tagged events. Tested with Empatica E4 only.

How to use:

1. Place the empatica2ledalab.m function where you can call it
2. Call empatica2ledalab.m using this syntax:

        empatica2ledalab(type)
        
        where type is either 2 or 3 and correspond to Ledalab type 2 and 3 text files.
                -Type 2 starts time at 0
                -Type 3 uses UNIX epoch time
                
3. Using the GUI, select the directory containing the unzipped empatica .CSV files
4. Enjoy your Ledalab compatible file named "reformated_data.csv" in the same directory as the other CSV files
