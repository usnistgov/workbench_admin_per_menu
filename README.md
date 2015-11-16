# workbench_admin_per_menu

##Synopsis

I am a module that provides Workbench access control for core drupal menus.

When enabled for specific roles via permissions, users will only be allowed to see, modify, and assign content to menus that are assigned to the same node of a taxonomy as they are via Workbench

This module only works with Workbench when Workbench is configured to use a taxonomy for content access.

## Installation / Setup

When installed go to the permissions screen and select which roles should have their menu access enforced by Workbench.

Other users (typically Administrators) should be give menu permissions normally provided by Drupal. If a role is both under this modules control AND assigned normal Drupal access the Drupal access takes precedence.

