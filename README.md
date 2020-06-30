# Ansible AWX Sample Playbook

Playbooks de "Hello Word" para execuções de teste no Ansible AWX (Tower).

## hello_world.yml

Afeta maquinas Debian, obtém informacoes como user, hostname e IP externo, testa e instala alguns pacotes (git, NGINX e HTOP).

## awx-manage.yml

Testa a capacidade de bulk import de inventario do awx-manage (disponível nos containers do AWX ou compilados a partir do código fonte) para importar um arquivo de texto e adicionar a um inventario existente sobrescrevendo com a ultima versão do arquivo.
