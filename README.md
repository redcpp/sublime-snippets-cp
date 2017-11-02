# Sublime 3 Snippets for Competitive Programming

This is a collection of python snippets that aim to reduce the time of creation of test cases for competitive programming.
All snippets begin with the **gen** prefix.

### Example

```python
genperm<Tab>
```

Autocompletes to the code to generate a random permutation of integers [1, N]:

```python
seq = list(range(1, N+1))
shuffle(seq)
print( ' '.join( map(str, seq) ) )
```

### Instalation

Download the repository contents as .zip to the sublime user snippets directory

`wget https://github.com/redcpp/sublime-snippets-cp/archive/master.zip -P ~/.config/sublime-text-3/Packages/User/`

Unzip the contents

`unzip ~/.config/sublime-text-3/Packages/User/master.zip`

Remove the zip file (optional)

`rm ~/.config/sublime-text-3/Packages/User/master.zip`
