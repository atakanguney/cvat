---
title: 'Tasks page'
linkTitle: 'Tasks page'
weight: 2.5
description: 'Overview of the Tasks page.'
---

![](/images/image006_detrac.jpg)

The tasks page contains elements and each of them relates to a separate task. They are sorted in creation order.
Each element contains: task name, preview, progress bar, button `Open`, and menu `Actions`.
Each button is responsible for a in menu `Actions` specific function:

- `Export task dataset` — download annotations or annotations and images in a specific format.
  More information is available in the [Downloading annotations](/docs/manual/advanced/downloading-annotations/)
  section.
- `Upload annotation` is available in the same formats as in `Export task dataset`. The
  [CVAT](/docs/manual/advanced/xml_format/) format accepts both video and image sub-formats.
- `Automatic Annotation` — automatic annotation with OpenVINO toolkit.
  Presence depends on how you build CVAT instance.
- `Export task` — Export a task into a zip archive.
  Read more in the [export/import a task](/docs/manual/advanced/export-import/) section.
- `Move to project` — Moving the task to the project (can be used to move a task from one project to another).
  Note that attributes reset during the moving process. In case of label mismatch,
  you can create or delete necessary labels in the project/task.
  Some task labels can be matched with the target project labels.
- `Delete` — delete task.

---

Push `Open` button to go to [task details](/docs/manual/basics/task-details/).
