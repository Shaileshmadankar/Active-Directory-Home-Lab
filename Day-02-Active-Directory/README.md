# Day 02: Group Policy

**Date:** 18 Nov 2026
**Tools:** Windows Server 2022, Windows 10 Pro, Group Policy Management

## Goal
Create a Group Policy Object (GPO), link it to an OU, and confirm it works on a domain client.

## Steps

### 1. Open Group Policy Management.
![GPMC](01-Group-Policy-Management-Console.png)

### 2. Create GPO 
Created a GPO named Permission.
![Create GPO](02-Create-Group-Policy-Management.png)

### 3. Create a User Inside Organization unit.
Create a User Inside Organization unit.
![Create_USER](03-Create-User-Inside-Organization-Unit.png)

### 4. Click Edit Open Group Policy Management Editor.
Open Group Policy Management Editor.
![Edit_GPO](04-Group-Policy-Managment-Editor.png)

### 5. Group Policy Configuration.
Group Policy User Configuration.
![GPO_Configure](05-Group-Policy-Configuration.png)

### 6. Group Policy Apply.
Apply Configuration to the Group Policy.
![Apply](06-Group-Policy-Apply.png)

### 7. Policy Update Command.
Group Policy Apply Update Command.
![Update_Command](07-Policy-Update-Command.png)

### 8. Group Policy Check.
Group Policy Check.
![Result](08-Group-Policy-Organization-Policy-Check.png)

## What I learned
- A GPO applies to the users and computers in the OU it is linked to
- `gpupdate /force` refreshes policy without waiting


