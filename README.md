# school-festival
文教大学　学祭　null2x Web制作

# CentOS7.3 install手順
`http://ftp.jaist.ac.jp/pub/Linux/CentOS/7.3.1611/isos/x86_64/CentOS-7-x86_64-DVD-1611.iso`  
`https://www.server-world.info/query?os=CentOS_7&p=install`  
`上記サイトを参考に、インストールを願います。GUIが良い方はソフトウェアの選択でGUIを選んでください`  

# Ansible構築　手順
`1.yum -y install ansible`  
`2.cd /etc/ansible`
`3.git clone https://github.com/yukiafronia/school-festival-SSH-Key.git`  
`4.wordpress-nginx_rhel7内のhosts内容を変更する。変更内容はIPアドレス`  
`5.ansible-playbook -i hosts -u root --ask-pass site.yml`  
