# How to Activate Your University Domain (web.itu.edu.tr/username)

Many universities provide personal web domains to students. This guide shows you how to activate your domain at Istanbul Technical University (ITU), but the process is similar for many institutions.

## Steps to Activate Your Domain:

1) **Connect to the university SSH server**
   - Check your university's IT documentation for specific connection details. For ITU, refer to the [official guide](https://bidb.itu.edu.tr/seyir-defteri/blog/2013/09/06/windows-ssh-server-kurulumu-ve-yap%C4%B1land%C4%B1r%C4%B1lmas%C4%B1)
   - I am using Cyberduck (available for macOS, Windows, and Linux via CLI)

   <p align="center">
     <img width="400" alt="SSH Connection Example" src="https://github.com/user-attachments/assets/cede96d4-2723-4c90-bbd6-9bb63759871b" />
   </p>

1) **Set up your web directory**
   - Navigate to your `web.itu.edu.tr` folder (this is typically created when you enroll)
   - Create a `public_html` folder if it doesn't already exist
   - Add an `index.html` file within this folder
   
   <p align="center">
     <img width="150" alt="Directory Structure Example" src="https://github.com/user-attachments/assets/207fb27c-e454-4bba-9c48-5b39b4a9c94c" />
   </p>

That's it! Your personal university web domain should now be active.
