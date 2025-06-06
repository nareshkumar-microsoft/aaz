# [Command] _network bastion delete_

Delete the specified Bastion Host.

## Versions

### [2022-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2Jhc3Rpb25ob3N0cy97fQ==/2022-01-01.xml) **Preview**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/bastionhosts/{} 2022-01-01 -->

#### examples

- Delete a Azure Bastion host machine.
    ```bash
        network bastion delete --name MyBastionHost --resource-group MyResourceGroup
    ```

### [2024-01-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcmVzb3VyY2Vncm91cHMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5uZXR3b3JrL2Jhc3Rpb25ob3N0cy97fQ==/2024-01-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/resourcegroups/{}/providers/microsoft.network/bastionhosts/{} 2024-01-01 -->

#### examples

- Delete Bastion Host
    ```bash
        network bastion delete --name MyBastionHost --resource-group MyResourceGroup
    ```
