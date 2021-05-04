# ansible-testing
ansible.cfg on fail, mis ütleb ära, kus on inventory fail(hetkel samas kaustas) ja määrab ka võtme asukoha.<br />
inventory fail määrab ära kõik hostid, mida ansiblega kontrollida. <br />
install_apache.yml - fail mis installib apache ja vajaliku komponendid ansiblega kõikidesse serveritesse. <br />
remove_apache.yml - fail, mis eemalbad apache koos teiste komponentidega serveritest. <br />
install_apache_v2 - koledam .yml fail, mis määrab ära, et tegevust teostatakse ainult inventorys olevatele web_server grupis olevatele serveritele.<br />
