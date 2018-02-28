# Change Log

## v1.1.13
- Revised ACLs on Tables
  - Added Delete ACL for "x_ris_rightscale_c.app_role" on table "x_ris_rightscale_c_inbound_executions".
  - Added Delete ACL is missing on table "x_ris_rightscale_c_servers_web"
  - Added Create, read, write and delete ACLs for "x_ris_rightscale_c.app_role" on table "x_ris_rightscale_c_inbound_server_arrays"
  - Added Create, read, write and delete ACLs for "x_ris_rightscale_c.app_role" on table "x_ris_rightscale_c_inbound_instances"
  - Added Delete ACL for "x_ris_rightscale_c.app_role" on table "x_ris_rightscale_c_inbound_deployments"
  - Added Read ACL for "x_ris_rightscale_c.user" on table "x_ris_rightscale_c_servers_web"
- Revised Roles on UI Actions
  - Added "x_ris_rightscale_c.app_role" role to "Update Applications"
  - Added "x_ris_rightscale_c.app_role" role to "Update Servers"
  - Added "x_ris_rightscale_c.app_role" role to "Update Executions"
  - Added "x_ris_rightscale_c.app_role" role to "Update ServerArrays"
  - Added "x_ris_rightscale_c.app_role" role to "Update Deployments"
  - Added "x_ris_rightscale_c.app_role" role to "Update Instances"
- Revised Inbound Applications TransformMap
  - Updated choice action from "Create" to "Ignore"

## v1.1.12
Adds "outputs" field to the Executions resources in the Executions staging table.
Tested in ServiceNow releases:
- TBD

## v1.1.11
Original integration.
Tested in ServiceNow releases:
- Geneva
- Helsinki
Partially Tested in ServiceNow releases:
- Istanbul
