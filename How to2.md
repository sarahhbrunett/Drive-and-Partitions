# how to:
Partition a disk drive into 3 partitions in a few easy steps.

1. Start by opening your Virtual machine and logging in. (Use the Virtual machine you added your new vitual disk to in How to1)
2. Click your home button and search for the gparted app in the search box.
3. If it is not downloaded, open up a terminal on your computer.
4. Sign in to your root account.
5. Download gparted by typing : apt install gparted.
6. Type Y when asked to finalise download.
7. Run the gparted app once it is downloaded.
8. Select the newly created disk by selecting the drag dwon box on the top right side of the window.
9. Once selected, go into the device tab at the top of the window and select "create new partition table".
10. Select the wanted partiton table type.
11. Click Apply to create your partition table.
12. Click the partition tab at the top of the window and select "new".
13. The create a new partion window will appear.  Select the size you would like your partition to be.  Mine is 25599 MIB but i want to seperate it to 3 partitions.  Therefore i will have each partition at 8533MIB each.
14. Select the file system you would like. I will chose ntfs.
15. Enter all other information you would like.
16. Click Apply at the bottom of the window.
17. Repeat steps 14 to 19 twice more to create your two remaining partitions.
18. Finish off by clicking The green check mark at the top of the Gparted window to apply your changes.(VERY IMPORTANT)

You have now created and formated 3 partitions in your new drive!

https://www.geeksforgeeks.org/disk-partitioning-in-ubuntu-using-gparted/
