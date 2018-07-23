^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package joint_state_publisher
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.11.15 (2017-09-15)
--------------------
* Added forward declaration for recent versions of urdfdom (`#217 <https://github.com/ros/robot_model/pull/217>`_)
* pcrecpp is no longer a dependency (`#216 <https://github.com/ros/robot_model/pull/216>`_)
* Contributors: Chris Lalancette, Michael Görner

1.11.14 (2017-08-14)
--------------------

1.11.13 (2017-03-27)
--------------------
* [joint_state_publisher] Handle time moving backwards
  Without this patch, joint_state_publisher dies whenever the ROS time moves backwards (e.g., when running `rosbag play --clock --loop`).
* Switch a couple more packages over to Chris and Shane.
* Contributors: Chris Lalancette, Martin Günther

1.11.12 (2017-01-04)
--------------------

1.11.11 (2016-06-10)
--------------------
* scroll joint_state_publisher if there are too many joints (`#137 <https://github.com/ros/robot_model//issues/137>`_)
* Contributors: v4hn

1.11.10 (2016-02-23)
--------------------

1.11.9 (2016-02-22)
-------------------
* Add Jackie as a maintainer
* Contributors: Jackie Kay

1.11.8 (2015-09-11)
-------------------

1.11.7 (2015-04-22)
-------------------
* Added a randomize button for the joints.
* Contributors: Aaron Blasdel

1.11.6 (2014-11-30)
-------------------
* Added floating joints to joint types ignored by publisher
* warn when joints have no limits
* add queue_size for publisher
* Contributors: Jihoon Lee, Michael Ferguson, Shaun Edwards

1.11.5 (2014-07-24)
-------------------

1.11.4 (2014-07-07)
-------------------
* Update package.xml
  Updating author and maintainer email for consistency
* Contributors: David Lu!!

1.11.3 (2014-06-24)
-------------------

1.11.2 (2014-03-22)
-------------------

1.11.1 (2014-03-20)
-------------------

1.11.0 (2014-02-21)
-------------------
* Use #!/usr/bin/env python for systems with multiple Python versions.
* Contributors: Benjamin Chretien

1.10.18 (2013-12-04)
--------------------

1.10.16 (2013-11-18)
--------------------

1.10.15 (2013-08-17)
--------------------

* joint_state_publisher: do not install script to global bin
  Also clean up no longer required setup.py
