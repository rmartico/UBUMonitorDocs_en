Frequently Asked Questions
==========================

**Can I accidentally change or delete data in my courses when using UBUMonitor?**

No. This application only reads data from the server and **does NOT modify any data**, therefore there is NO risk in using it.

**Can I run UBUMonitor without a network connection?**

Yes, from version *2.6.1-stable* it is allowed to work in offline mode with previously loaded subjects.

**Can I have several versions of UBUMonitor installed on the same computer?**

Yes, you can have as many installations as you want, since each one goes in its own directory, without affecting the other versions. 

**Can I delete the data cache?**

Yes, you can delete the cache directory manually from the operating system or by using the "Clear" button available in the course selection window. 

**How can I uninstall UBUMonitor?**

Simply by deleting the directory where the application is installed. Note that this deletes ALL local files and downloaded data, but has no effect on the original data on the server.

**Are we using any data that we should not legally have access to in Moodle?**

No. UBUMonitor only reads data that the current user has permission to read. All data used is the same as that available in Moodle. UBUMonitor simply extracts, cleans and sorts that data to make it easier to filter and improve its display.

**If I run UBUMonitor on a third party computer, should I uninstall the application when I am done?**

This is only necessary if you have used the **export** options. If you export graphics in ``.png`` format or data in ``.csv`` format you should be aware that this data is **NOT encrypted**. In this case, it is advisable to delete those files that have been exported.

**Can I run UBUMonitor from a USB stick?**

Yes, as long as you use a portable version, or you have Java 8 installed with JavaFX on the computer where the USB stick is connected.

**With some subjects an error is generated when loading the data.**

If we don't have a teacher role, we won't have enough permissions to read the data and UBUMonitor generates an error. Check that you really are a teacher of that course.

**The application works, but it doesn't scale and resize the charts correctly, why?**

Check that the application is running with a **Java 8 version that includes the JavaFX libraries**. To check the current version, you can open an operating system console and execute $> java -version. The current number of installed version will be shown. With higher versions (e.g. Java 11 or higher) it has been detected that the graph display is not correct. Remember that the free versions (e.g. OpenJDK) will not work either because they do not include JavaFX.