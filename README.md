# debian_balena_etcher

# Flashing a Debian Install using Balena Etcher

You can download all versions of Debian here: https://www.debian.org/CD/http-ftp/. Choose the correct CD version (e.g. arm, amd) under the header "Official CD/DVD images of the stable release."

Once this is downloaded to your computer, you will need to "flash" this to an external USB drive. To do this, you need another program. I recommend [Balena Etcher](https://etcher.balena.io/#download-etcher), which is widely used and easy to understand. 

Download and install Balena Etcher. Start the program. You will see the following screen:

![[balena_etcher copy.png]]

Click on **Flash from File** and point to the location where you have downloaded the Debian .iso file. 

Then, click on **Select target**. This will be your USB drive. Be sure you choose the correct drive so that you don't overwrite any files on your computer or peripherals. 

To start the process, click **Flash**. You will be prompted for a password. This is your administrator password. Note that if you are not the primary administrator on your Mac, you may get an error message. If this happens, you may need to use Balena Etcher from your administrator login. 

Your USB drive is now ready to install Debian on your computer. 
