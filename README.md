the data are organized like:
```
{
"bambara": [array of sentences or paragraph], 
"boomu": [array of sentences or paragraph], 
....

}
```

```bash 
    git clone https://github.com/mlsftwrs/malian-languages-text
    cd malian-languages-text
```

```python
    import json
    data = json.load(open("malian-languages-text.json"))
```

list of languages:
- bambara
- boomu
- songhoy
- sonoufo
- kanabere
- minianka
- khassonke
- dogon
- fulfulde
- tamasheq

