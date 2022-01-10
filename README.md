# PrintSpoofer

PrintSpoofer exploit that can be used to escalate service user permissions on Windows Server 2016, Server 2019, and Windows 10.

To escalate privileges, the service account must have SeImpersonate privileges. To execute:

PrintSpoofer.exe -i -c cmd

With appropriate privileges this should grant system user shell access.

![image](https://user-images.githubusercontent.com/66146701/148759629-ee6184c7-3f68-4bdb-9a1e-56691284bb99.png)

![image](https://user-images.githubusercontent.com/66146701/148759662-fdf95d68-f55e-4fe4-a0c4-729f879dba9c.png)

![image](https://user-images.githubusercontent.com/66146701/148759677-a92aa374-4257-4058-8918-0fccbf0d3dce.png)
