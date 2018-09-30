### addNewCmd ###

# Description
  This script is to add a given directory path to the environment variavble
  $PATH and add a new command file to the directory so that a user can use
  the command on the Terminal.

# Usage
  This script requires 1 mandarory argument and 2 optional arguments.
  $ addNewCmd <cmd_name> <option: dir_path> <option: dir_name>
  
  cmd_name: The name of the command to be added.
  dir_path: The absolute path of the directory where a new command is added.
  	    The default path is </usr/local>.
  dir_name: The name of the directory where a new command is added.
            The directory will be created if it doesn't exist.
            The default directory name is <custom_command>.

# Install
  There are two ways to use this script.
  (1) Save the script file to any directory and run as ./createPages
  (2) Save the script file and add its path to $PATH. This can be done 
      using addNewCmd.

# Author
  tomokoji

# Date
  30 September 2018
