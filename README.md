### How to use (in Ubuntu 18.04 / you maybe need administer rights)
1. Install suricata by "apt install suricata"
2. Copy 'suricata.yaml' to /etc/suricata
3. Copy 'test.rules' to /etc/suricata/rules
4. Execute suricata by "sudo suricata -c /etc/suricata/suricata.yaml -i \<interface\>"
