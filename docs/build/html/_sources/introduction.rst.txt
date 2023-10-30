Introduction and requirements
=============================

UBUMonitor is a *desktop client application* that allows you to connect to a *Moodle server* to monitor the particular activity of the students. It allows to extract the data from the logs, gradebook and activity completion of our subjects, visualizing these data in a more friendly way for the teacher.

Installation requirements
-------------------------

* Windows, GNU/Linux or Mac operating system
* Have an Internet connection.
* Have a minimum of:

   * *250 MB free hard disk* for the portable version, which includes the Java Runtime Environment (JRE).
   * *26 MB free disk* if you already have Java 8 installed.

Requirements in Moodle
----------------------

* Required

   * Have a **teacher's account** in the subjects or courses you want to access.
   * Access Moodle with basic web validation through `http://` or `https://`. Currently **NO** support is included for *Single Sign-on* type systems.
   * Have activated in the Moodle server the **mobile support** (mobile apps). In case of an error when *login* from UBUMonitor, ask the Moodle server administrator for possible activation.

* Optional (for a better experience)

   * Set correctly (in **Edit settings** of the course), in **General**, the *Course start date* and *Course end date* (enabled) in your subjects. Otherwise, the initial course selection (in the *In Progress*, *Future* and *Past* tabs) and the date filters for the log charts **WILL NOT work correctly**.
   * Activate **show percentage** of the subject in the **Moodle gradebook**. Otherwise **NO data can be loaded from the gradebook**.
   * Activate in **Edit settings** of the course, in the section **Completion tracking** the option **Enable completion tracking**. Once this change has been made, it is recommended that you adjust the **Completion Tracking** option for each activity and resource in *Activity Completion*, if you want to use the corresponding table.
   * Have **defined groups in the subject** if you want to use the filters and particular charts on groups.