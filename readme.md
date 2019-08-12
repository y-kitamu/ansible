# ansible の playbook 集

## Install

- ubuntu/ubuntu_initialsetup.yml : デスクトップ ubuntu の初期設定用の playbook

```shell
ansible-playbook -i inventory/inventory ubuntu_initialsetup.yml --ask-vault-pass
```
TODO:
- emacs の install
- dotfiles の install
- パッケージの洗い出し

## Reference
- Ansible 実践ガイド
