# When (*when-command*)

**When** is a configurable user task scheduler for modern Gnome environments. It interacts with the user through a GUI, where the user can define tasks and conditions, as well as relationships of causality that bind conditions to tasks.

![Screenshot](https://raw.githubusercontent.com/almostearthling/when-command-docs/master/_static/when_screenshot_part.png)

The purpose of this small utility is to provide the user, possibly without administrative credentials, the ability to define conditions that do not only depend on time, but also on particular states of the session, result of commands run in a shell or other events that may occur when the system is being used. The scheduler runs in the background, and displays an indicator applet icon for user interaction.

It is not generally intended as a replacement to [*cron*](https://en.wikipedia.org/wiki/Cron) and the [Gnome Task Scheduler](http://gnome-schedule.sourceforge.net/), although to some extent these utilities might overlap. **When** is intended to be more flexible, although less precise, and to provide an alternative to more complicated solutions -- such as the implementation of *cron* jobs that check for a particular condition and execute commands when the condition is verified. In such spirit, **When** is not as fine-grained in terms of doing things on a strict time schedule: the **When** approach is that "*when* a certain condition is met, *then* something has to be done". The condition is checked periodically, and the "countermeasure" is taken *subsequently* -- although not *immediately* in most cases.

[![Documentation Status](https://readthedocs.org/projects/when-documentation/badge/?version=latest)](http://when-documentation.readthedocs.org/en/latest/?badge=latest)

The complete documentation for **When** can be found online [here](http://when-documentation.readthedocs.org/).


## Credits

Open Source Software relies on collaboration, and I'm more than happy to receive help from other developers. Here I'll list the main contributions.

* Adolfo Jayme-Barrientos, aka [fitojb](https://github.com/fitojb), for the Spanish translation

Also, I'd like to thank everyone who contributes to the development of **When** by commenting, filing bugs, suggesting features and testing. Every kind of help is welcome.

The top panel icons and the emblems used in the application were selected within Google's [Material Design](https://materialdesignicons.com/) icon collection.

Application [icon](http://www.graphicsfuel.com/2012/08/alarm-clock-icon-psd/) by Rafi at [GraphicsFuel](http://www.graphicsfuel.com/).


## Resources

The resources that I have found particularly useful in the development of **When** are:

* [Python 3.x Documentation](https://docs.python.org/3/)
* [PyGTK 3.x Tutorial](http://python-gtk-3-tutorial.readthedocs.org/en/latest/index.html)
* [PyGTK 2.x Documentation](https://developer.gnome.org/pygtk/stable/)
* [PyGObject Documentation](https://developer.gnome.org/pygobject/stable/)
* [GTK 3.0 Documentation](http://lazka.github.io/pgi-docs/Gtk-3.0/index.html)
* [DBus Documentation](http://www.freedesktop.org/wiki/Software/dbus/)
* [pyinotify Documentation](https://github.com/seb-m/pyinotify/wiki)

The guidelines specified in [UnityLaunchersAndDesktopFiles](https://help.ubuntu.com/community/UnityLaunchersAndDesktopFiles) have been roughly followed to create the launcher from within the application.

Many hints taken on [StackOverflow](http://stackoverflow.com/) and the like.
