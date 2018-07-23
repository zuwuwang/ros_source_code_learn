^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package collada_parser
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

1.11.14 (2017-05-04)
--------------------
* Moved to new repository

1.11.13 (2017-03-27)
--------------------
* Use urdf::*ShredPtr instead of boost::shared_ptr (`#144 <https://github.com/ros/robot_model/issues/144>`_)
* add Chris and Shane as maintainers (`#185 <https://github.com/ros/robot_model/issues/185>`_)
* Contributors: Jochen Sprickerhof, William Woodall

1.11.12 (2017-01-04)
--------------------

1.11.11 (2016-06-10)
--------------------

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

1.11.6 (2014-11-30)
-------------------
* fix rotation of joint axis when oriantation between parent link and child link is differ
* Contributors: YoheiKakiuchi

1.11.5 (2014-07-24)
-------------------

1.11.4 (2014-07-07)
-------------------
* collada_parser: add extract actuators, fix for using nominal torque
* moving to new dependency for urdfdom and urdfdom_headers. https://github.com/ros/rosdistro/issues/4633
* Contributors: Tully Foote, YoheiKakiuchi

1.11.3 (2014-06-24)
-------------------
* update usage of urdfdom_headers for indigo/trusty
* Contributors: William Woodall

1.11.2 (2014-03-22)
-------------------

1.11.1 (2014-03-20)
-------------------
* remove visual and collision if there is no vertices
* do not use visual and collision group
* fix debug message
* fix problem of root coordinates
* Contributors: YoheiKakiuchi

1.11.0 (2014-02-21)
-------------------
* fix, joint axis should be rotated depend on local coords
* fix overwriting velocity limit
* Contributors: YoheiKakiuchi

1.10.18 (2013-12-04)
--------------------
* add DEPENDS for kdl_parser
* Contributors: Ioan Sucan

1.10.16 (2013-11-18)
--------------------
* fix for using collada_parser_plugin

1.10.15 (2013-08-17)
--------------------
