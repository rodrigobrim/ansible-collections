# Requisitos para usar esse collection

1. Ansible 2.9+ instalado
2. Packer 1.6+ instalado e disponível no PATH
3. Virtualbox 5.0+

# Como usar

1. Faça o download do collection: `ansible-galaxy collection install rodrigobrim.packer_vagrant_images`
2. Preencha as seguintes variáveis para cada role:

## virtualbox_build
```
virtualbox_build_path: "{{ ansible_env.PWD }}"
virtualbox_build_username: "{{ vagrant_cloud_username }}"
virtualbox_build_box_name: "{{ box_name }}"
virtualbox_build_json: "{{ packer_build_vagrant_json }}"
```
