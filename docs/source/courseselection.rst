Course/subject selection
========================

At the top, the user, host url, login date, and working mode (onlines vs. offlines) are displayed. The **Logout** button allows you to return to the previous login window, closing the current one.

The main area shows the list of courses (or subjects) in which the current user is registered. It is possible to select one of them, to carry out the data loading and to access the following screen. The subjects are presented in alphabetical order in tabs as follows:

* **Recent**: courses recently accessed by the user.
* **Highlighted**: courses highlighted by the user.
* **All**: complete set of courses in which the user is enrolled.
* **In progress**: current course, with start and end date including the current date.
* **Futures**: courses to be taken, with a start date later than the current date.
* **Past**: courses already completed, with an end date prior to the current date.

*Note*: it is the user's responsibility to classify the courses as *highlighted* (and even *hidden*) in their *Dashboard* of Moodle. The start and end dates of each course are customized in *Edit Settings* for each subject.

.. figure:: images/Seleccion_de_curso.png
  :width: 400
  :alt: Course/suject selection in first access
  :align: center
  
  Course/suject selection in first access

The first time a course is selected the text **Last local update** will be displayed and the option to **Update data** is checked by default to force the download of data from the server. 

Additionally the **advanced option** of downloading **Web logs only** is left if you want to download only logs from the browser (ignoring client, *web service*, *restore* or unclassified logs). By default it is unchecked and only recommended for advanced users.

We press the button **Enter** to start the download. This data download process may **take several minutes for the first download** (depending on the number of students, size of the gradebook, number of new logs and activities with active completion tracking). 

A progress bar will be displayed at the bottom indicating the stages completed (uploading of the gradebook, downloading of activity completion, downloading of the log and parsing of logs). **Further updates will be shorter**, as the log loading is incremental, although the gradebook and activity completion is always fully updated.

On the other hand, it is **VERY IMPORTANT** that the percentage information is visible in the gradebook configuration (by default it is visible in Moodle) for correct reading and subsequent display of the grades.

Once the download is finished, the main window of the application will be shown.

Updating data
-------------

In subsequent accesses to previously loaded courses, the date of **Last local update** will already be shown and the option to mark, or not, the option **Update data** will be given.  

If we want to force the update of data with the current content of the server, we must mark this option manually. Otherwise, the data from the local cache (which might be outdated) will be loaded and displayed.

.. figure:: images/Seleccion_de_curso_recargar_asignatura.png
  :width: 400
  :alt: Course selection by reloading
  :align: center

  Subsequent access to previously loaded course
  
Cache cleaning
--------------

By selecting a previously loaded subject, the **Clean** button will be activated. This button allows us to clear the local cache of our current UBUMonitor installation.

.. figure:: images/Boton_limpiar.png
  :width: 100
  :alt: Cache cleaning
  :align: center

  Cache cleaning


When the cache disappears, the subject is detected as not previously loaded, always forcing the use of the **Update data** option in the next subsequent access. 


This option is useful to delete files of subjects that are no longer going to be accessed in the future or when the installed version of UBUMonitor detects problems with the local file version and it is necessary to delete it (see Sec. :ref:`errormessages`).


Offline mode
------------

If we have selected access in **Offline mode** only the subjects available in the local cache will be shown, in the *Local files* tab. In this mode it is not possible to update data, but it is possible to access the full data display functionality.

.. figure:: images/Seleccion_de_curso_offline.png
  :width: 400
  :alt: Offline course/subject selection
  :align: center
  
  Offline course/subject selection

  
Password changed
----------------

In the case that the Moodle password has been changed recently, a pop-up window is displayed, indicating that a change has been detected and asking for the previous password, which was held on the date indicated.

.. figure:: images/password_antiguo.png
  :width: 400
  :alt: Password changed
  :align: center
  
  Password changed
  
When the old password has been successfully entered, the local cached file is encrypted and saved with the new password. This is **required**, because the information is **always encrypted**.

**VERY IMPORTANT**: It is necessary to remember the previous password, in order to recover the data. If not, the cache must be cleared (**Clean** button), to force the courses to be reloaded.