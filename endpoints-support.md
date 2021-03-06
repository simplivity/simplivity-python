Refer SimpliVity REST API doc for the resource endpoints documentation [HPE SimpliVity REST API Documentation](https://developer.hpe.com/api/simplivity/).

<br />

## Supported resources and endpoints

| Endpoints                                                        | Action |
| ---------------------------------------------------------------- | ------ |
|     **Backups**
<<<<<<< HEAD
|<sub>/backups	</sub>                                                                    |GET       |
|<sub>/backups/delete  </sub>                                                             |POST      |
|<sub>/backups/{bkpId}  </sub>                                                            |DELETE    |
<<<<<<< HEAD
|<sub>/backups/{bkpId}/lock</sub>                                                            |POST    |
|<sub>/backups/{bkpId}/restore  </sub>                                                    |POST      |
|     **Cluster Groups**
|<sub>/cluster_groups  </sub>                                                             |GET       |
<<<<<<< HEAD
=======
|     **Cluster Groups**
|<sub>/cluster_groups  </sub>                                                             |POST      |
>>>>>>> add endpoint support for cluster_groups <POST>
=======
|<sub>/cluster_groups/{clusterGroupId}/rename  </sub>                                     |POST      |
>>>>>>> Add support for Cluster Group rename
=======
|<sub>/backups</sub>                                               |GET     |
|<sub>/backups/delete</sub>                                        |POST    |
|<sub>/backups/{bkpId}</sub>                                       |DELETE  |
|<sub>/backups/{bkpId}/restore</sub>                               |POST    |
|     **Cluster Groups**
|<sub>/cluster_groups</sub>                                        |GET     |
|<sub>/cluster_groups/{clusterGroupId}/rename</sub>                |POST    |
>>>>>>> clean up formatting of endpoints-support.md file
|     **Datastores**
|<sub>/datastores</sub>                                            |GET     |
|<sub>/datastores</sub>                                            |POST    |
|<sub>/datastores/{datastoreId}</sub>                              |DELETE  |
|<sub>/datastores/{datastoreId}/resize</sub>                       |POST    |
|<sub>/datastores/{datastoreId}/set_policy</sub>                   |POST    |
|     **Hosts**
<<<<<<< HEAD
|<sub>/hosts	</sub>                                                                    |GET       |
|<sub>/hosts/{hostId}/cancel_virtual_controller_shutdown </sub>                 	  |POST      |
|<sub>/hosts/{hostId}/remove_from_federation  </sub>						|POST      |
|<sub>/hosts/{hostId}/hardware  </sub>						          |GET      |
|<sub>/hosts/{hostId}/virtual_controller_shutdown_status  </sub>                          |GET      |
|<sub>/hosts/{hostId}/shutdown_virtual_controller </sub>                                  |POST     |
|     **OmniStack Clusters**
|<sub>/omnistack_clusters	</sub>                                                        |GET       |
|<sub>/omnistack_clusters/time_zone_list  </sub>                                          |GET       |
|<sub>/omnistack_clusters/{clusterId}/connected_clusters  </sub>                          |GET       |
|     **Policies**
|<sub>/policies	</sub>                                                                    |GET       |
|<sub>/policies</sub>                                                                     |POST      |
<<<<<<< HEAD
|<sub>/policies/suspend </sub>                                                            |POST      |
=======
>>>>>>> Add support for the create policy
|<sub>/policies/{policyId} </sub>                                                         |DELETE    |
<<<<<<< HEAD
|<sub>/policies/{policyId}/rename</sub>                                                   |POST      |
|<sub>/policies/{policyId}/rules </sub>                                                   |POST      |
|<sub>/policies/{policyId}/rules/{ruleId} </sub>                                          |GET       |
|<sub>/policies/{policyId}/rules/{ruleId} </sub>                                          |DELETE    |
=======
|<sub>/policies/{policyId}/rules </sub>                                                   |POST      |
>>>>>>> Add support for the creating rules in the Simplivity policy
|     **Virtual Machines**
|<sub>/virtual_machines	</sub>                                                            |GET       |
|<sub>/virtual_machines/set_policy	</sub>                                                |POST      |
|<sub>/virtual_machines/{vmId}	</sub>                                                    |GET       |
|<sub>/virtual_machines/{vmId}/backup	</sub>                                            |POST      |
|<sub>/virtual_machines/{vmId}/backup_parameters	</sub>                                |POST      |
|<sub>/virtual_machines/{vmId}/backups	</sub>                                            |GET       |
|<sub>/virtual_machines/{vmId}/clone	</sub>                                            |POST      |
|<sub>/virtual_machines/{vmId}/move	</sub>                                                |POST      |
|<sub>/virtual_machines/{vmId}/power_off	</sub>                                        |POST      |
|<sub>/virtual_machines/{vmId}/power_on	</sub>                                        |POST      |
|<sub>/virtual_machines/{vmId}/set_policy	</sub>                                        |POST      |
=======
|<sub>/hosts</sub>                                                 |GET     |
|<sub>/hosts/{hostId}/remove_from_federation</sub>                 |POST    |
|<sub>/hosts/{hostId}/hardware</sub>                               |GET     |
|<sub>/hosts/{hostId}/virtual_controller_shutdown_status</sub>     |GET     |
|     **OmniStack Clusters**
|<sub>/omnistack_clusters</sub>                                    |GET     |
|<sub>/omnistack_clusters/time_zone_list</sub>                     |GET     |
|     **Policies**
|<sub>/policies</sub>                                              |GET     |
|<sub>/policies</sub>                                              |POST    |
|<sub>/policies/{policyId}</sub>                                   |DELETE  |
|<sub>/policies/{policyId}/rules</sub>                             |POST    |
|<sub>/policies/{policyId}/rules/{ruleId}</sub>                    |GET     |
|<sub>/policies/{policyId}/rules/{ruleId}</sub>                    |DELETE  |
|     **Virtual Machines**
|<sub>/virtual_machines</sub>                                      |GET     |
|<sub>/virtual_machines/set_policy</sub>                           |POST    |
|<sub>/virtual_machines/{vmId}</sub>                               |GET     |
|<sub>/virtual_machines/{vmId}/backup</sub>                        |POST    |
|<sub>/virtual_machines/{vmId}/backup_parameters</sub>             |POST    |
|<sub>/virtual_machines/{vmId}/backups</sub>                       |GET     |
|<sub>/virtual_machines/{vmId}/clone</sub>                         |POST    |
|<sub>/virtual_machines/{vmId}/move</sub>                          |POST    |
|<sub>/virtual_machines/{vmId}/power_off</sub>                     |POST    |
|<sub>/virtual_machines/{vmId}/set_policy</sub>                    |POST    |
>>>>>>> clean up formatting of endpoints-support.md file
