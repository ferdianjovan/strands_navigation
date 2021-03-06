^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package message_store_map_switcher
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.6 (2014-11-06)
------------------

0.0.5 (2014-11-05)
------------------
* Adding licences and bug fix
* Contributors: Jaime Pulido Fentanes

0.0.4 (2014-10-30)
------------------
* Lowering acceptable yaml version.
* Robustifying cmake file.
* Standardising python parts based on catkin docs.
* Standardising python parts based on catkin docs.
* Fixed build for Indigo
* Contributors: Nick Hawes

0.0.3 (2014-10-29)
------------------

0.0.2 (2014-10-29)
------------------
* 0.0.1
* added changelogs
* deleting comment
* Merge branch 'hydro-devel' of https://github.com/strands-project/strands_navigation into hydro-devel
  Conflicts:
  message_store_map_switcher/CMakeLists.txt
* removing more mongodb_store_cpp_client references
* removing message_store_cpp_client from message_store_map_switcher
* adding mongodb_store to message_store_map_switcher dependencies
* removing mongodb_store_cpp_client from message_store_map_switcher
* Renamed ros_datacentre to mongodb_store
  This simply bulk replaces all ros_datacentre strings to mongodb_store strings inside files and also in file names.
  Needs `strands-project/ros_datacentre#76 <https://github.com/strands-project/ros_datacentre/issues/76>`_ to be merged first.
* Added definition for new cxx features.
* swapping  target link libraries to correct compilation error
* Fixed to use correct query options. Damn untyped language.
* Now using the new updateNamed method to ensure we don't get lots of maps in the database.
* More docs
* Adding basic usage docs.
* Added switching service with return for success/fail. Tested and working on two maps in rviz.
* Added server node.
* Added saving to db.
* Added loading of map from file based on map_server code.
* Contributors: Bruno Lacerda, Jaime Pulido Fentanes, Marc Hanheide, Nick Hawes
