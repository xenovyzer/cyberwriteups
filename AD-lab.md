# AD-LAB - Self Run

## What is being conducted
This lab is an personal attempt to gain skills in active directory and virtualisation, concepts that I am very unfamiliar with but hope to get competent at throughout the course of this lab.
The lab itself uses my gaming pc as a headless virtualisation host which is remote accessed from my macbook. To achieve this I have set-up Proxmox onto the computer and used a travel router to make a network in which my computer and macbook can communicate. 

## Session 0 -  Physical Setup
During this session I have arranged for my computer to sit elsewhere from my workspace and plugged it up with a monitor and the travel router. Then I initialised virtualisation through the bios before putting in a usb with Proxmox loaded beforehand to override windows. Upon initial setup of proxmox and aligning all IP values to what comes pre-installed in my travel router, I was able to remotely connect to the proxmox server and access the Linux shell within the computer. 

### Mistakes and Issues
After initial setup I left the usb in the computer which made it recognise a foreign boot devvice and I had to set it up all over. :( 
