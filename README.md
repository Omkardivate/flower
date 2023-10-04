# flowers cart

1. Create new repository on github
2. Clone github repository on local machine in new folder (folder name: Project)
3. Go inside 'Project/cloned_project' create project files (do coding)
4. 'Dockerfile' should be implemented compulsory (save as, for all formats)
5. push on github (exclude lock-up.json, node_modules)

6. Create AWS instance
7. turn off instance firewall
8. <strong>sudo apt update </strong>
9. make directorty [<strong>mkdir docker_project</strong>]
10. <strong>sudo apt install docker.io   </strong>
11. clone git repository in new folder (folder name: docker_project)
12. Go inside 'docker_project/cloned_project'
13. <strong>sudo systemctl --type=service --state=running</strong>
14. <strong>sudo docker build -t img_name . </strong>
15. <strong>sudo docker ps </strong> -> gives running containers 
16. <strong>sudo docker images </strong> -> gives created images 
17. <strong>sudo docker run -d -p port_no:port_no  img_name </strong>  -> to run the image on port_no
18. go to browser, 'http://ip_address:port_no' 
