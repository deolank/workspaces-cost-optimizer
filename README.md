PROJECT NOTES
-------------
# We have 4 python files for the engine

source/engine/wco.py - depends on source/engine/lib/directory_reader.py
source/engine/lib/directory_reader.py depends on workspaces_helper
source/engine/lib/workspaces_helper.py depends on metrics_helper
source/engine/lib/metrics_helper.py

# We have 1 python file for the scheduler, just lambda create task

source/scheduler/create-task.py
