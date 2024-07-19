# Install_Apache_with_Ansible

For this basic mini project I decided to automate the installation and configuration of the Apache web server on my local Ubuntu machine using an Ansible playbook.

## Confirm Ansible installation and create playbook

First, I confirm that Ansible is indeed installed on my Ubuntu machine.

![Screenshot (289)](https://github.com/user-attachments/assets/52d751ec-15a1-4c6e-84a1-072ab14931c5)

Then I create the YAML file (playbook) containing the tasks to automate the installation of Apache on my local machine. I used the Vim editor for this step.

![Screenshot (293)](https://github.com/user-attachments/assets/0d7b703c-32cc-4c23-8ff9-61dc86e9fccf)
![Screenshot (294)](https://github.com/user-attachments/assets/5c3f81ce-dbe0-4026-b41c-c723c9f4a23b)

## Run the playbook

After it is done, I run the playbook.

![Screenshot (296)](https://github.com/user-attachments/assets/4e9663e7-f3e2-4ec2-aa0b-355d517f7754)
![Screenshot (297)](https://github.com/user-attachments/assets/83d74fba-6afb-499c-b934-3153b5894cdc)

## Verify installation

After the installation is finished, I verify that Apache is indeed installed. First I check the service status.

![Screenshot (298)](https://github.com/user-attachments/assets/27fb9af4-1f34-480d-b4f5-9153fbd32918)

Then, I test in my web browser by navigating to 'http://localhost'.

![Screenshot (300)](https://github.com/user-attachments/assets/621e44c6-12b7-480d-b8e7-4e0cfcf70657)

Apache is correctly installed and serving web pages.
