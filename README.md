# Controller test project for henryorgtesting.server_test

This is a small project you can import into Controller (AAP) to test your new collection.

## Files

- `playbooks/test_access_and_zip.yml` : runs the role in the collection
- `inventory/hosts.yml` : example inventory (edit your host)
- `collections/requirements.yml` : tells Controller to install the collection from Automation Hub

## Typical steps in Controller

1. Add Credential (Machine / Windows / etc.)
2. Add Inventory (or use this example)
3. Add Project (upload this zip, or connect to SCM)
4. Create Job Template pointing to `playbooks/test_access_and_zip.yml`
