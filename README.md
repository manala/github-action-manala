# GitHub Action - Manala

## Usage

Setup & Update:

```yaml
...
- name: Manala update
  uses: manala/github-action-manala@v1
  with:
    directory: foo  # Optional working directory 
...
```

Setup only:

```yaml
...
- name: Set up manala
  uses: manala/github-action-manala/setup@v1
...
```

Update only:

```yaml
...
- name: Manala update
  uses: manala/github-action-manala/update@v1
  with:
    directory: foo  # Optional working directory 
...
```
