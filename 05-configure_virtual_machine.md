# Chapter 5: Configuring the Virtual Machine
In this chapter, you will configure your new virtual machine.  
[Click here for chapter 4](https://github.com/rubyonracetracks/tutorial-virtualbox/blob/master/04-create_virtual_machine.md)

## Procedure
* In the main screen of VirtualBox, select the "SparkyLinux" virtual machine, and click on "Settings" to configure your virtual machine.
* In the settings screen, click on "System".  Click on the "Processor" tab.  Set the number of processors to the upper end of the green range.  The "Execution Cap" should be set to 100%.  Toggle on the "Enable PAE/NX" setting.
* In the settings screen, click on "Display".  In the "Screen" tab, set the video memory to the maximum possible value allowed.  Toggle on the "Enable 3D Acceleration" setting.
* In the settings screen, click on "Storage".  Under "Controller/IDE", click on "Empty".  Click on the disc symbol and select "Choose Virtual Optical Disc File", and select the SparkyLinux ISO file that you downloaded earlier in this tutorial.  This is the virtual equivalent of inserting the SparkyLinux DVD into the DVD drive.
* If your host OS is Linux or Windows, click on "User Interface".  Toggle on the "Show at Top of Screen" setting.
* Click on "OK".  This updates the virtual machine settings.
* You should now be back in the main screen of VirtualBox.  Your virtual machine is now ready to boot up, which is the subject of the next chapter.
* [Click here for chapter 6](https://github.com/rubyonracetracks/tutorial-virtualbox/blob/master/06-boot_up_virtual_machine.md)
