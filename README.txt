This webapp interface allows a user to do manual review and
give feedback at a high level while ensuring that

* feedback is standardized, which is required to automate
  the merge/unmerge process
* all needed feedback is collected, which is invaluable
  for creating training sets and evaluating performance
* the feedback can immediately be used to update the
  database to fix any FPs or FNs, without needing to
  write any code

The advantages of this are:

* Allows all people with the knowledge actually required
  (native-level knowledge of American
  names/nicknames/conventions, streets, etc.) to do this
  important but tedious task, rather than needing 
  people with technical skills to regularly commit time
  to it.
* Even for someone with technical skills, using this
  interface is a more robust way to do the task. Writing
  your own update and editing it for every case is
  dangerously error-prone, as is designing a process that
  relies on the reviewer to record their feedback according
  to specifications that they can easily violate.
* Saves time and mental energy better used elsewhere. 
  The interface guides the user on what they need to do so
  training time for how to do manual review is minimal. 
  This also allows the reviewer to focus on the actual task
  rather than on the minutiae of how they are recording 
  their feedback.
* Creates an audit trail of who reviewed/updated what and when.
