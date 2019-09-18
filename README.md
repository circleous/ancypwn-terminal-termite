Termite terminal plugin for ancypwn

# dependencies
1. termite
2. python3
3. pip3

# installation
1. From pypi,
```
pip install ancypwn_terminal_termite
```
2. From git,
```
git clone https://github.com/circleous/ancypwn-terminal-termite
cd ancypwn-terminal-termite/
pip install .
```

# usage
Inside your exploit.py or script, add the following line
```python
context.terminal = ['ancyterm', '-s', 'localhost', '-p', '-t', 'termite', '-e']
```