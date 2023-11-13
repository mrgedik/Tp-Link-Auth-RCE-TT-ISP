# TurkTelekom TP-Link Modems - Authenticated Remote Code Execution Vulnerability

"A Auth-based RCE vulnerability is a security flaw that allows a user with limited access to a system or application to execute code beyond their permissions. These vulnerabilities enable an attacker to execute any code they want on a remote server. Such vulnerabilities typically arise due to a lack of security controls in software, inadequate input validation, or poor system configuration.

In TP-Link Türktelekom modems, after logging in, a command injection vulnerability has been identified in the "connName" input field, which is an Interface parameter in the IP & Domain Test module under the System Tools Menu, using the expressions "$(command)" and "\`command\`" .

<img width="1489" alt="1" src="https://github.com/mrgedik/Tp-Link-Auth-RCE-TT-ISP/assets/46036678/0a7cb10c-a06c-47d3-99a5-3a1b7e72ed3e">
<img width="1481" alt="2" src="https://github.com/mrgedik/Tp-Link-Auth-RCE-TT-ISP/assets/46036678/0e7be619-6ebf-41aa-a420-bb72aa336a37">
<img width="984" alt="3" src="https://github.com/mrgedik/Tp-Link-Auth-RCE-TT-ISP/assets/46036678/df6b1a08-2252-4a59-89aa-6f9a622563b5">
