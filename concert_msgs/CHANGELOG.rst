^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package concert_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.6.3 (forthcoming)
-------------------

* Next iteration of role manager messages and services (`#26`_).

0.6.3 (2013-10-30)
------------------
* added a service name to uniquely separate same services in a solution.
* role manager messages, closes `#24 <https://github.com/robotics-in-concert/rocon_msgs/issues/24>`_
* rocon_std_msgs centralises some app manager messages for sharing.

0.6.2 (2013-09-11)
------------------

0.6.1 (2013-08-30)
------------------

0.6.0 (2013-08-07 18:58)
------------------------
* 0.5.2
* remove unused zeroconf_msgs dependency.
* 0.5.1
* 0.5.0
* AppDescription->App

0.5.3 (2013-08-07 19:04)
------------------------

0.5.2 (2013-07-17)
------------------
* remove unused zeroconf_msgs dependency.
* AppDescription->App

0.5.1 (2013-06-10 16:28:55 +0900)
---------------------------------
* 0.5.0
* proper dependency exporting for rocon msgs.

0.5.0 (2013-05-27)
------------------
* added forced matching parameter.
* min, max added to node parameters.
* splitting human friendly and gateway name identification.
* splitting human friendly and gateway name identification.
* 0.4.0

0.3.0 (2013-02-05)
------------------
* fix broken cmake for reshuffled messages.
* update jihoon email
* invitation now handled directly by the app manager.
* concert status -> app manager status, part of first redesign.
* platform info constants -> platform info msg.
* finished testing.
* testing pre-release with qt4 rosdep.
* Merge branch 'groovy-devel' of https://github.com/robotics-in-concert/rocon_msgs into groovy-devel
* testing pre-release with qt4 rosdep.

0.2.1 (2013-01-31)
------------------
* PlatformInfo msg GetPlatformInfo srv moved from concert to app manager. RemoteGatewayInfo srv typo
* platform info to rocon_app_manager_msgs
* merge zeroconfmsgs bugfix.
* refactoring app->rapp.
* bugfix typo in build_depend as well.
* bugfix typo in rosdep zeroconf_msgs.
* catkinized.

0.2.0 (2012-12-23 14:15:44)
---------------------------

0.1.4 (2012-12-23 14:15:23)
---------------------------
* simplified start solution.
* updates to the idea of implementation.
* ROBOT_ANY constant added.
* Link graph messages.
* concert client configuration updates for orchestration.
* reinstated apps into client information.
* concert clients and minor mod to platform info.
* starting the concert clients.
* Autoinvite no longer needed.
* remove quotes from the strings.
* platform info moved to concert msgs and eclipse project files.
* adding auto invitatin setting service

0.1.3 (2012-12-07)
------------------
* updated concert msgs
* conductor msgs
* more srvs
* updated srvs and msgs

0.1.2 (2012-11-22)
------------------
* missed a comms->msg update.
* migrate remaining packages from comms->msgs.

0.1.1 (2012-11-21)
------------------

0.1.0 (2012-03-29)
------------------

.. _`#26`: https://github.com/robotics-in-concert/rocon_msgs/pull/26
