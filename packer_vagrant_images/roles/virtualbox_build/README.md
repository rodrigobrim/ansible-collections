# Defina as seguintes variáveis para chamar a role

```
vars:
  virtualbox_build_path: "{{ ansible_env.PWD }}"
  virtualbox_build_username: "{{ vagrant_cloud_username }}"
  virtualbox_build_box_name: "{{ box_name }}"
  virtualbox_build_json: "{{ packer_build_vagrant_json }}"
```
