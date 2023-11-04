# Ansible-molecule

Template ansible molecule and testinfra.

---

## Prepare

```bash
python3 -m pip install --user molecule==5.1.0 molecule-docker==2.1.0 ansible-core==2.15.2 ansible-compat==4.1.5 testinfra==6.0.0
```

## Development

```bash
molecule test      # Create molecule instance, converge, test and destroy
molecule converge  # Molecule converge, without destroy instance
molecule verify    # Run test on molecule instance
molecule destoy    # Destroy molecule instance
```
