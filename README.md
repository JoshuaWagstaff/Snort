Objective

The primary goal of the Snort Intrusion Detection Lab project was to gain a deep understanding of real-time network-based threat detection using Snort. The project focused on analyzing live network traffic to identify and block malicious activity by developing and deploying custom Snort rules. Through hands-on configuration and rule writing, the lab aimed to enhance detection accuracy, improve incident response capabilities, and contribute to building a proactive network security posture.

Skills Learned

Fundamental knowledge of Snort architecture, rule syntax, and operational modes.

Proficiency in writing custom Snort rules to detect and block various forms of network-based attacks, including port scans, brute force attempts, and malware communication.

Ability to analyze packet captures and network traffic to identify suspicious patterns and behaviors.

Experience in configuring Snort for real-time intrusion detection and prevention.

Enhanced understanding of protocol analysis, traffic filtering, and signature-based detection.

Skills in interpreting Snort alerts and logs to understand and respond to ongoing threats.

Development of analytical thinking and problem-solving skills in live threat environments.

Tools Used

Snort: Used as the primary intrusion detection/prevention system to analyze network traffic in real time and detect/block malicious activity using custom rules.

Snort Rules: Created and tuned to detect specific attack signatures, such as reconnaissance scans, DoS attempts, and unauthorized access attempts.

Linux Environment: Provided the platform for running Snort, simulating attacks, and managing network configurations.



Steps

---
<img width="320" alt="1 - scenario p 1" src="https://github.com/user-attachments/assets/4e330fbe-33c6-4e37-b107-83773e2fd9c7" />
p.1 scenario

---

<img width="325" alt="2- scenario p 2" src="https://github.com/user-attachments/assets/af3240ee-4ffd-4390-93ad-57171e22a906" />
p.2- scenario p.2

---

<img width="629" alt="3- varlogsnort - running dev mode" src="https://github.com/user-attachments/assets/f8e9aa16-0213-4dd1-b4d4-f6db3e96f459" />
p.3- varlogsnort- running dev mode

---

<img width="569" alt="4- ssh spotted in live feed from running sudo snort -dev" src="https://github.com/user-attachments/assets/304a5bca-b7f2-4ecc-899f-2dced09d6b7f" />
p.4- ssh spotted in live feed from running command

---

<img width="787" alt="5- creating local rule folder" src="https://github.com/user-attachments/assets/83c7a170-0f07-4cb0-9986-68cb4afc07e7" />
p.5- creating local rule folder

---

<img width="658" alt="6 - wrote rule to catch ssh traffic" src="https://github.com/user-attachments/assets/917760b5-6628-4a53-8241-ac0fdcbf146d" />
p.6- wrote rule to catch ssh traffic

---

<img width="802" alt="7- command on local rules" src="https://github.com/user-attachments/assets/50128783-fc92-46cf-b3b3-f2fb52a3294e" />
p.7- command on local.rules

---

<img width="521" alt="8- cat alert" src="https://github.com/user-attachments/assets/3ba3d8d4-32f2-4a61-ab38-d9530c6ec3f7" />
p.8- cat alelrt

---

<img width="899" alt="9- flag one" src="https://github.com/user-attachments/assets/7998ca86-575a-4870-957d-3819dc1f58f6" />
p.9- flag one

---

<img width="370" alt="10- attack one neutralized -all flags" src="https://github.com/user-attachments/assets/42eb68b8-e7f9-4b78-b597-a8908eba2d65" />
p.10 - attack one neutralized (all flags)

---

<img width="555" alt="11- scenario (second task)" src="https://github.com/user-attachments/assets/b20cd765-a34e-416c-a3c7-dfca943e11a8" />
p.11 -scenario (second task)

---

<img width="541" alt="12- scenario 2 p 2" src="https://github.com/user-attachments/assets/b6bfe8a7-5864-4b27-b458-522a5255c7fa" />
p.12 - scenario p.2

---

<img width="800" alt="13- cd varlogsnort then traffic with sudo snort -dev" src="https://github.com/user-attachments/assets/ad6eb05c-c17d-4e65-b2aa-f296eed0abaa" />

p.13 running varlogsnort then traffic with sudo snort -dev

---

<img width="615" alt="14-- port 4444 (metasploit) questionable traffic" src="https://github.com/user-attachments/assets/2a60463d-5bb7-45f8-9437-27789658f460" />
p.14- port 4444 (metasploit) questionable traffic

---

<img width="500" alt="15- creating local rule to block port command" src="https://github.com/user-attachments/assets/127881de-27c2-451c-a4d9-fe14f64ae579" />
p.15- craating local rule to block port command 

---

<img width="746" alt="16- rule for blocking port" src="https://github.com/user-attachments/assets/1309d92e-5d9b-4992-98ac-98b4628e740b" />
p.16 rule for blocking port

---
<img width="582" alt="17- running rule for alerts" src="https://github.com/user-attachments/assets/9ab2bbca-e045-4d0c-a5dd-62589d4bd3af" />
p.17- running rule for alerts

---

<img width="431" alt="18- alerrts received" src="https://github.com/user-attachments/assets/7bd2d214-d528-4cc9-9842-450414252532" />
p.18- alerts received

---

<img width="534" alt="19- viewing our alert (blocked traffic" src="https://github.com/user-attachments/assets/d5e4184c-e872-4f5d-b303-edfadc708fb8" />

p.20- viewing alert (lbocked traffic)

---
<img width="695" alt="20- flag received" src="https://github.com/user-attachments/assets/7b31baaa-1acd-48ff-a79d-a62571d2929e" />

20- flag received

---

<img width="440" alt="21- all questions answered" src="https://github.com/user-attachments/assets/4ed5c2f3-9bf2-4846-8943-5b6869ecc328" />
21- all questions answered




