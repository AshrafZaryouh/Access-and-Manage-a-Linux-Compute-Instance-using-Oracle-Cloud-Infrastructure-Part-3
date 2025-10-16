# Approach 3: Connect via SSH to the Compute Instance Public IP Address using a SSH Private Key with the Royal TSX Application

In this approach, we will connect to a Linux instance using SSH and the public IP address that is provided by OCI to connect directly to the instance using the Royal TSX application.

<img width="2338" height="1710" alt="Access-Manage-Linux-Instance-208" src="https://github.com/user-attachments/assets/ac2082b2-bf7f-413f-a927-8f9c15e8cdce" />

+ Open the Royal TSX application and create a new document.

1. Right-click the **Connections** folder.
2. Click **Add**.
3. Click **Terminal**.

<img width="1021" height="601" alt="Access-Manage-Linux-Instance-209" src="https://github.com/user-attachments/assets/a30d7949-5d8c-42b7-a6f1-c43d1850ea2c" />

+ In the Terminal tab, enter the following information.

1. Enter the **Display Name**.
2. Enter the public IP address or FQDN of the instance in **Computer Name**.
3. Click **Credentials**.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-210" src="https://github.com/user-attachments/assets/73d59ce1-61e8-474a-90d6-4c22af28e135" />

+ In the Credentials tab, enter the following information.

1. Make sure the **Credential** is selected.
2. Select **Specify username and password**.
3. Enter the **Username**.
4. Select the **Private Key File** tab.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-211" src="https://github.com/user-attachments/assets/36402a03-298f-4082-b434-5a9cf28e2eb4" />

+ In the Private Key File tab, enter the following information.

1. Select Path to Private Key File.
2. Select the Private Key File path.
3. Click Apply & Close.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-212" src="https://github.com/user-attachments/assets/79e4604d-0b12-43aa-8069-164a8ea6ddea" />

1. Double-click the new create connection to log in.
2. Run the `ip` a command to review the private IP address.

<img width="1024" height="600" alt="Access-Manage-Linux-Instance-213" src="https://github.com/user-attachments/assets/0addf810-463b-43d8-a1e6-6c1ffad54461" />

---
