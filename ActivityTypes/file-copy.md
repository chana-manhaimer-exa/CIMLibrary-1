file-copy
=========

Description
-----------
A file was copied

The possible fields for this activity type will vary depending on whether the activity was a [success](#file-copysuccess) or a [fail](#file-copyfail).

| Parameter     | Value     |
| ------------- | --------- |
| Subject       | file      |
| Activity      | copy      |
| Activity Type | file-copy |
| Pretty Name   | File Copy |
| Legacy Name   |           |

file-copy:success
-----------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| src_file_name |      | &#10003;  |               |
| src_file_ext  |      | &#10003;  |               |
| src_file_dir  |      |           | &#10003;      |
| src_file_path |      | &#10003;  |               |

file-copy:fail
--------------

| Field         | Core | Detection | Informational |
| ------------- | ---- | --------- | ------------- |
| src_file_name |      | &#10003;  |               |
| src_file_ext  |      | &#10003;  |               |
| src_file_dir  |      |           | &#10003;      |
| src_file_path |      | &#10003;  |               |