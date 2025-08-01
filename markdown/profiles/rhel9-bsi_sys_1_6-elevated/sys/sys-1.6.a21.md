---
x-trestle-global:
  profile:
    title: rhel9-bsi_sys_1_6-elevated
  sort-id: sys-01.06.a21
---

# sys-1.6.a21 - \[REPLACE_ME\] Extended Security Policies

## Control Statement

(1) Extended policies SHOULD restrict the permissions of containers. (2) Mandatory Access Control (MAC) or a comparable technology SHOULD enforce these policies. (3) At minimum, policies SHOULD restrict the following types of access: • Incoming and outgoing network connections • File system access attempts • Kernel requests (syscalls) (4) A runtime SHOULD start containers in such a way that the kernel of the host system prevents all activities of the containers that are not allowed by the relevant policy (e.g. by setting up local packet filters or revoking permissions), or at least reports violations appropriately.

# Editable Content

<!-- Make additions and edits below -->
<!-- The above represents the contents of the control as received by the profile, prior to additions. -->
<!-- If the profile makes additions to the control, they will appear below. -->
<!-- The above markdown may not be edited but you may edit the content below, and/or introduce new additions to be made by the profile. -->
<!-- If there is a yaml header at the top, parameter values may be edited. Use --set-parameters to incorporate the changes during assembly. -->
<!-- The content here will then replace what is in the profile for this control, after running profile-assemble. -->
<!-- The current profile has no added parts for this control, but you may add new ones here. -->
<!-- Each addition must have a heading either of the form ## Control my_addition_name -->
<!-- or ## Part a. (where the a. refers to one of the control statement labels.) -->
<!-- "## Control" parts are new parts added after the statement part. -->
<!-- "## Part" parts are new parts added into the top-level statement part with that label. -->
<!-- Subparts may be added with nested hash levels of the form ### My Subpart Name -->
<!-- underneath the parent ## Control or ## Part being added -->
<!-- See https://oscal-compass.github.io/compliance-trestle/tutorials/ssp_profile_catalog_authoring/ssp_profile_catalog_authoring for guidance. -->
