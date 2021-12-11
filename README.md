
############# Install elasticsearch ############################
1-cd /etc/yum.repos.d/
2-sudo vim elasticsearch.repo
3-save file
4-sudo dnf install elasticsearch
5-sudo systemctl start elasticsearch
6-sudo systemctl enable elasticsearch

############# Install kibana ############################
1-sudo dnf install kibana
2-sudo systemctl start kibana
3-sudo systemctl enable kibana

##############Install and Set Up Logstash ################
1-sudo dnf install logstash
2-sudo systemctl start logstash
3-sudo systemctl enable logstash
#########################Install Filebeat ##########################
1-sudo yum install filebeat
2-sudo filebeat modules enable system
3-sudo filebeat setup
4-sudo service filebeat start
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
refer-https://phoenixnap.com/kb/install-elk-stack-centos-8
