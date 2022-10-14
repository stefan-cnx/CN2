
1. Download the "device_serial.sh" file from the "https://github.com/stefan-cnx/CN2/" repository.\n
   To download: a. Click the file link and the file content will show
                b. Right-click the "Raw" button and select "Save link as...".
                c. The "Save As" dialog window will open.
                d. Select a folder that you want to use for downloading the file.
                e. Click "Save" to download the file.
2. Change the permissions of this file to allow execution.
   To change: a. Open Terminal: "Raspbian's start menu" => "Accessories" => "Terminal".
              b. Navigate to the folder of the downloaded file, e.g. type "cd Downloads".
              c. List directory content and check file permissions, e.g. type "ls -al".
                 Note the colour coding of the different files and directories.
              d. Change permissions for the file, e.g. type "sudo chmod +x device_serial.sh".
              e. Check that file permissions have been changed, e.g. type "ls -al".
                 Observe and check if the colour coding for "device_serial.sh" has changed?
3. Run the script to create a new file with a file name starting 'Device_Serial_'.
   To run: a. Type "sudo ./device_serial.sh".
           b. List directory content and check for new file, e.g. type "ls -al".
           c. Note the colour coding of the different files and directories.
4. Upload this file to your private repository.
5. Review: a. Was the file with a file name starting with 'Device_Serial_' created?
           b. Do you understand the file permissions, e.g. "-rwxr-xr-x"?
           c. Can you see the file content of the file name starting with 'Device_Serial_'?
              Type "cat" + " " + file name starting with 'Device_Serial_'.
           d. Review the CLI commands. Are there any commands that you are not sure about?
