workbench_moderation_keep_author_after_suppervisor_modification_fix
===================================================================

It fixes a problem with workbench_moderation module from drupal. The problem happens when a pubisher modify a node created by a creator i changes the state of the node to draft. The creator looses is not the owner anymore, it is the publisher instead.

It is extracted from:

http://drupal.stackexchange.com/questions/45114/assigning-revision-owner-when-moderating-backwards-with-workbench
