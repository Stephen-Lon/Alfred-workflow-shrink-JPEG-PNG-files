# Alfred-workflow-shrink-jpg-png-files
# Introduction

This workflow, which works as a Universal Action both on a *single* selected JPEG or PNG file and on *multiple* selected JPEG or PNG files:

- saves each *original* image in a temporary folder specified in the User Configuration;
- offers two methods of resizing the dimensions of each selected image: *either* to the default longest side measurement specified in the User Configuration (measured in pixels) *or* by the default percentage reduction specified in the User Configuration.

**Note**:

- The workflow does *not* enlarge images that already have a shorter longer side than specified in the User Configuration.

- If you specify a default percentage in the User Configuration greater than 99 the workflow will produce an error message notifying you of that.

# Important note

If you use the default backup folder in the User Configuration the backup is to a temporary folder which is:
- automatically created if it does not exist; and
- *automatically deleted when your Mac restarts*.

*If you need to retrieve a backup you must move it from that default temporary folder before your Mac restarts*.

# Usage

Select a single JPEG or PNG file, or multiple JPEG or PNG files, in Finder, use your Universal Actions hotkey and choose `Shrink JPEG/PNG file(s)` to run the workflow.

Version 2.0 now enables you to set the default resizing method (by longest side or by percentage) so that if you use one of those methods regularly it is quicker to dismiss the dialogs simply by pressing <Enter>.
