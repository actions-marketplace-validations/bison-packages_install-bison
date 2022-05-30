## GitHub action to install bison

This action downloads pre-compiled ditribution of Bison, un-tars it and adds to `$PATH`.

### Usage

```yml
      - name: setup bison
        uses: bison-packages/install-bison@v1
        with:
          version: '3.8.2'
```
