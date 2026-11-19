# Active Directory Homelab

Windows Server 2022 Active Directory lab built in VirtualBox: domain controller, DNS, users, OUs, and a domain-joined Windows 10 client.

**Tools:** Windows Server 2022, Windows 10, AD DS, DNS, VirtualBox, PowerShell, CMD

**Skills:** Windows Server administration, Active Directory, DNS, IAM, virtualization, networking, troubleshooting

## Steps

### 1. VM setup
Configured VM hardware, network adapters, and installation media.

![VM memory and boot](screenshots/01-vm-setup/01-server-vm-memory-and-boot.png)
![VM CPU](screenshots/01-vm-setup/02-server-vm-cpu-hardware.png)
![Network adapters](screenshots/01-vm-setup/04-server-vm-network-adapters.png)

### 2. Windows Server installation

![Installation](screenshots/02-server-installation/01-windows-server-installation-progress.png)
![Server Manager](screenshots/02-server-installation/02-server-manager-dashboard-initial.png)

### 3. DC networking
Set static IP and DNS, verified connectivity.

![Static IP and DNS](screenshots/03-dc-networking/02-dc01-static-ip-dns-configuration.png)
![IPv4 properties](screenshots/03-dc-networking/04-dc01-ipv4-properties.png)

### 4. AD DS installation
Installed AD DS and promoted the server to domain controller.

![AD DS installation](screenshots/04-active-directory-install/02-ad-ds-role-installation-progress.png)
![New forest](screenshots/04-active-directory-install/03-create-new-forest-homelab-local.png)

### 5. AD management
Created users and OUs.

![IT OU users](screenshots/05-ad-management/03-creating-it-ou-users.png)
![Users and groups](screenshots/05-ad-management/07-aduc-users-and-groups-view.png)

### 6. Domain join and authentication
Joined the client to the domain and verified login with `whoami`.

![Domain join](screenshots/08-domain-join-authentication/04-welcome-to-domain-confirmation.png)
![whoami](screenshots/08-domain-join-authentication/06-whoami-domain-user-verification.png)

## Next
Group Policy, shared folder permissions, PowerShell automation, security groups, more clients, network segmentation.
