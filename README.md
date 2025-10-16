# Approach 3: Connect via SSH to the Compute Instance Public IP Address using a SSH Private Key with the Royal TSX Application

In this approach, we will connect to a Linux instance using SSH and the public IP address that is provided by OCI to connect directly to the instance using the Royal TSX application.

<img width="2338" height="1710" alt="Access-Manage-Linux-Instance-208" src="https://github.com/user-attachments/assets/f2ab53c4-d0a1-4ab1-b339-0d8d836667a0" />

+ Open the Royal TSX application and create a new document.

1. Right-click the **Connections** folder.
2. Click **Add**.
3. Click **Terminal**.

<img width="1021" height="601" alt="Access-Manage-Linux-Instance-209" src="https://github.com/user-attachments/assets/ac8b8ec4-c04a-4db4-b69c-d022f3b5bd97" />

+ In the Terminal tab, enter the following information.

1. Enter the **Display Name**.
2. Enter the public IP address or FQDN of the instance in **Computer Name**.
3. Click **Credentials**.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-210" src="https://github.com/user-attachments/assets/64ee16fa-2603-443e-bd0a-68b3f4eb6d68" />

+ In the Credentials tab, enter the following information.

1. Make sure the **Credential** is selected.
2. Select **Specify username and password**.
3. Enter the **Username**.
4. Select the **Private Key File** tab.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-211" src="https://github.com/user-attachments/assets/c69949ab-442d-4315-ae7c-2c10312d56db" />

+ In the Private Key File tab, enter the following information.

1. Select Path to Private Key File.
2. Select the Private Key File path.
3. Click Apply & Close.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-212" src="https://github.com/user-attachments/assets/54b6325b-fe9a-44b0-9bd7-8b04d7171d95" />

1. Double-click the new create connection to log in.
2. Run the `ip` a command to review the private IP address.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-213" src="https://github.com/user-attachments/assets/b385bc34-1982-41fa-9cba-334a687c18fc" />

---
