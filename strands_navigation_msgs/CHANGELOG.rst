^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package strands_navigation_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.6 (2014-11-06)
------------------

0.0.5 (2014-11-05)
------------------
* Adding licences and bug fix
* Removed topological_utils dependency.
* Moved Vertex and Edge into strands_navigation_msgs.
  Basic test for travel_time_tester passes.
* Merge topological_navigation and topological_map_manager packages.
  Added the EstimateTravelTime service to provide a clean way of getting travel times of the topological map.
* added service definitions for adding and removing monitor and help states to the overall monitored nav state machine
* Contributors: Bruno Lacerda, Jaime Pulido Fentanes, Nick Hawes

0.0.4 (2014-10-30)
------------------

0.0.3 (2014-10-29)
------------------
* moving human_help_manager service definition to human_help_manager package
* Contributors: Bruno Lacerda

0.0.2 (2014-10-29)
------------------
* 0.0.1
* added changelogs
* Removing TopologicalMap.msg as it may create conflicts with other pull requests
* Adding Missing TopologicalMap.msg and changing maintainer emails, names and Licences for Packages
* Moving and renaming Execute Policy Action
* taking out distinction between local and global plan failure
  first steps to make monitored_nav scitos independent
  always oututs after help
  new action definition
  less management of new goals arriving during execution, as it was buggy
* Fixes bugs created by name changes of mongodb_store and moving packages between repositories
* moving strands_navigation_msgs to strands_navigation
* Contributors: Bruno Lacerda, Jaime Pulido Fentanes, Marc Hanheide
