Siin repositooriumis on erinevad skriptid, mida saab kasutada ansible serveris.
Näiteks apache2 installeerimine, mysql serveri installeerimine ja mysql andmebaasi kasutaja loomine, wordpressi installeerimine ja phpmyadmin installeerimine.
Ansible skriptide käivitamiseks kasutatakse käsku "ansible-playbook" ja siis .yml skripti faili nimi. Näiteks "ansible-playbook /etc/ansible/playbooks/apache2.yml".
Ansible playbook-ide puhul on see hea, et ei pea uuesti sisetama kõiki käske, et installeerida midagi, vaid saab kasutada ansible serverit, et installeerida automaatselt.
