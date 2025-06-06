# [Command] _computeschedule vm-execute-hibernate_

VirtualMachinesExecuteHibernate: Execute hibernate operation for a batch of virtual machines, this operation is triggered as soon as Computeschedule receives it.

## Versions

### [2024-10-01](/Resources/mgmt-plane/L3N1YnNjcmlwdGlvbnMve30vcHJvdmlkZXJzL21pY3Jvc29mdC5jb21wdXRlc2NoZWR1bGUvbG9jYXRpb25zL3t9L3ZpcnR1YWxtYWNoaW5lc2V4ZWN1dGVoaWJlcm5hdGU=/2024-10-01.xml) **Stable**

<!-- mgmt-plane /subscriptions/{}/providers/microsoft.computeschedule/locations/{}/virtualmachinesexecutehibernate 2024-10-01 -->

#### examples

- VirtualMachinesExecuteHibernate
    ```bash
        computeschedule vm-execute-hibernate --location eastus2euap --execution-parameters "{retry-policy:{retry-count:5,retry-window-in-minutes:27}}" --resources "{ids:[/subscriptions/fe541807-8c68-475d-976d-f453f9db4d81/resourceGroups/test-rg/providers/Microsoft.Compute/virtualMachines/testResource3]}" --correlationid 23480d2f-1dca-4610-afb4-dd25eec1f34r
    ```
