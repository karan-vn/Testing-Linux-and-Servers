# Testing-Linux-and-Servers
This repository is made for practice assignment made for HeroVired

# Instructions to be followed for Task 1

#===============================================================================

# To install htop

sudo apt update
sudo apt install htop -y

#================================================================================

# TO verify installation 

htop

# A prompt will open on the screen showing all the system information

#===================================================================================

# To make the script executable (need to use this command so that you can use the script)

chmod +x system_monitor.sh

#====================================================================================

# To run the script

./system_monitor.sh

#=====================================================================================

# TO check the generated logs 

cat system_metrics.log

#or

cat ~/monitoring_logs/system_report.log

#======================================================================================
