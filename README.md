# ml-big-data-lab-3

Лабортаорная № 3. РАЗМЕЩЕНИЕ СЕКРЕТОВ В ХРАНИЛИЩЕ

Цель: Получить навыки размещения секретов в хранилище и взаимодействия с ним.

Стек: Python 3.10, Jupyter, FastApi, redis, scikit-learn, DVC, Docker, Jenkins, Ansible Vault

[Письменный отчет](static/ИБД-Лаб-3.pdf)

## Ansible Vault

```python
pip install ansible-vault-win
```

## Encrypt

```bash
ansible-vault encrypt env/secrets.env --vault-pass-file env/.vault-pass
```

## Decrypt

```bash
ansible-vault decrypt env/secrets.env --vault-pass-file env/.vault-pass
```
