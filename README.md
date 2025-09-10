# 🚀 **DevOps Project: ZOMATO Clone App Deployment**

In this **DevOps project**, I demonstrate how to **deploy a ZOMATO Clone App** using a variety of modern DevOps tools and services.

## 🛠️ Tools & Services Used:

1. **GitHub** ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
2. **Jenkins** ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
3. **SonarQube** ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
4. **Docker** ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
5. **Kubernetes** ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
6. **Prometheus** ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
7. **Grafana** ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
8. **ArgoCD** ![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
9. **OWASP** ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white)
10. **Trivy** ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white)

### 📂 GitHub Repo Link:  
[**ZOMATO Clone DevOps Project**](#)

## Connect with me on LinkedIn:  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdulazizuk/)

## Happy learning!  AbdulAziz Mohammed

Zomato application Deploy on kubernetes using Github, Jenkins, Sonar Qube, OWASP, Trivy, Docker, Docker-Scout, Email, Kubernetes, ArgoCD, Grafana, Prometheus.
<ul>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" alt="" width="855" height="449" /></a></li>
<li><details><summary>Tools &amp; Services Used</summary>
<ul>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato2.jpg" alt="" width="588" height="311" /></a></li>
<li>GitHub</li>
<li>Jekins - CI/CD</li>
<li>Sonar Qube: Code Quality Analysis&nbsp;</li>
<li>OWASP: File System scan</li>
<li>Trivy: Dependency</li>
<li>Docker: Image</li>
<li>Docker Scout: Image Scan</li>
<li>Deploy on docker container:</li>
<li>Email Notification:</li>
<li>Deploy on Kubernetes Cluster: EKS</li>
<li>Deploy ton EKS with ArgoCD</li>
<li>Monitoring: EKS, Jenkins using Grafana, Prometheus</li>
</ul>
</details></li>
<li><details><summary>Clone Repository</summary>
<ul>
<li>Install Git&nbsp;</li>
<li>$git clone&nbsp;<a href="https://github.com/AbdulAziz-uk/zomato.git">https://github.com/AbdulAziz-uk/zomato.git</a></li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato3.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato3.jpg" alt="" width="508" height="322" /></a></li>
<li>list the files</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato4.jpg" alt="" width="687" height="138" /></li>
</ul>
</details></li>
<li><details><summary>Project Architecture</summary>
<ul>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato3.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato3.jpg" alt="" width="567" height="360" /></a></li>
<li>Dockerfile explanation:</li>
<li>Jenkinsfile explanation:</li>
<li>code</li>
</ul>
</details></li>
<li><details><summary>Deploy Locally&nbsp;</summary>
<ul>
<li>change directory to clone repository zomato</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato4.jpg" alt="" width="687" height="138" /></li>
<li>Install the following pre requisite to run the application
<ul>
<li>Java 17:&nbsp;</li>
<li>npm: $npm install or $sudo apt install npm</li>
</ul>
</li>
<li>npm build package:
<ul>
<li>$npm run build</li>
</ul>
</li>
<li>Start npm
<ul>
<li>$npm start</li>
</ul>
</li>
<li>Access application.
<ul>
<li><a href="http://PublicIP:3000">http://PublicIP:3000</a></li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" alt="" width="619" height="325" /></a></li>
</ul>
</li>
</ul>
</details></li>
<li><details><summary>Infra Setup for CI/CD</summary>
<ul>
<li>Create 3 Ubuntu VMs (you can create 3 vms or single vm for each service and integrate)</li>
<li>First VM: Install git, Java, AWS CLI,docker, kubectl, eksctl, helm
<ul>
<li>This VM is used for:</li>
<li>Deploy application locally.</li>
<li>EKS setup</li>
<li>helm version</li>
</ul>
</li>
<li>Second VM: Install Jenkins, Docker, Trivy, Docker scout, sonarqube container,&nbsp;
<ul>
<li>
<p>1. Launch an Instance (Ubuntu, 24.04, t2.large, 30 GB)</p>
<p>2. Connect to the instance</p>
<p>3. Update the packages<br />$ switch to root user ---&gt; sudo su<br />$ sudo apt update -y</p>
<p>4. Install AWS CLI<br />sudo apt install unzip -y<br />curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"<br />unzip awscliv2.zip<br />sudo ./aws/install</p>
<p>5. Install Jenkins on Ubuntu<br />(Reference URL for commands: https://www.jenkins.io/doc/book/installing/linux/#debianubuntu)<br />#!/bin/bash<br />sudo apt update -y<br />wget -O - https://packages.adoptium.net/artifactory/api/gpg/key/public | sudo tee /etc/apt/keyrings/adoptium.asc<br />echo "deb [signed-by=/etc/apt/keyrings/adoptium.asc] https://packages.adoptium.net/artifactory/deb $(awk -F= '/^VERSION_CODENAME/{print$2}' /etc/os-release) main" | sudo tee /etc/apt/sources.list.d/adoptium.list<br />sudo apt update -y<br />sudo apt install temurin-17-jdk -y<br />/usr/bin/java --version<br />curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee /usr/share/keyrings/jenkins-keyring.asc &gt; /dev/null<br />echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list &gt; /dev/null<br />sudo apt-get update -y<br />sudo apt-get install jenkins -y<br />sudo systemctl start jenkins<br />sudo systemctl status jenkins</p>
<p>Verifiy Jenkins installation: jenkins --version</p>
<p>5.1. Open Port No. 8080 for VM and access Jenkins<br />5.2. Setup Jenkins by following the necessary steps</p>
<p>6. Install Docker on Ubuntu<br />(Reference URL for commands: https://docs.docker.com/engine/install/ubuntu/)</p>
<p># Add Docker's official GPG key:<br />sudo apt-get update<br />sudo apt-get install ca-certificates curl<br />sudo install -m 0755 -d /etc/apt/keyrings<br />sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc<br />sudo chmod a+r /etc/apt/keyrings/docker.asc<br /># Add the repository to Apt sources:<br />echo \<br /> "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \<br /> $(. /etc/os-release &amp;&amp; echo "$VERSION_CODENAME") stable" | \<br /> sudo tee /etc/apt/sources.list.d/docker.list &gt; /dev/null<br />sudo apt-get update<br />sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin -y<br />sudo usermod -aG docker ubuntu<br />sudo chmod 777 /var/run/docker.sock<br />newgrp docker<br />sudo systemctl status docker</p>
<p>Verifiy Docker installation: docker --version</p>
<p>7. Install Trivy on Ubuntu<br />(Reference URL for commands: https://aquasecurity.github.io/trivy/v0.55/getting-started/installation/)<br />sudo apt-get install wget apt-transport-https gnupg<br />wget -qO - https://aquasecurity.github.io/trivy-repo/deb/public.key | gpg --dearmor | sudo tee /usr/share/keyrings/trivy.gpg &gt; /dev/null<br />echo "deb [signed-by=/usr/share/keyrings/trivy.gpg] https://aquasecurity.github.io/trivy-repo/deb generic main" | sudo tee -a /etc/apt/sources.list.d/trivy.list<br />sudo apt-get update<br />sudo apt-get install trivy</p>
<p>Verifiy Trivy installation: trivy --version</p>
<p>8. Install Docker Scout.</p>
<ul>
<li>It is required to login to docker hub account from ubuntu CLI.</li>
<li>run $docker login -u aziz27uk&nbsp; (enter password)</li>
<li>switch to root user: $su root</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato6.jpg" alt="" width="822" height="310" /></li>
<li>Lets install the Docker Scout : $curl -fsSL https://raw.githubusercontent.com/docker/scout-cli/main/install.sh -o install-scout.sh<br />sh install-scout.sh&nbsp;</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato5.jpg" alt="" width="814" height="168" /></li>
<li>Give the permission to dockerScout to execute the file: $sudo chmod 777 /var/run/docker.sock</li>
</ul>
</li>
<li>
<p>9. Install SonarQube using Docker<br />$ docker run -d --name sonar -p 9000:9000 sonarqube:lts-community<br />$ docker ps (You can see SonarQube container)</p>
<p>&lt;Follow the process as explained in the video&gt;</p>
<p>10. Installation of Plugins in Jenkins<br />Install below plugins:<br />&lt;jdk17, nodejs 23, OWASP Dependency check, sonar-scanner, docker&nbsp; &gt;</p>
<p>11. SonarQube configuration in Jenkins<br />&lt;Follow the process as explained in the video&gt;</p>
<p>11.1. Tools Configuration in Jenkins<br />&lt;Follow the process as explained in the video&gt;</p>
<p>11.2. Configuration of SonarQube Token in Jenkins<br />&lt;Follow the process as explained in the video&gt;</p>
<p>Lets create another credentials for DockerHub. This is being done because, as soon as the docker image is created, it should get pushed to dockerhub. <br />&lt;Follow the process as explained in the video&gt;</p>
<p>11.3 Configuration of Email notification in Jenkins<br />As soon as the build happens, i need to get an email notification to do that we have to configure our email.</p>
<ul>
<li>Gmail Setup:
<ul>
<li>To receive emails for success/failure of CICD pipeline.</li>
<li>Go to Gmail account and click on account top right corner and select manage your account.</li>
<li>type app passwords (This option will only available after MFA is enabled, To enable go to security/2 step verification and enable it and add phone number)</li>
<li>app name=hotstar and create password.&nbsp; copy app password.</li>
</ul>
</li>
<li>Go to Manage Jenkins/System/E-mail Notification
<ul>
<li>SMTP Server = smtp.gmail.com</li>
<li>Default user email suffix=@gmail.com</li>
<li>Advanced</li>
<li>select Use SMTP Authentication:</li>
<li>user name =&nbsp;<a href="mailto:aziz.azure2024@gmail.com">aziz.azure2025@gmail.com</a>&nbsp;(enter email address for which app password has been created)</li>
<li>Password =&nbsp;svgi&nbsp;xqps&nbsp;yhyj&nbsp;zcaj (paste token)</li>
<li>select Use SSL</li>
<li>SMTP Port = 465 (open this port on firewall)</li>
<li>Reply-To-Address =&nbsp;<a href="mailto:aziz.azure2024@gmail.com">aziz.azure2025@gmail.com</a></li>
<li>Charset = UTF-8</li>
<li>Select Test configurtion by sending test e-mail</li>
<li>Test e-mail recipient =&nbsp;<a href="mailto:aziz.azure2024@gmail.com">aziz.azure2025@gmail.com</a></li>
<li>Test Configuration: Email received.</li>
</ul>
</li>
<li>Go to Manage Jenkins/System/Extended E-mail Notification
<ul>
<li>SMTP server=smtp.gmail.com</li>
<li>SMTP Port =587 (open port)</li>
<li>Advanced:</li>
<li>Credentials: Add Jenkins
<ul>
<li>Domain: global credentials (unrestricted)</li>
<li>Kind = Username with Password</li>
<li>Scope = Global (Jenkins, nodes, items, all child items,etc)</li>
<li>username =&nbsp;<a href="mailto:aziz.azure2024@gmail.com">aziz.azure2025@gmail.com</a></li>
<li>Password=svgixqpsyhyjzcaj (paste token)</li>
<li>ID = smtp-gmail</li>
<li>Description = smtp-gmail</li>
</ul>
</li>
<li>In credentials selet smtp-gmail</li>
<li>select Use TLS</li>
<li>Default user e-mail suffix = @gmail.com</li>
</ul>
</li>
<li>Triiger email setup
<ul>
<li>ctrl f and search for default trigger in system</li>
<li>select Always, Failure-any, success</li>
<li>Apply &amp; save</li>
</ul>
</li>
</ul>
<p><br />12. System Configuration in Jenkins<br />&lt;Follow the process as explained in the video&gt;</p>
<p>13. Create webhook in SonarQube<br />&lt;Follow the process as explained in the video&gt;</p>
<p>14. Create Pipeline Job</p>
</li>
</ul>
</li>
<li>Third VM: Monitoring server- check below monitoring section</li>
</ul>
</details></li>
<li><details><summary>CI/CD Deployment on Docker Container</summary>
<ul>
<li>Login to Jenkins and create a project.</li>
<li>CI/CD <a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato.yaml" target="_blank" rel="noopener">yaml script</a>.
<ul>
<li>
<div>
<div>pipeline {</div>
<div>&nbsp; &nbsp; agent any</div>
<div>&nbsp; &nbsp; tools {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; jdk 'jdk17'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; nodejs 'node23'</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; environment {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; SCANNER_HOME=tool 'sonar-scanner'</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; stages {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("clean workspace") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; cleanWs()</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("Git Checkout") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; git 'https://github.com/AbdulAziz-uk/zomato.git'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage("Sonarqube Analysis"){</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps{</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; withSonarQubeEnv('sonar') {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh ''' $SCANNER_HOME/bin/sonar-scanner -Dsonar.projectName=zomato \</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; -Dsonar.projectKey=zomato '''</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage("Code Quality Gate"){</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; script {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; waitForQualityGate abortPipeline: false, credentialsId: 'sonar-token'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage("Install NPM Dependencies") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "npm install"</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage('OWASP FS SCAN') {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; dependencyCheck additionalArguments:'--scan ./ --disableYarnAudit --disableNodeAudit -n', odcInstallation:'DC'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; dependencyCheckPublisher pattern:'**/dependency-check-report.xml'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("Trivy File Scan") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "trivy fs . &gt; trivy.txt"</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("Build Docker Image") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker build -t zomato ."</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("Tag &amp; Push to DockerHub") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; script {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; withDockerRegistry(credentialsId:'docker-cred') {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker tag zomato aziz27uk/zomato:latest "</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh "docker push aziz27uk/zomato:latest "</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage('Docker Scout Image Analysis') {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; script{</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;withDockerRegistry(credentialsId:'docker-cred', toolName:'docker'){</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;sh 'docker-scout quickview aziz27uk/zomato:latest'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;sh 'docker-scout cves aziz27uk/zomato:latest'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;sh 'docker-scout recommendations aziz27uk/zomato:latest'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;}</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; stage ("Deploy to Container") {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; steps {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; sh 'docker run -d --name zomato -p 3000:3000 aziz27uk/zomato:latest'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; post {</div>
<div>&nbsp; &nbsp; always {</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; emailext attachLog:true,</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; subject:"'${currentBuild.result}'",</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; body:"""</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;html&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;body&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;div style="background-color:#FFA07A; padding:10px; margin-bottom:10px;"&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;p style="color:white; font-weight:bold;"&gt;Project:${env.JOB_NAME}&lt;/p&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;/div&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;div style="background-color:#90EE90; padding:10px; margin-bottom:10px;"&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;p style="color:white; font-weight:bold;"&gt;Build Number:${env.BUILD_NUMBER}&lt;/p&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;/div&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;div style="background-color:#87CEEB; padding:10px; margin-bottom:10px;"&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;p style="color:white; font-weight:bold;"&gt;URL:${env.BUILD_URL}&lt;/p&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;/div&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;/body&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;/html&gt;</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; """,</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; to:'aziz.azure2025@gmail.com',</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; mimeType:'text/html',</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; attachmentsPattern:'trivy.txt'</div>
<div>&nbsp; &nbsp; &nbsp; &nbsp; }</div>
<div>&nbsp; &nbsp; }</div>
<div>}</div>
</div>
</li>
</ul>
</li>
<li>Build the CI/CD pipeline</li>
<li>Error in docker scout stage:</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato7.jpg" alt="" width="1295" height="130" /></li>
<li>Solution:&nbsp; Permission issue, Give ubuntu user permission to run commands on docker.
<ul>
<li>$sudo usermod -aG docker ubuntu<br />$sudo chmod 777 /var/run/docker.sock<br />$newgrp docker</li>
</ul>
</li>
<li>Access the applicaiton: <a href="http://publicIP:3000">http://publicIP:3000</a>&nbsp;(check Dockerfile for port number)</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" alt="" width="619" height="325" /></a></li>
</ul>
</details></li>
<li><details><summary>CI/CD Deployment on Kubernetes Cluster.</summary>
<ul>
<li>Deploy zomato application on K8S cluster. In order to do that will create the EKS cluster.</li>
<li><details><summary>Create EKS service in AWS using VS code editor.</summary>
<ul>
<li>Note 1: You might get errors while executing the below commands. Make sure to do the required configurations eksctl, kubectl, and other tools.<br />Note 2: Run the VS Code Editor/Power Shell/Command Prompt as Administrator, to avoid errors.</li>
<li>Open vs code editor and execute the below commands; <br />Step 01: Create EKS Cluster using eksctl<br /># Create Cluster. I will keep the cluster name as "kastrocluster"<br />eksctl create cluster --name=kastrocluster \<br /> --region=ap-northeast-1 \<br /> --zones=ap-northeast-1a,ap-northeast-1c \<br /> --without-nodegroup
<p>If you see any error while executing the above commands in VS Code Editor, it is due to how PowerShell interprets backslashes (\) as line continuation characters. Unlike Unix-like shells, PowerShell does not support line continuation in this way.</p>
<p>To resolve this issue, you can either write the entire command on a single line or use a different method for line continuation. Here are the two approaches:</p>
<p>Approach 1: Single Line Command (In this video i will prefer this)<br />Simply run the entire command in one line without using backslashes for line continuation:<br />eksctl create cluster --name=kastrocluster --region=ap-northeast-1 --zones=ap-northeast-1a,ap-northeast-1c --without-nodegroup</p>
<p><br />Approach 2: Use PowerShell&rsquo;s Backtick for Line Continuation<br />If you want to split the command across multiple lines, you can use the backtick character (`) in PowerShell for line continuation:<br />eksctl create cluster --name=kastrocluster `<br /> --region=ap-northeast-1 `<br /> --zones=ap-northeast-1a,ap-northeast-1c `<br /> --without-nodegroup</p>
<p>Note: Make sure there is no space after the backtick.</p>
<p>It will take atleast 20-25 minutes for the cluster to create.</p>
<p>To verify the cluster creation ---&gt; Goto Cloud Formation service in AWS ----&gt; You should see a stack got created with the name "kastrocluster". Make sure in the vs code editor the cluster will get created. As said earlier it will take atleast 20 minutes.<br />Once the cluster is ready, you will see "EKS Cluster "kastrocluster" in "us-east-1" region is ready" in vs code editor. wait till you see this.<br />+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++<br /># Get List of clusters<br />eksctl get cluster</p>
<p>Execute the below in vs code editor;</p>
<p>Step 02: Create &amp; Associate IAM OIDC Provider for our EKS Cluster<br />To enable and use AWS IAM roles for Kubernetes service accounts on our EKS cluster, we must create &amp; associate OIDC identity provider.<br />To do so using eksctl we can use the below commands.</p>
<p># Template<br />eksctl utils associate-iam-oidc-provider \<br /> --region region-code \<br /> --cluster &lt;cluster-name&gt; \<br /> --approve</p>
<p># Replace with region &amp; cluster name<br />eksctl utils associate-iam-oidc-provider \<br /> --region ap-northeast-1 \<br /> --cluster kastrocluster \<br /> --approve</p>
<p>(OR)<br />eksctl utils associate-iam-oidc-provider --region ap-northeast-1 --cluster kastrocluster --approve</p>
<p>(OR)<br />eksctl utils associate-iam-oidc-provider `<br /> --region uap-northeast-1 `<br /> --cluster kastrocluster `<br /> --approve</p>
<p>Step 03: Create Node Group with additional Add-Ons in Public Subnets<br />These add-ons will create the respective IAM policies for us automatically within our Node Group role.</p>
<p># Create Public Node Group <br />eksctl create nodegroup --cluster=kastrocluster \<br /> --region=ap-northeast-1 \<br /> --name=kastrodemo-ng-public1 \<br /> --node-type=t3.medium \<br /> --nodes=2 \<br /> --nodes-min=2 \<br /> --nodes-max=4 \<br /> --node-volume-size=20 \<br /> --ssh-access \<br /> --ssh-public-key=Prajwal \<br /> --managed \<br /> --asg-access \<br /> --external-dns-access \<br /> --full-ecr-access \<br /> --appmesh-access \<br /> --alb-ingress-access</p>
<p>(OR)<br />eksctl create nodegroup --cluster=kastrocluster --region=ap-northeast-1 --name=kastrodemo-ng-public1 --node-type=t3.medium --nodes=2 --nodes-min=2 --nodes-max=4 --node-volume-size=20 --ssh-access --ssh-public-key=Prajwal --managed --asg-access --external-dns-access --full-ecr-access --appmesh-access --alb-ingress-access</p>
<p>(OR)<br />eksctl create nodegroup --cluster=kastrocluster `<br /> --region=ap-northeast-1 `<br /> --name=kastrodemo-ng-public1 `<br /> --node-type=t3.medium `<br /> --nodes=2 `<br /> --nodes-min=2 `<br /> --nodes-max=4 `<br /> --node-volume-size=20 `<br /> --ssh-access `<br /> --ssh-public-key=Prajwal `<br /> --managed `<br /> --asg-access `<br /> --external-dns-access `<br /> --full-ecr-access `<br /> --appmesh-access `<br /> --alb-ingress-access</p>
<p>Step 05: Verify Cluster &amp; Nodes<br />Goto EKS Service in AWS and check for the cluster creation</p>
<p>******************************************<br />Optional - do it at the end of complete demo<br />******************************************<br />Step 06: Delete Node Group<br /># List EKS Clusters<br />eksctl get clusters</p>
<p># Capture Node Group name<br />eksctl get nodegroup --cluster=&lt;clusterName&gt;<br />eksctl get nodegroup --cluster=kastrocluster</p>
<p># Delete Node Group<br />eksctl delete nodegroup --cluster=&lt;clusterName&gt; --name=&lt;nodegroupName&gt;<br />eksctl delete nodegroup --cluster=kastrocluster --name=kastrodemo-ng-public1</p>
<p>Step 07: Delete Cluster<br /># Delete Cluster<br />eksctl delete cluster &lt;clusterName&gt;<br />eksctl delete cluster kastrocluster<br />********************************************************************************<br />********************************************************************************<br />Let us deploy the same application in the EKS cluster also</p>
<p>&lt;Follow the process as explained in the video&gt;</p>
</li>
</ul>
</details></li>
<li><details><summary>Create EKS service in AWS using script</summary>
<ul>
<li>Click the link and follow the steps:&nbsp;<a href="https://github.com/AbdulAziz-uk/EKS_with_Terraform.git">https://github.com/AbdulAziz-uk/EKS_with_Terraform.git</a></li>
<li>Install AWS CLI:&nbsp; Create a VM or perform on your local computer:&nbsp;
<ul>
<li>on your laptop / local VM / AWS VM through we can configure EKS cluster on AWS</li>
<li>Get Security Credentials (AWS Security Key, Security Access Key) of a user from AWS(click on user top right corner on aws console and security credentials/ AWS command CLI/ and create keys)</li>
<li>ubuntu@ip-172-31-37-97:~$ sudo apt up</li>
<li>$curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"<br />sudo apt-get install unzip -y<br />unzip awscliv2.zip<br />sudo ./aws/install</li>
<li>$aws configure</li>
<li>Enter access key and secret access key, Region (eu-west-2)</li>
</ul>
</li>
<li>Clone Repository of EKS with Terraform:
<ul>
<li>$git clone&nbsp;<a href="https://github.com/AbdulAziz-uk/EKS_with_Terraform.git">https://github.com/AbdulAziz-uk/EKS_with_Terraform.git</a></li>
<li>$cd EKS_with_terraform:&nbsp; This folder contain</li>
<li>RBAC</li>
<li>main.tf: It contains all the codes to create VPC and EKS</li>
<li>output.tf:&nbsp; It outputs cluster id, nodegroup id, vpc id, subnet id.</li>
<li>variable.tf: It contains ssh key of AWS</li>
</ul>
</li>
<li>Install Terraform:
<ul>
<li>$sudo vim terraform.sh</li>
<li>paste the below script
<ul>
<li>
<p>#!/bin/bash<br /># Script to install Terraform on an instance</p>
<p># Update package list and install dependencies<br />sudo apt-get update &amp;&amp; sudo apt-get install -y gnupg software-properties-common</p>
<p># Add HashiCorp GPG key<br />wget -O- https://apt.releases.hashicorp.com/gpg | \<br />gpg --dearmor | \<br />sudo tee /usr/share/keyrings/hashicorp-archive-keyring.gpg &gt; /dev/null</p>
<p># Verify the key fingerprint<br />gpg --no-default-keyring \<br />--keyring /usr/share/keyrings/hashicorp-archive-keyring.gpg \<br />--fingerprint</p>
<p># Add HashiCorp repository to sources list<br />echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] \<br />https://apt.releases.hashicorp.com $(lsb_release -cs) main" | \<br />sudo tee /etc/apt/sources.list.d/hashicorp.list</p>
<p># Update package lists<br />sudo apt update</p>
<p># Install Terraform<br />sudo apt-get install terraform -y</p>
<p>## Verify installation<br />terraform -v</p>
</li>
</ul>
</li>
<li>make script executable</li>
<li>$sudo chmod +x terraform.sh</li>
<li>Run Script</li>
<li>$sudo sh terraform.sh (it will install terraform)</li>
<li>$terraform --version</li>
</ul>
</li>
<li>Configure EKS on AWS:
<ul>
<li>Initialize the terraform.</li>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$ terraform init</li>
<li>Run terraform plan:</li>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$ terraform plan</li>
<li>&nbsp;Run Terraform apply:</li>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$ terraform apply&nbsp; --auto-approve</li>
<li>It will create 19 resources:</li>
</ul>
</li>
<li>Configure Kubeconfig:&nbsp; We will be able to access the cluster.
<ul>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$aws&nbsp;eks --region eu-west-2 update-kubeconfig --name star-cluster</li>
<li>updated context arn:aws:eks:eu-west-2:034646250868:cluster/star-cluster to /home/ubuntu/.kube/config</li>
</ul>
</li>
<li>Install kubectl:&nbsp; We can communicate with cluster and perform commands&nbsp;
<ul>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$curl -LO https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl<br />sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl<br />kubectl version --client</li>
</ul>
</li>
<li>Install eksctl:
<ul>
<li>ubuntu@ip-172-31-37-97:~/EKS_with_Terraform$curl --silent --location "https://github.com/weaveworks/eksctl/releases/latest/download/eksctl_$(uname -s)_amd64.tar.gz" | tar xz -C /tmp<br />sudo mv /tmp/eksctl /usr/local/bin<br />kubectl version --client</li>
</ul>
</li>
<li>Associate iam-oidc-provider:
<ul>
<li>ubuntu@ip-172-31-37-97:~$ eksctl utils associate-iam-oidc-provider --region eu-west-2 --cluster star-cluster --approve</li>
</ul>
</li>
<li>Create IAM Service Account for EBS CSI Driver:
<ul>
<li>ubuntu@ip-172-31-37-97:~$eksctl create iamserviceaccount \<br />--region eu-west-2 \<br />--name ebs-csi-controller-sa \<br />--namespace kube-system \<br />--cluster star-cluster \<br />--attach-policy-arn arn:aws:iam::aws:policy/service-role/AmazonEBSCSIDriverPolicy \<br />--approve \<br />--override-existing-serviceaccounts</li>
</ul>
</li>
<li>Deploy Add-Ons
<ul>
<li>EBS CSI Driver:</li>
<li>ubuntu@ip-172-31-37-97:~$kubectl apply -k "github.com/kubernetes-sigs/aws-ebs-csi-driver/deploy/kubernetes/overlays/stable/ecr/?ref=release-1.11"</li>
<li>NGINX Ingress Controller:</li>
<li>ubuntu@ip-172-31-37-97:~$kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/cloud/deploy.yaml</li>
<li>cert-manager:</li>
<li>ubuntu@ip-172-31-37-97:~$kubectl apply -f <a href="https://github.com/cert-manager/cert-manager/releases/download/v1.12.0/cert-manager.yaml">https://github.com/cert-manager/cert-manager/releases/download/v1.12.0/cert-manager.yaml</a></li>
</ul>
</li>
<li>Check EKS Cluster:
<ul>
<li>zomato14.jpg</li>
<li>Check nodes, node groups, click on compute.&nbsp; There is 1 node group with desired size 3 (nodes)</li>
<li>zomato15.jpg</li>
</ul>
</li>
<li>Delete the EKs Cluster.
<ul>
<li>$terraform destroy</li>
</ul>
</li>
</ul>
</details></li>
<li><details><summary>Infra Setup for Kubernetes cluster using kubeadm:</summary>
<ul>
<li>&nbsp;Install Kubectl on jenkins.
<ul>
<li>vi kubectl.sh</li>
<li>paste the following</li>
<li>
<p>#!/bin/bash<br /># Script to install kubectl on an instance</p>
<p># Update package list<br />sudo apt update -y</p>
<p># Install curl<br />sudo apt install curl -y</p>
<p># Download the latest stable kubectl binary<br />curl -LO https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl</p>
<p># Install kubectl and set correct permissions<br />sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl</p>
<p># Verify the installation<br />kubectl version --client</p>
</li>
<li>Give executve permission $sudo chmod +x kubectl.sh</li>
</ul>
</li>
<li>Create 2 Ubuntu VMS T2 Medium (Master &amp; worker)
<ul>
<li>Take SSH connection for both</li>
<li>$sudo apt update</li>
<li>$sudo hostnamectl set-hostname master</li>
<li>$bash</li>
<li>$sudo hostnamectl set-hostname worker</li>
<li>$bash</li>
</ul>
</li>
</ul>
<ul>
<li>Install Docker on both:
<ul>
<li>$sudo apt install docker.io -y</li>
<li>$sudo usermod -aG docker ubuntu</li>
<li>$newgrp docker</li>
<li>$sudo chmod 777 /var/run/docker.sock</li>
<li>$docker ps</li>
</ul>
</li>
<li>Dowload packages on both
<ul>
<li>$sudo curl -s https://packages.cloud.google.com/apt/doc/apt-key.gpg&nbsp;| sudo apt-key add -</li>
<li>$sudo tee /etc/apt/sources.list.d/Kubernetes.list &lt;&lt;EOF<br />deb https://apt.kubernetes.io/ kubernetes-xenial main<br />EOF</li>
<li>$sudo apt get update</li>
<li>$sudo apt-get install -y kubelet kubeadm kubectl</li>
<li>$sudo snap install kube-apiserver</li>
</ul>
</li>
<li>Master node:
<ul>
<li>$sudo kubeadm init --pod-network-cidr=192.168.171.200/24</li>
<li>copy and run mkdir -p $HOME/.kube</li>
<li>copy and run cp -i /etc/kubernetes/admin.conf $HOME/.kube/config</li>
<li>copy and run chown $(id -u):$(id -g) $HOME/.kube/config</li>
<li>kubectl apply -f&nbsp;<a href="https://raw.githubsercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml">https://raw.githubsercontent.com/coreos/flannel/master/Documentation/kube-flannel.yml</a></li>
<li>$kubectl get nodes</li>
<li>$cd .kube/</li>
<li>$cat config</li>
<li>copy the entire content and paste it in your local computer (SecretFile.txt).</li>
</ul>
</li>
<li>Worker Node:
<ul>
<li>copy the join node command and run in worker nod: sudo kubeadm joint 192.168.171.200:6443 --token xxxxxxxxxxxxxxxx</li>
</ul>
</li>
<li>Install Plugins in jenkins:
<ul>
<li>kubernetes</li>
<li>kubernetes credentials</li>
<li>kubernetes client api</li>
<li>kubernetes CLI</li>
<li>Kubernetes credentials provider</li>
</ul>
</li>
</ul>
</details></li>
<li><details><summary>Integration of EKS with Jenkins</summary>
<ul>
<li>Code</li>
<li>Code</li>
</ul>
</details></li>
<li>Deployment of zomato on EKS Cluster
<ul>
<li>Login to Jenkins and create a project.</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato2.yaml" target="_blank" rel="noopener">CI/CD yaml script</a>.</li>
<li></li>
<li>Build the CI/CD pipeline</li>
<li>Access the application</li>
</ul>
</li>
<li>Code</li>
</ul>
</details></li>
<li><details><summary>Deployment of application on EKS through ArgosCD</summary>
<ul>
<li>ArgoCD Installation:
<ul>
<li>In order to monitor k8s with Prometheus, we need to install ArgoCD.&nbsp; It is install in Kubernetes cluster.</li>
<li>Connect to kubernetes cluster and perform the following.</li>
<li>Create namespace:
<ul>
<li>$kubectl create namespace argocd</li>
</ul>
</li>
<li>Intstall ArgoCD:
<ul>
<li>$kubectl apply -n argocd -f <a href="https://raw.githubusercontent.com/argoproj/argo-cd/v2.4.7/manifests/install.yaml">https://raw.githubusercontent.com/argoproj/argo-cd/v2.4.7/manifests/install.yaml</a></li>
</ul>
</li>
<li>Load Balancer: Expose ArgoCD to the public through load balancer:&nbsp;By default the argo CD server is not publicly exposed, so we need to expose it publicly. To do that apply load balancer
<ul>
<li>$kubectl patch svc argocd-server -n argocd -p '{"spec": {"type": "LoadBalancer"}}'</li>
<li>or at command prompt, $kubectl patch svc argocd-server -n argocd -p "{\"spec\": {\"type\": \"LoadBalancer\"}}"</li>
<li>After successful execution you should see "patched"</li>
<li>Wait for 5 minutes for the load balancer creation. Once the loadbalancer is created, we will get the load balancer url.</li>
<li>Load Balancer URL =&nbsp;a19d070b0caf3445b929fb0a3dd3b2fe-850225668.eu-west-2.elb.amazonaws.com</li>
</ul>
</li>
<li>To see the pods available in the argocd namespace ----&gt;
<ul>
<li>$kubectl get pods -n argocd</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato16.jpg" alt="" width="964" height="230" /></li>
</ul>
</li>
<li>Access ArgoCD:
<ul>
<li>open browser and paste load balancer URL: a19d070b0caf3445b929fb0a3dd3b2fe-850225668.eu-west-2.elb.amazonaws.com</li>
</ul>
<ul>
<li>username: admin</li>
<li>Password: To get the password run the following command.
<ul>
<li>export ARGO_PWD=`kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d`</li>
<li>Execute the below command in powershell, if the command doesn't get executed in VS Code Editor<br />$env:ARGO_PWD = (kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | % { [System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String($_)) })</li>
<li>To see the password;<br />echo $ARGO_PWD</li>
</ul>
</li>
<li>You will see the password. copy and paste it in the argo cd homepage ---&gt;login</li>
<li>Change password:</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato18.jpg" alt="" width="404" height="230" /></li>
</ul>
</li>
<li>Add Repositories: Click on Manage your repositories, projects, settings
<ul>
<li>Click repositories/+ connect repo using https</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato19.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato19.jpg" alt="" width="403" height="306" /></a></li>
<li>Provide details and click connect.</li>
<li>Connection status: successful</li>
</ul>
</li>
<li>Manage your applications, and diagnose health problems.
<ul>
<li>+ New App</li>
<li>Application Name = zomato</li>
<li>Project Name = default</li>
<li>Sync Policy = Automatic</li>
<li>Repository URL =&nbsp;<a href="https://github.com/AbdulAziz-uk/zomato.git">https://github.com/AbdulAziz-uk/zomato.git</a></li>
<li>Revision = HEAD</li>
<li>Path = kubernetes (enter the folder name contain minifest files, deployment.yaml, node-service.yaml, service.yaml)</li>
<li>Estination/cluster url, drop down and select&nbsp;<a href="https://kubernetes.default.svc">https://kubernetes.default.svc</a></li>
<li>Namespace = default</li>
<li>click create.</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato20.jpg" alt="" width="320" height="157" /></li>
<li>folder name is Kubernetes (K in cap)</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato21.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato21.jpg" alt="" width="479" height="332" /></a></li>
</ul>
</li>
<li>Add a Job to Scrape Metrics on nodeip:9001/metrics in prometheus.yml:
<ul>
<li>Go to the monitoring server.</li>
<li>sudo vi /etc/prometheus/prometheus.yml</li>
<li>Paste the below commands at the bottom of screen.</li>
<li>- job_name: 'k8s'<br /> metrics_path: '/metrics'<br /> static_configs:<br /> - targets: ['nodeIP:9100']</li>
<li>In the above, to get the "nodeIP", go to EKS in AWS ----&gt; Click on EKS Cluster ----&gt; "Compute" tab ----&gt; Nodes ----&gt; Click on any one node ----&gt; Click on the "instance id" ----&gt; Copy the public ip ----&gt; Paste in the above script (18.170.35.125).&nbsp; The static_configs section specifies the targets to scrape metrics from, and in this case, it's set to nodeip:9001.</li>
<li>save &amp; exit</li>
<li>$promtool check config /etc/prometheus/prometheus.yml</li>
<li>You should see "Success"</li>
<li>Check the validity of the configuration file:</li>
<li>curl -X POST <a href="http://localhost:9090/-/reload">http://localhost:9090/-/reload</a></li>
</ul>
</li>
<li>Check Prometheus:&nbsp;
<ul>
<li>Goto Prometheus and reload.</li>
<li>Note: If you see error in Prometheus under "k8s", open port number 9100 for the EC2 instances which were created as part of EKS cluster i.e nodes.</li>
</ul>
</li>
<li>Check ArgoCD.&nbsp;
<ul>
<li>Goto ArgoCD and reload to see whether the pipeline is done or not.</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato22.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato22.jpg" alt="" width="596" height="334" /></a></li>
</ul>
</li>
<li>Copy the public ip of "nodeIP" which we have done exactly 4 steps above this line. copy of any public IP of node
<ul>
<li>Goto browser and paste it:30001</li>
<li>You will see the application</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" alt="" width="855" height="449" /></a></li>
<li>Application running on port 3000 is on Docker Container.</li>
<li>Application running on port 30001 is at kubernetes cluster.&nbsp; It has been defined in service.yaml in kubernetes folder of code repository.</li>
</ul>
</li>
</ul>
</li>
<li>code</li>
</ul>
</details></li>
<li><details><summary>Infra setup for monitoring</summary>
<ul>
<li>Launch VM: Name= Monitoring Server, Ubuntu 24.04, t2.large, InSecurity Group allow ports 3000 9090, EBS: 30GB</li>
<li>We will install Grafana, Prometheus, Node Exporter in the same instance and then we will monitor.</li>
<li>Connect to 'monitoring-server (192.168.171.104)' VM and perform the following.</li>
<li><details><summary>Installing Prometheus.</summary>
<ul>
<li>Switch to root user:
<ul>
<li>$sudo su</li>
</ul>
</li>
<li>Create a dedicated Linux user for Prometheus and download Prometheus.
<ul>
<li>$sudo useradd --system --no-create-home --shell /bin/false prometheus</li>
</ul>
</li>
<li>Download the prometheus tar file.
<ul>
<li>$wget <a href="https://github.com/prometheus/prometheus/releases/download/v2.47.1/prometheus-2.47.1.linux-amd64.tar.gz">https://github.com/prometheus/prometheus/releases/download/v2.47.1/prometheus-2.47.1.linux-amd64.tar.gz</a></li>
</ul>
</li>
<li>Extract the tar file:
<ul>
<li>$tar -xvf&nbsp;prometheus-2.47.1.linux-amd64.tar.gz</li>
</ul>
</li>
<li>Change directory to extracted folder
<ul>
<li>$cd prometheus-2.47.1.linux-amd64 (list of files &amp; folders)</li>
<li>console_libraries LICENSE prometheus promtool<br />consoles NOTICE prometheus.yml</li>
</ul>
</li>
<li>Make a directory.
<ul>
<li>$sudo mkdir -p /data /etc/prometheus</li>
</ul>
</li>
<li>Move the following files:
<ul>
<li>$ sudo mv prometheus promtool /usr/local/bin/</li>
<li>$sudo mv consoles/ consoles_libraries/&nbsp; /etc/prometheus/</li>
<li>$sudo mv prometheus.yml /etc/prometheus/prometheus.yml</li>
</ul>
</li>
<li>Set ownership for directories:
<ul>
<li>$sudo chown -R prometheus:prometheus /etc/prometheus/ /data/</li>
</ul>
</li>
<li>Create a systemd unit configuration file for Prometheus.
<ul>
<li>$sudo vi /etc/systemd/system/prometheus.service</li>
<li>Add the following which is required to run prometheus service.</li>
<li>
<p>[Unit]<br />Description=Prometheus<br />Wants=network-online.target<br />After=network-online.target</p>
<p>StartLimitIntervalSec=500<br />StartLimitBurst=5</p>
<p>[Service]<br />User=prometheus<br />Group=prometheus<br />Type=simple<br />Restart=on-failure<br />RestartSec=5s<br />ExecStart=/usr/local/bin/prometheus \<br /> --config.file=/etc/prometheus/prometheus.yml \<br /> --storage.tsdb.path=/data \<br /> --web.console.templates=/etc/prometheus/consoles \<br /> --web.console.libraries=/etc/prometheus/console_libraries \<br /> --web.listen-address=0.0.0.0:9090 \<br /> --web.enable-lifecycle</p>
<p>[Install]<br />WantedBy=multi-user.target</p>
</li>
<li>save the file.</li>
<li>Explanation of the key elements in the above prometheus.service file:<br />User and Group specify the Linux user and group under which Prometheus will run.<br />ExecStart is where you specify the Prometheus binary path, the location of the configuration file (prometheus.yml), the storage directory, and other settings.<br />web.listen-address configures Prometheus to listen on all network interfaces on port 9090.<br />web.enable-lifecycle allows for management of Prometheus through API calls.</li>
</ul>
</li>
<li>Enable and start Prometheus:
<ul>
<li>$sudo systemctl enable prometheus</li>
<li>$sudo systemctl start prometheus</li>
</ul>
</li>
<li>Verify Prometheus's status:
<ul>
<li>$sudo systemctl status prometheus</li>
<li>Active (running),&nbsp;Press Control+c to come out</li>
</ul>
</li>
<li>Access Prometheus, by default it runs on port 9090.
<ul>
<li>&nbsp;In browser using your server's IP and port 9090:&nbsp;</li>
<li><a href="http://192.168.171.104:9090">http://192.168.171.104:9090</a></li>
<li>user = admin, password=admin</li>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/prometheus/installation_script_1.jpg" target="_blank" rel="noopener"><img src="https://stardistributors.co.uk/devops/devops_tools/prometheus/installation_script_1.jpg" alt="" width="606" height="215" /></a></li>
<li>Click on 'Status' dropdown ---&gt; Click on 'Targets' ---&gt; You can see 'Prometheus (1/1 up)'</li>
</ul>
</li>
<li>Code</li>
</ul>
</details></li>
<li><details><summary>Installing Node Exporter.</summary>
<ul>
<li>$pwd (/root)</li>
<li>Create a system user for Node Exporter and download Node Exporter:
<ul>
<li>$sudo useradd --system --no-create-home --shell /bin/false node_exporter</li>
</ul>
</li>
<li>Download Node Exporter tar
<ul>
<li>$wget <a href="https://github.com/prometheus/node_exporter/releases/download/v1.6.1/node_exporter-1.6.1.linux-amd64.tar.gz">https://github.com/prometheus/node_exporter/releases/download/v1.6.1/node_exporter-1.6.1.linux-amd64.tar.gz</a></li>
</ul>
</li>
<li>Extract the tar.
<ul>
<li>$tar -xvf node_exporter-1.6.1.linux-amd64.tar.gz</li>
</ul>
</li>
<li>Move the files:
<ul>
<li>$sudo mv node_exporter-1.6.1.linux-amd64/node_exporter /usr/local/bin/</li>
<li>Delete the tar file.</li>
<li>$rm -rf node_exporter*</li>
</ul>
</li>
<li>Create a systemd unit configuration file for Node Exporter:
<ul>
<li>sudo vi /etc/systemd/system/node_exporter.service</li>
<li>Add the following content to the node_exporter.service file:</li>
<li>
<p>[Unit]<br />Description=Node Exporter<br />Wants=network-online.target<br />After=network-online.target</p>
<p>StartLimitIntervalSec=500<br />StartLimitBurst=5</p>
<p>[Service]<br />User=node_exporter<br />Group=node_exporter<br />Type=simple<br />Restart=on-failure<br />RestartSec=5s<br />ExecStart=/usr/local/bin/node_exporter --collector.logind</p>
<p>[Install]<br />WantedBy=multi-user.target</p>
</li>
<li>Note: Replace --collector.logind with any additional flags as needed.</li>
</ul>
</li>
<li>Enable and start Node Exporter:
<ul>
<li>$sudo systemctl enable node_exporter</li>
<li>$sudo systemctl start node_exporter</li>
</ul>
</li>
<li>Verify the Node Exporter's status:
<ul>
<li>$sudo systemctl status node_exporter</li>
<li>You can see "active (running)" in green colour</li>
<li>Press control+c to come out of the file</li>
</ul>
</li>
</ul>
</details></li>
<li><details><summary>Integration Prometheus plugin in Jenkins Server</summary>
<ul>
<li>As of now we created Prometheus service, but we need to add a job in order to fetch the details by node exporter. So for that we need to create 2 jobs, one with 'node exporter' and the other with 'jenkins' as shown below;</li>
<li>To configure Prometheus to scrape metrics from Node Exporter and Jenkins, you need to modify the prometheus.yml file.</li>
<li>$cd /etc/prometheus</li>
<li>$ls -l (console_libraries, Consoles, prometheus.yml)</li>
<li>$vim prometheus.yml (Edit prometheus.yml)</li>
<li>You will see the content and also there is a default job called "Prometheus" Paste the below content at the end of the file;</li>
<li>
<p>- job_name: 'node_exporter'<br /> static_configs:<br /> - targets: ['&lt;MonitoringVMip&gt;:9100']</p>
<p>- job_name: 'jenkins'<br /> metrics_path: '/prometheus'<br /> static_configs:<br /> - targets: ['&lt;your-jenkins-ip&gt;:&lt;your-jenkins-port&gt;']</p>
</li>
<li>save &amp; exit</li>
<li>zomato9.jpg</li>
<li>Check the validity of the configuration file:</li>
<li>$promtool check config /etc/prometheus/prometheus.yml
<ul>
<li>Checking /etc/prometheus/prometheus.yml<br /> SUCCESS: /etc/prometheus/prometheus.yml is valid prometheus config file syntax</li>
</ul>
</li>
<li>Reload the Prometheus configuration without restarting:
<ul>
<li>$curl -X POST http://localhost:9090/-/reload</li>
</ul>
</li>
<li>Access Prometheus in browser (if already opened, just reload the page):
<ul>
<li><a href="http://&lt;your-prometheus-ip&gt;:9090/targets">http://&lt;your-prometheus-ip&gt;:9090/targets</a></li>
<li>zomato10.jpg</li>
<li>You should now see "Jenkins (1/1 up)" "node exporter (1/1 up)" and "prometheus (1/1 up)" in the prometheus browser.</li>
<li>Click on "showmore" next to "jenkins." You will see a link. Open the link in new tab, to see the metrics that are getting scraped</li>
</ul>
</li>
</ul>
</details></li>
<li><details><summary>Installing Grafana.</summary>
<ul>
<li>$pwd (You are currently in /etc/Prometheus path.)</li>
<li>Install Dependencies, First ensure that all necessary dependencies are installed:.
<ul>
<li>$sudo apt-get update</li>
<li>$sudo apt-get install -y apt-transport-https software-properties-common</li>
</ul>
</li>
<li>Add the GPG Key:
<ul>
<li>cd enter (You are now in ~ path = /root)</li>
<li>Add the GPG key for Grafana:</li>
<li>$ wget -q -O - https://packages.grafana.com/gpg.key | sudo apt-key add -</li>
</ul>
</li>
<li>Add Grafana Repository:&nbsp;Add the repository for Grafana stable releases:
<ul>
<li>$echo "deb https://packages.grafana.com/oss/deb stable main" | sudo tee -a /etc/apt/sources.list.d/grafana.list</li>
</ul>
</li>
<li>Update and Install Grafana:
<ul>
<li>$sudo apt-get update</li>
<li>$sudo apt-get -y install grafana</li>
</ul>
</li>
<li>Start Grafana:
<ul>
<li>$sudo systemctl start grafana-server</li>
</ul>
</li>
<li>Check Grafana Status:&nbsp;Verify the status of the Grafana service to ensure it's running correctly:
<ul>
<li>$sudo systemctl status grafana-server</li>
<li>You should see "Active (running)" in green colour</li>
<li>Press control+c to come out</li>
</ul>
</li>
<li>Access Grafana Web Interface:
<ul>
<li>The default port for Grafana is 3000</li>
<li><a href="http://&lt;monitoring-server-ip&gt;:3000">http://&lt;monitoring-server-ip&gt;:3000</a></li>
<li>Default id and password is "admin"</li>
<li>You will see the Grafana dashboard</li>
</ul>
</li>
<li>The first thing that we have to do in Grafana is to add the data source.</li>
<li>zomato11.jpg</li>
<li>Click on DATA SOURCES (or click --&gt;Select Prometheus, make sure Enable "default" toogle bar, In Connection: Paste the Prometheus URL (<a href="http://192.168.171.104:9090">http://192.168.171.104:9090</a>) and remove / at the end of url,&nbsp;</li>
<li>Scroll down and click Save and test.&nbsp; If everything is fine, you will see "green" colour tick mark.</li>
</ul>
</details></li>
<li><details><summary>Add Dashboard</summary>
<ul>
<li>Click on Dashboards in the left pane, Add the following 2 dashboards.</li>
<li>Dashboard for Jenkins: use code 9964</li>
<li>Click on + sign on top right corner --&gt;import dashboard --&gt;dashboard URL or ID&nbsp;(<a href="https://grafana.com/grafana/dashboards/1860-node-exporter-full/">https://grafana.com/grafana/dashboards/9964-jenkins-performance-and-health-overview/</a>)&nbsp;--&gt;click load --&gt;select prometheus in prometheus section and import.</li>
<li>All the details of jenkins jobs will be displayed.</li>
<li>zomato13.jpg</li>
<li>Dashboard for Grafana Node Exporter: use ID 1860</li>
<li>Click on + sign on top right corner --&gt;import dashboard --&gt;dashboard URL or ID, (<a href="https://grafana.com/grafana/dashboards/1860-node-exporter-full/">https://grafana.com/grafana/dashboards/1860-node-exporter-full/</a>) --&gt;click load --&gt;select prometheus in prometheus section and import.</li>
<li>zomato12.jpg</li>
</ul>
</details></li>
<li>Code</li>
<li>code</li>
</ul>
</details></li>
<li><details><summary>Monitoring Kubernetes Cluster with Prometeus &amp; Grafana</summary>
<ul>
<li>
<p>Infrastructure has been setup in the previous step.</p>
</li>
<li>
<p>Additionally, will install the node exporter using Helm to collect metrics from kubernetes cluster nodes.</p>
</li>
<li>Helm installed on first VM.
<ul>
<li>Install &amp; configure Helm:
<ul>
<li>$curl -fsSL -o get_helm.sh <a href="https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3">https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3</a></li>
<li>$sudo chmod 700 get_helm.sh</li>
<li>$sudo ./get_helm.sh</li>
</ul>
</li>
<li>$helm version</li>
</ul>
</li>
<li>Install Node Exporter using Helm.</li>
<li>Add the Prometheus Community Helm repository:
<ul>
<li>$helm repo add prometheus-community <a href="https://prometheus-community.github.io/helm-charts">https://prometheus-community.github.io/helm-charts</a></li>
<li>"prometheus-community" has been added to your repositories</li>
</ul>
</li>
<li>Create a Kubernetes namespace for the Node Exporter:
<ul>
<li>$kubectl create namespace prometheus-node-exporter</li>
</ul>
</li>
<li>Install the Node Exporter using Helm:
<ul>
<li>$helm install prometheus-node-exporter prometheus-community/prometheus-node-exporter --namespace prometheus-node-exporter</li>
<li><img src="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato17.jpg" alt="" width="1146" height="332" /></li>
</ul>
</li>
<li>Lets continue with load balancer thing of previous step; execute the below.
<ul>
<li>export ARGOCD_SERVER=`kubectl get svc argocd-server -n argocd -o json | jq --raw-output '.status.loadBalancer.ingress[0].hostname'`</li>
<li>Execute the below command in powershell, if the command doesn't get executed in VS Code Editor<br />$env:ARGOCD_SERVER = $(kubectl get svc argocd-server -n argocd -o json | jq --raw-output '.status.loadBalancer.ingress[0].hostname')</li>
</ul>
</li>
<li>To get the loadbalancer url;
<ul>
<li>echo $ARGOCD_SERVER</li>
<li>Execute the below command in powershell, if the command doesn't get executed in VS Code Editor<br />echo $env:ARGOCD_SERVER</li>
<li>a19d070b0caf3445b929fb0a3dd3b2fe-850225668.eu-west-2.elb.amazonaws.com (you can get this url from AWS console/load balancer)</li>
</ul>
<ul>
<li><a href="https://stardistributors.co.uk/devops/devops_tools/projects/Zomato/zomato1.jpg" target="_blank" rel="noopener">&nbsp;</a></li>
</ul>
</li>
<li>code</li>
</ul>
</details></li>
</ul>
</details></li>

