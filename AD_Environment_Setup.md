# Active Directory Home Lab Setup

This is the Active Directory environment I set up in a virtual machine inside my home lab.

![AD environment overview](https://github.com/lorentzbissereth-arch/ActiveDirectoryLab/blob/73c6b6e1988d6894c27b4d301417b38a293f5c3f/image3.png)

## Organizational Units

Here, I created three new organizational units: **USA**, **Europe**, and **Asia**. I did this by right-clicking `lolo.local`, then **New**, then **Organizational Unit**.

![Creating organizational units](https://github.com/lorentzbissereth-arch/ActiveDirectoryLab/blob/e9796d1660c8c7897bcb5cad6a9b88ee5ea14a10/image1.png)

Here, I added three other organizational units inside the USA OU: **Computers**, **Users**, and **Servers**.

![Sub-OUs inside USA](https://github.com/lorentzbissereth-arch/ActiveDirectoryLab/blob/6646ed0fa035b426597327821734230c8873e5ff/image6.png)

## User Creation

Here, I created a user inside the **Users** organizational unit, within the USA OU.

![User creation](media/image5.png)

## Security Groups

Here, I created a security group named **IT** inside the USA OU.

![IT security group](media/image2.png)

Here, you can see all the groups I created inside the Users OU — one of them being a user, and the three others being distribution groups and security groups.

![Groups overview](media/image4.png)

## Summary

In this project, I demonstrate comprehension of using the Active Directory workspace. It showcases the ability to create users and groups, and the ability to work inside a virtual machine.
